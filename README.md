# POWER BI TASK 1

We had a Power BI session with Promise Chinonso and she actually taught us how Power BI  works and after the session we were giving some tasks to work on.

# QUESTIONS.

Import the ‘Bank Term Deposit Subscription’ dataset into your Power BI Desktop using the csv file option
Load the dataset into a database in SQL Server, connect your Power BI desktop to this database and import only the first 25 rows into your desktop for analysis



We were giving a dataset which i downloaded as a csv file and I cleaned it on excel,checked out for blanks which there was none ,and i also noticed the colunms were separated with semi commas i had to change the delimiter to semi colon using the text to column on the data tab.below is the result of our data set after the changes.

![data set](https://github.com/Maris27/Learning-Power-BI/assets/140453106/5f943c89-b61b-4705-ba42-ff1ee2bdaca8)


Next step was to load the data set into the Power BI

# Steps 
1. Opened Power BI, when the page was set
2. Clicked on Get data drop down, then i selected the text/csv option which redirected me to where i selected my data set, then i clicked on load. 


![data set on POWER BI](https://github.com/Maris27/Learning-Power-BI/assets/140453106/41568f80-1e09-47b1-a186-944fde01f1df)





Next task was to load the data set into SQL server and then load it into power BI

# SKILLS DEMONSTRATED

1.Created a database on sql server known as BANK_FULLSET

2.Imported the csv table by selecting importing flat file into the BANK_FULLSET database

3.Uploaded the data set into the Power BI through the power query(transform data).

4.Reduce the rows to 25, by selecting the Reduce rows on the home tab and i selected keep rows by range using 25 as the range.


![keep 25 rows](https://github.com/Maris27/Learning-Power-BI/assets/140453106/3720a758-79b7-48ac-be4e-443f916d71c0)





# TASK 2

QUESTION

Extensively clean the ‘Employee.csv’, ‘Department.csv’ and ‘Salary.csv’ datasets provided and  Merge all three datasets together.

# STEPS
First of all i downloaded the datasets into Power BI through the transform data on the home page, next step was to clean the datas, 
i cleaned the salary dataset by removing all the nulls values using the reduce colums, and i clicked on keep top rows and selected the first 100 rows, with this the colums with null values were gone. then for the other two data sets i checked out for empty cell ,there were no empty cells and the data type were accurate.
Now i was to merge all three together as instructed. 
i merged the employee data and department data first using the combine files on the home tab, i clicked on merge on a new query ,so with this it created a new query which was named merge 1 as shown below



![image](https://github.com/Maris27/Learning-Power-BI/assets/140453106/19bb411d-3753-4ac7-9c85-0055ff562987)
![image](https://github.com/Maris27/Learning-Power-BI/assets/140453106/80ae84e9-6448-4588-a908-571884beddfd)



then my next action was to merge the salary data and the merge 1 which is the combination of both the employee data set and the department data.

![image](https://github.com/Maris27/Learning-Power-BI/assets/140453106/c5dfea37-91b3-47c6-980c-6a0e61226a1d)    ![image](https://github.com/Maris27/Learning-Power-BI/assets/140453106/7dab4a2b-2148-4be5-ba57-734f4596d1b0)


then i reordered the colunms by moving the base and yearly increment colunms from the salary data set to the last columns so it can fit.


![image](https://github.com/Maris27/Learning-Power-BI/assets/140453106/3a3ea3d3-0445-4a53-b01e-7d8098ae798b)
















