# 2019 eICU/eRI Collaborative Research Workshop (23rd September 2019, Colorado)

## Documentation

Documention for the eICU Collaborative Research Database is available at: [https://eicu-crd.mit.edu/](https://eicu-crd.mit.edu/).

## Preparation

During the workshop, you will explore the eICU Collaborative Research Database using two cloud services: BigQuery and Colab. To get started, please follow the steps below:

1. Create a [Gmail account](https://www.google.com/gmail/about/), if you don't already have one. It will be used to manage your access to the resources.
2. Give your gmail address to the session hosts.

## Exploring data with BigQuery

BigQuery is a database system that makes it easy to explore data with Structured Query Language ("SQL").

1. [Open BigQuery](https://console.cloud.google.com/bigquery?project=philips-eicu-meeting-2019)
2. Run a query. For example, try counting the number of hospital admissions in the demo eICU dataset:

   ```SQL
   SELECT count(*)
   FROM `physionet-data.eicu_crd_demo.patient` 
   ```

## Exploring data with executable notebooks

Python is an increasingly popular programming language for analysing data. We will explore the data using Python notebooks, which allow code and text to be combined into executable documents. 

Several tutorials are provided below. Requirements for these notebooks are: (1) you have a Gmail account and (2) your Gmail address has been added to the appropriate Google Group by the workshop hosts.

* [01-accessing-the-data.ipynb](https://colab.research.google.com/github/MIT-LCP/philips-eicu-meeting-2019/blob/master/tutorials/eicu/01-accessing-the-data.ipynb)
* [02-explore-patients.ipynb](https://colab.research.google.com/github/MIT-LCP/philips-eicu-meeting-2019/blob/master/tutorials/eicu/02-explore-patients.ipynb)
* [03-severity-of-illness.ipynb](https://colab.research.google.com/github/MIT-LCP/philips-eicu-meeting-2019/blob/master/tutorials/eicu/03-severity-of-illness.ipynb)
* [04-summary-statistics.ipynb](https://colab.research.google.com/github/MIT-LCP/philips-eicu-meeting-2019/blob/master/tutorials/eicu/04-summary-statistics.ipynb)
* [05-prediction.ipynb](https://colab.research.google.com/github/MIT-LCP/philips-eicu-meeting-2019/blob/master/tutorials/eicu/05-prediction.ipynb)

## R 

Datasets can also be queried directly from R. This is shown in the following R markdown notebook: [mimic-iii-los.Rmd](https://colab.research.google.com/github/MIT-LCP/philips-eicu-meeting-2019/blob/master/tutorials/mimic-iii/mimic-iii-los.Rmd)
