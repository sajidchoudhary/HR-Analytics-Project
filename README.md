## MACHINE LEARNING BASED CLASSIFICATION PROJECT

## Content

### Overview:
This is classification based problem in which 54808 rows and 13 feature's are present, Large MNC identifying the right people for promotion only for manager position and below.
in this project try to predict right employees for promotion using machine learning. HR analytics is revolutionising the way human resources departments operate, leading to higher efficiency and better results overall. Human resources has been using analytics for years. However, the collection and processing of data has been largely manual.

![Human_Resource](https://user-images.githubusercontent.com/66259814/102377775-0f361880-3feb-11eb-83cf-897a2a507299.png)


### Problem Statement:
Large MNC and they have 9 broad verticals across the organisation. One of the problem facing is around identifying the right people for promotion (only for manager position and below) and prepare them in time. Currently the process, they are following is:
1-They first identify a set of employees based on recommendations/ past performance, 2-Selected employees go through the separate training and evaluation program for each vertical. These programs are based on the required skill of each vertical, 3-At the end of the program, based on various factors such as training performance, KPI completion (only employees with KPIs completed greater than 60% are considered) etc., employee gets promotion company needs  help in identifying the eligible candidates at a particular checkpoint so that they can expedite the entire promotion cycle. 
Company have provided multiple attributes around Employee's past and current performance along with demographics. Now, The task is to predict whether a potential promotee at checkpoint in the test set will be promoted or not after the evaluation process.


### Dataset Description: 
employee_id(Unique ID for employee), department(Department of employee), region(Region of employment (unordered)), education(Education Level), gender( Gender of Employee), recruitment_channel( Channel of recruitment for employee), no_of_trainings(no of other trainings completed in previous year on soft skills, technical skills etc.), age( Age of Employee), previous_year_rating(Employee Rating for the previous year), length_of_service(Length of service in years), KPIs_met >80%(if Percent of KPIs(Key performance Indicators) >80% then 1 else 0), awards_won?(if awards won during previous year then 1 else 0), avg_training_score(Average score in current training evaluations), is_promoted(Target feature).
