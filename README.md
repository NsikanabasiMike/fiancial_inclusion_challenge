## Table of Contents
- [Installation](#install)
- [Introduction and Problem Statement](#intro)
- [Project Motivation](#motivate)
- [File Descriptions](#describe)
- [Licensing, Authors, and Acknowledgements](#acknowledge)

<a id='install'></a>
### Installation
1. Python 3.6 and latest from [here](https://www.python.org/downloads/)
2. Anaconda distribution of Python from [here](https://www.anaconda.com/blog/anaconda-distribution-2022-10#).<br>

<a id='intro'></a>
### Introduction and Problem Statement
Financial inclusion remains one of the main obstacles to economic and human development in Africa. For example, across Kenya, Rwanda, Tanzania, and Uganda only 9.1 million adults (or 14% of adults) have access to or use a commercial bank account.<br>

The objective of this competition is to create a machine learning model to predict which individuals are most likely to have or use a bank account. The models and solutions developed can provide an indication of the state of financial inclusion in Kenya, Rwanda, Tanzania and Uganda, while providing insights into some of the key factors driving individuals’ financial security.<br>

<a id='motivate'></a>
### Project Motivation
This project is about applying data analytics and Machine Learning(ML) skills to gather, clean, analyze, and build a ML classifier that predicts whether an individual has accrss to bank account or not (Yes = 1, No = 0). You will train your model on 70% of the data (train.csv) and test your model on the final 30% of the data (test.csv), across four East African countries - Kenya, Rwanda, Tanzania, and Uganda.

<a id='describe'></a>
### File Descriptions
The main dataset contains demographic information and what financial services are used by approximately 33,600 individuals across East Africa. This data was extracted from various Finscope surveys ranging from 2016 to 2018, and more information about these surveys can be found [here](https://zindi.africa/competitions/financial-inclusion-in-africa/data)<br>

#### Files:

1. **train.csv**: Train contains the target. This is the dataset that you will use to train your model.

2. **test.csv**: Test resembles Train.csv but without the target-related columns. This is the dataset on which you will apply your model to.

3. **VariableDefinitions.csv**: Full list of variables and their explanations:
0	country:	Country interviewee is in.
1	year:	Year survey was done in.
2	uniqueid:	Unique identifier for each interviewee
3	location_type:	Type of location
4	cellphone_access:	If interviewee has access to a cellphone
5	household_size:	Number of people living in one house
6	age_of_respondent:	The age of the interviewee
7	gender_of_respondent:	Gender of interviewee
8	relationship_with_head:	The interviewee’s relationship with the head of organisation.
9	marital_status:	The martial status of the interviewee
10	education_level:	Highest level of education
11	job_type:	Type of job interviewee has.

4. **SampleSubmission.csv**: This shows the submission format for this competition, with the ‘ID’ column mirroring that of Test.csv and the ‘target’ column containing your predictions. The order of the rows does not matter, but the names of the ID must be correct. Note that the variable ID in the submission file is: uniqueid + " x " + country name.<br>

#### Uploaded Files
Two files are uploaded:
1. **financial_inclusion_challenge.ipynb**: This is a notebook containing all the code for analysis, modeling, and results.
2. **submission.csv**: This is a csv file that stores the predictedclasses of transactions for each client.<br>
<a id='acknowledge'></a>
### Licensing, Authors, Acknowledgements
The data used is for this project is hosted by [Zindi Africa](https://zindi.africa/) for Machine Learning competition purposes.