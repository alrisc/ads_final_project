# ads_final_project
This is the repository for the final project of Applied Data Science.

1.	Project Title: Data Scientist Salaries
2.	Team: Alexander Schmig (Solo)
3.	Project Description:
    a.	Objective: I want to build an application that lets prospective data scientists know how much they should roughly earn for their salary.
    b.	Usefulness: This application will be helpful for those of us who are newly entering as Data Scientists to better understand salary expectations, and may help those who have been Data Scientists for some time know an approximate trajectory of their salary.  I know there are others, but not of this dataset as far as I can tell.  And while there may be other interactive apps, they tend to pertain to many jobs rather than a singular job.
    c.	Dataset: The data was aggregated on https://salaries.ai-jobs.net/ and the dataset was built and posted by Ruchi Bhatia on Kaggle here: https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries
        i.	The data is organized by categorical independent variables and the target continuous variable of “salary_in_usd”, which converts the salaries of data scientists in other countries to the USD so they can be scaled together.  The “salary” variable is continuous, but useless to us since it is the relative salary of the individual, and as such will be dropped from the dataset prior to modeling.
        ii.	The data does not have any missing values.  The “years_worked” column will need to be changed to categorical, as those years are automatically converted to continuous numerical in python.
    d.	Functionalities: I will provide a visual plot to show what the average data scientist with their respective experience level at a small/medium/large company could expect for a salary.  I will also have a predictive model to show what Data Scientists could expect to make in 2023, given that same criteria.  The user will be allowed to filter and adjust the criteria.

