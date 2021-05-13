<img src = "https://storage.googleapis.com/kaggle-datasets-images/1019790/1719283/f7505a4e4d6e9c141aa2196a7a77ddf7/data-original.png?t=2020-12-07-00-41-54" height = "350" width="800">
 
 # <font color='blue'> HR Analytics: Job Change of Data Scientists </font> 
 
 
 In this project, we will use the CRISP-DM (Cross-Industrie Standard Process for Data Mining) to predict job change of data scientists in a particular company. We use this framework in order to work with a robust and well-proven methodology. Each stage of this framework will be describe in details belong this project.
 
 
## Business Understanding
 

A company which is active in Big Data and Data Science wants to hire data scientists among people who successfully pass some courses which conduct by the company. Many people signup for their training. Company wants to know which of these candidates are really wants to work for the company after training or looking for a new employment because it helps to reduce the cost and time as well as the quality of training or planning the courses and categorization of candidates. Information related to demographics, education, experience are in hands from candidates signup and enrollment.

## Data Understanding

This data is taken from Kaggle repository and can be downloaded in https://www.kaggle.com/arashnic/hr-analytics-job-change-of-data-scientists. The dataset is designed to understand the factors that lead a person to leave current job for HR researches too. By a model that uses the current credentials, demographics, experience data we need to predict the probability of a candidate to look for a new job or will work for the company, as well as interpreting affected factors on employee decision.

The whole data divided to train and test . Target isn't included in test but the test target values data file is in hands for related tasks.

**Note:**

The dataset is imbalanced.
Most features are categorical (Nominal, Ordinal, Binary), some with high cardinality.
Missing imputation is part of our pipeline as well.

**Features**

enrollee_id : Unique ID for candidate

city: City code

city_ development _index : Developement index of the city (scaled)

gender: Gender of candidate

relevent_experience: Relevant experience of candidate

enrolled_university: Type of University course enrolled if any

education_level: Education level of candidate

major_discipline :Education major discipline of candidate

experience: Candidate total experience in years

company_size: No of employees in current employer's company

company_type : Type of current employer

lastnewjob: Difference in years between previous job and current job

training_hours: training hours completed

target: 0 – Not looking for job change, 1 – Looking for a job change
