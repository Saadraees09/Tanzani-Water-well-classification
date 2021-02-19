# Tanzania Waterpoint Operational Status

## Phase 3 Project
### Flatiron Online Data Science Bootcamp

Prepared and presented by: [Saad Raees](https://www.linkedin.com/in/saad-raees-19b1231a9/) (full time Data Science student)

Presentation: [here](https://docs.google.com/presentation/d/15tefq3OIQ0aiemq4IUCQiW8P1u8KvS9LVE3gPtKSVGA/edit#slide=id.gbdda438371_0_863)



![water](images/pexels-photo-2837863.jpeg)

![tanzania_map](images/tanzania-map.gif)


# Introduction

The goal of this project is to use data from the Tanzania Ministry of Water to gain insight into the country's waterpoints.   

The Stakeholders for my project are Tanzania Ministry of Water officals who want a dashboard view of the country's offical waterpoints. Addtionally, the officals want to know if Classifer can be created using the current data to predict waterpoint operational status. A data-supported understanding of which waterpoints may be more likely to fail can improve maintenance operations and ensure that clean, potable water is available to communities across Tanzania.


# Data Description

Data Set Used: Waterpoint data for the Republic of Tanzania:
* tza_waterpoint_train.csv
    * 59400 records in Original Training Set
* tza_waterpoint_test.csv
    * 14850 records in Original Test Set
* Data is from the [Pump It Up: Data Mining the Water Table Challenge hosted on DrivenData](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/page/23/)


# EDA Questions Explored
### Question 1: What is the operational status of waterpoints in Tanzania?
#### [Notebook](./Phase_3_project_Saad/EDA.ipynb)


### Question 2: What is the reported Quality and Quantity of Working (Functioning and Functioning Needs Repair) waterpoints?
#### [Notebook](./Phase_3_project_Saad/EDA.ipynb)


### Question 3: Is there a difference between the average age of Waterpoints by Operation Status?
#### [Notebook](./notebooks/EDA.ipynb)



# Modeling
### Can current data on waterpoints be used to create a Classifer to predict operational status?
#### [Notebook](./Phase_3_project_Saad/Modelling.ipynb)



# Next Steps/Future Work

Futher analysis into the following areas could yield additional insights.

* __idea 1__  Futher Analysis into Working waterpoints:
    * What are the water sources? 
    * Who are the major installers?
    * Who are the major management groups?
    * Who are the major scheme managers?

* __idea 2__  Water Availability Analysis:
    * How many people use waterpoints? By Country, Region, District, Ward, etc. 
    * How many people use lower Quality/Quantity waterpoints? By Country, Region, District, Ward, etc. 
    * What do we know about the payment types? By Country, Region, District, Ward, etc.


# For More Information
* Review the non-technical presentation [here](https://docs.google.com/presentation/d/15tefq3OIQ0aiemq4IUCQiW8P1u8KvS9LVE3gPtKSVGA/edit#slide=id.gbdda438371_0_863)


* Contact the author [Saad Raees](https://www.linkedin.com/in/saad-raees-19b1231a9/)


# Repository Structure
```
--notebooks
----Data cleaning and EDA prep.ipynb
----EDA.ipynb
----Modekling.ipynb
--data
----train_processed_values.csv
----test_processed_values.csv
----final_submission.csv
----original (dir for raw data downloaded from challenge website)
--extras (dir for Project Presentation and other supporting files)
```
