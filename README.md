# Bertelsmann/Arvato - Customer Segmentation Project

This project delivers a report for a better customer segmentation process based on supervised Machine Learning models. Arvato Financial Solutions, a Bertelsmann subsidiary.


##  Installations

This project requires **Python 3.x** and the following Python libraries installed:

- [Numpy](https://www.numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Pandas](http://pandas.pydata.org)
- [scikit-learn](http://scikit-learn.org/stable/)


## Overview:
Arvato Financial Solutions which is a Bertelsmann subsidiary provides a big dataset of population and customers with tremendeous amount of features. The report should find characteristics that enable to differente their customers from the rest of the population, with the final objective of beeing able to better target new potential customers. 

This work is part of the Captsone project for the 2nd term of the Udacity Data Science Nanodegree Program. 

Project is divided into two components : 

- 1. A Jupyter notebook in python which conducts the analysis and contains the models. There are three main sections : 
	- 

- 1.**Customer Segmentation Report**:  This section is dedicated to data preprocessing and building of unsupervised models in order to differente the company's customers from the general population. The two two mains datasets are a table of Customers, and a table of General Population (both with several hundreads of thousands of entries)
- 2.**Supervised Learning Model**:  The second section is used to build a supervised model for prediction if a person is a good target for a mail-compaign. In orther words, to predict those clients that are likely to become new customers. For that a new TRAIN dataset is provided.
- 3.**Kaggle Competition**?: Taking part to a kaggle competition with a TEST dataset provided ans see how the developed model performs amongst others.

Summary of the findings are published in the article linked below [Medium]().


## Datasets

- 'Udacity_AZDIAS_052018.csv': Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).
- 'Udacity_CUSTOMERS_052018.csv': Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).
- 'Udacity_MAILOUT_052018_TRAIN.csv': Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).
- 'Udacity_MAILOUT_052018_TEST.csv': Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).
- 'DIAS Attributes - Values 2017.xls' : Description of features from the population and customers data.

We are not allowed to publish the data provided by Arvato Financial Services due to the terms and conditions.

## Author

-   **Christopher Hogendijk**


## Acknowledgments

I am very grateful to Udacity for enabling me to better understand and enjoy the world of datascience and software engineering. I also thank Arvato Financial Solutions for providing this dataset that allowed us to conduct a real-world-like analysis and to develop cool models.
