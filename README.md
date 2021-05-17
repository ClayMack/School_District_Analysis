# School District Analysis

* Use Jupyter Notebooks

* Use Python and Pandas library to analyze school district data 

* Track school performance based on key metrics to aid school board budgetary decisions 



## Overview of the school district analysis:

* Install Jupyter Notebooks and load pandas
* load data in csv file.
* Clean data for missing values
* Merge school and student datasets into one complete dataset
* Create data frames to calculate data metrics using functions
* Create data tables for trend analysis

## Challenge Objective:
The school board noticed the data shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. The board needs to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once the math and reading scores have been replaced, the school district needs the analysis repeated.

## Results:

* How is the district summary affected?
    * The district summary is relatively unchanged. Because the Thomas Highschool 9th grade scores were dropped, the averages for math and reading, as well as the percent passing, lowered slightly.    


Original:

![District Summary](https://github.com/ClayMack/School_District_Analysis/blob/main/Resources/Screenshots/District%20Summary.png "This is a screenshot image.")

Updated:

![Updated District Summary](https://github.com/ClayMack/School_District_Analysis/blob/main/Resources/Screenshots/Updated%20District%20Summary.png "This is a screenshot image.")
    
    
* How is the school summary affected?
    * The change here is minimal. Because we only removed the Thomas Highschool 9th grade score, the school size and buget data did not change. The only observable difference is a lowering of the math and reading average scores and percent passing for both. Because we only removed data for one of the four Thomas Highschool grades, the recorded change was minimal. Even though the change was small, it was shifted lower. 
    
Original:

![School Summary](https://github.com/ClayMack/School_District_Analysis/blob/main/Resources/Screenshots/School%20Summary.png "This is a screenshot image.")

Updated:

![Updated School Summary](https://github.com/ClayMack/School_District_Analysis/blob/main/Resources/Screenshots/Updated%20School%20Summary.png "This is a screenshot image.")

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
   * the averages and percent passing scores drop lower
    
#### How does replacing the ninth-grade scores affect the following:


When we remove the scores, we do see changes in the scores based off of school spending, school size, and school type, but there is no appreciable change here because we are only omitting a small portion of the data. 




## Summary:

After removing the scores, the resulting analysis indicates that the original data may not be fradulent. Had there been fradulent data, the results would indicate a wider variance then what is there.








