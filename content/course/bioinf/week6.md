---
title: Week 6
date: '2021-01-01'
type: book
weight: 40
---

Week 6: Data Processing and Feature generation with clinical data

<!--more-->

{{< icon name="clock" pack="fas" >}} 2 - 4 Hours

## Class Content

In this class we will start describing the methods used to process EHR data and generate features with it.

## Assignments

- Read all the mandatory readings
- Contribute to our Github repository by taking the code generated in week 4 class activity and merging everything in a single .Rmd in our class [repo](https://github.com/jdposada/bioinf_202210). For doing that your first need to `fork` and then perform a `pull request`. The route for the file we will be editing together is `bioinf_202210/src/assigment1.Rmd`


## Readings

- Mandatory Readings
    - Get acquainted with the [Feature Extraction](https://ohdsi.github.io/FeatureExtraction/articles/UsingFeatureExtraction.html) OHDSI package. You just need to read and if you wish you could follow along some of the examples using the sample Eunomia Dataset. 
        - [Here](https://ohdsi.github.io/FeatureExtraction/reference/createCovariateSettings.html) is the portion of the documentation that describes how the features are generated
        - [Here](https://github.com/OHDSI/FeatureExtraction/blob/main/inst/csv/PrespecAnalyses.csv) is the pre-specified analyses CSV. The SQL files mentioned there are very hard to read because they are supporting a wide range of use cases. 
    - Read the articles:
        - [Population-Level Prediction of Type 2 Diabetes From Claims Data and Analysis of Risk Factors](https://people.csail.mit.edu/dsontag/papers/RazavianEtAl_BigData15.pdf)
            - [GitHub Repository](https://github.com/clinicalml/omop-learn)
        - [Democratizing EHR analyses with FIDDLE: a flexible data-driven preprocessing pipeline for structured clinical data](https://academic.oup.com/jamia/article/27/12/1921/5920826?login=false)
            - [GitHub Repository](https://github.com/MLD3/FIDDLE)

**Note:** If you do not understand everything is ok. We will discuss the packages and papers during class


## Learn


