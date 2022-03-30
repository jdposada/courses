---
title: Week 4
date: '2021-01-01'
type: book
weight: 40
---

Clinical Data and Standardization

<!--more-->

{{< icon name="clock" pack="fas" >}} 2 - 4 Hours

## Class Content

In this class we will explain in more detail the role of ontologies in the content of standardizing data elements from EHR and claims data. We will zoom in into the [OMOP-CDM](https://ohdsi.github.io/TheBookOfOhdsi/CommonDataModel.html) data model and the need of an ETL from source data to this model. 

## Assignments

- Last week there was a bug in the page and the assignments were not there. Please take a look at **week 3** assignments and be sure you have done all of them. 
- Open an account on [Athena](https://athena.ohdsi.org/) with your university email and navigate the interface to become familiar with it.
- Create an [HL7 V2](https://www.hl7.org/implement/standards/product_brief.cfm?product_id=185) message with a piece of your information a of course some fake one.
- Finish all the steps to access MIMIC III and MIMIC IV data.
- Follow the instructions on this [Github Repository](https://github.com/jdposada/bioinf_202210). We will use this repo the entire semester

### In-Class Activity

- Given the class size we will divide in four groups each group will have a different but related assignment. By the end of the class it is expected that all the code will be pushed to a single GitHub repository
    - *Group 1:* Download the [MIMIC IV OMOP-CDM demo dataset](https://physionet.org/content/mimic-iv-demo-omop/0.9/) and load it into a SQL Lite Database using [RSQLite](https://cran.r-project.org/web/packages/RSQLite/vignettes/RSQLite.html)
    - *Group 2:* Download the [MIMIC IV OMOP-CDM demo dataset](https://physionet.org/content/mimic-iv-demo-omop/0.9/) and produce a graph like the one below for conditions and procedures
    - *Group 3:* Download the [MIMIC IV OMOP-CDM demo dataset](https://physionet.org/content/mimic-iv-demo-omop/0.9/) and produce a graph like the one below for drugs and measurements
    - *Group 4:* Run the [OHDSI Data Quality Dashboard](https://github.com/OHDSI/DataQualityDashboard) to Visualize the file(`results_MIMICIVdemo210426.json`) generated when running the tool on the demo data. The file is part of the [MIMIC IV OMOP-CDM demo dataset](https://physionet.org/content/mimic-iv-demo-omop/0.9/)

*Example of graph to be generated for Groups 2 and 3*
{{< figure src="tree_map_conditions.png" >}}

## Readings

- Read sections [4](https://ohdsi.github.io/TheBookOfOhdsi/CommonDataModel.html#CommonDataModel) and [4.1](https://ohdsi.github.io/TheBookOfOhdsi/CommonDataModel.html#design-principles) of the OHDSI book


## Learn

The [EHDEN academy](https://academy.ehden.eu/) is an excellent resource to expand your knowledge on the OMOP-CDM. Please check it out and hopefully you peek into some videos for courses like the OMOP-CDM and Standardized vocabularies. 

A short video about *Lessons Learned Converting Patient-Level Data to the OMOP Common Data Model to Support the COVID-19 Crisis*

{{< youtube c08rXeUyFWM >}}
