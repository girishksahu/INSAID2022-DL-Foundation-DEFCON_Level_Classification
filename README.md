# INSAID2022-DL-Foundation-DEFCON_Level_Classification
INSAID 2022 Deep Learning Foundation Term Project
# Project Description
## Introduction
- Your client for this project is a major modern armament manufacturer.
    - Military conflict is an intense state of violence. In such situations, it is crucial for a nation to stay alert, cope with it, and mitigate its implications.
    - The US government has set up the DEFCON (Defense Readiness Condition) warning system.
    - This alert system is used to gauge the level of alertness of the defence forces.
    - It consists of five levels of readiness for the military forces to be prepared for the consequences of the conflict.

## Current Scenario
- The government is trying to build a better defence system by automating most of the process.
- One of the processes they are working on is the DEFCON (Defence Readiness Condition) alert system. 
- The DEFCON system allows the nation’s forces to be a step ahead of its rivals.

## Problem Statement
The current process suffers from the following problems:

- The US government has created a DEFCON alert system previously but they have to go through a manual check to gauge the level of the DEFCON.

    - Due to these reasons, it is quite difficult to have an efficient prediction of the DEFCON level.

 - The company has hired you as a data science consultant.

    - They want to automate the process of predicting the DEFCON level of the country security, based on the military data

## Project Task
* Dataset contains synthesized data that can be used to build a model that can accurately predict the DEFCON level raised as a result of the conflict.
* Project task is to build a classification model for predicting DEFCON Level.
## Project Deliverables
- Deliverable: **Predict the DEFCON level of a country.**
- Machine Learning Task: **Classification**
- Target Variable: **DEFCON_Level**
## Evaluation Metric
* The model evaluation will be based on the Accuracy score.
# Data Description
* The columns contains all the necessary information that can be used to build a model that can accurately predict the DEFCON level raised as a result of the conflict.
* The column DEFCON_Level is the level of readiness for the military forces.

The dataset is divided into two parts: Train and Test sets.

## Train Set:
* The train set contains 8000 rows and 13 columns.
* The column DEFCON_Level is the target variable.

## Test Set:
* The test set contains 2000 rows and 12 columns.
* The test set doesn’t contain the DEFCON_Level column.
* It needs to be predicted for the test set.

# Dataset Feature Description
The Dataset contains the following columns:

| ID | Feature Name | Description of the feature |
| :-- | :--| :--| 
|01| **Allied_Nations**   | The number of nations that have joined together as allies          |
|02| **Diplomatic_Meetings_Set** | The number of meetings with the intent to resolve the conflict that is planned       |
|03| **Percent_Of_Forces_Mobilized**   | Same as the name of the variable                  |
|04| **Hostile_Nations** | The number of enemy nations that have allied together        |
|05| **Active_Threats**   | The number of situations or threats that require immediate attention             |
|06| **Inactive_Threats** | The number of situations or threats being monitored for activity or escalation             |
|07| **Citizen_Fear_Index**   | The percentage of citizens who fear catastrophic military conflicts                   |
|08| **Closest_Threat_Distance(km)** | The closest threat to the border of the country in question             |
|09| **Aircraft_Carriers_Responding**   | The number of aircraft carriers actively travelling towards a threat to neutralize it                   |
|10| **Troops_Mobilized(thousands)** | The number of troops that are activated and responding to the threats             |
|11| **DEFCON_Level**   | A numeric scale of conflict 'seriousness' with 1 being the least serious and 5 being the most                 |
|12| **Id** | An ID to aid a checker script            |
