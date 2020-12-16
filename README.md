## MACHINE LEARNING BASED CLASSIFICATION PROJECT

## Content

### Problem Statement:
Client is a large MNC and they have 9 broad verticals across the organisation. One of the problem  client is facing is around identifying the right people for promotion (only for manager position and below) and prepare them in time. Currently the process, they are following is:
1-They first identify a set of employees based on recommendations/ past performance, 2-Selected employees go through the separate training and evaluation program for each vertical. These programs are based on the required skill of each vertical, 3-At the end of the program, based on various factors such as training performance, KPI completion (only employees with KPIs completed greater than 60% are considered) etc., employee gets promotion company needs  help in identifying the eligible candidates at a particular checkpoint so that they can expedite the entire promotion cycle. 
Company have provided multiple attributes around Employee's past and current performance along with demographics. Now, The task is to predict whether a potential promotee at checkpoint in the test set will be promoted or not after the evaluation process.

![Human_Resource](https://user-images.githubusercontent.com/66259814/102377775-0f361880-3feb-11eb-83cf-897a2a507299.png)

### Overview:
This is classification based problem in which 54808 rows and 13 feature's are present applied EDA techniques tried to understand the data, it was target class imbalanced data apply some over sampling and under sampling techniques make target class balanced data.apply differenet different techniques to handle categorical features, some features are belongs to ordinal some are belongs to nominal , dataset having lots of Missing values and some belongs to Missing completely at Random, Missing not at Random, Missing at Random, make distribution as Normally Distributed by use Transformation Techniques than do Feature Selection in the last train a model using all Machine Leaning algorithm and choose one which will give best F1 score.
Test Datasets has 23490 rows and 13 features

### Dataset Description: 
employee_id(Unique ID for employee), department(Department of employee), region(Region of employment (unordered)), education(Education Level), gender( Gender of Employee), recruitment_channel( Channel of recruitment for employee), no_of_trainings(no of other trainings completed in previous year on soft skills, technical skills etc.), age( Age of Employee), previous_year_rating(Employee Rating for the previous year), length_of_service(Length of service in years), KPIs_met >80%(if Percent of KPIs(Key performance Indicators) >80% then 1 else 0), awards_won?(if awards won during previous year then 1 else 0), avg_training_score(Average score in current training evaluations), is_promoted((Target) Recommended for promotion)
