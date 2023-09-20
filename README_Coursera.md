# Coursera Data Analysis

This project is an exploratory analysis on course data from the Coursera online learning provider, aiming to get insights into the most popular courses and course providers.  

## Format

The analysis is performed in a Jupyter notebook, and can be opened in any IDE that supports Jupyter notebook files (.ipynb).

## Dataset

The dataset comes from a website called Kaggle, to be found in csv format via this url: https://www.kaggle.com/datasets/siddharthm1698/coursera-course-dataset 
The data represents 891 courses that have been followed by over 8 million users on the website of the online learning provider Coursera. The dataset was created not by Coursera itself, but scraped from their website by an individual for the purpose of building a tool to help people choose courses. 
The raw dataset consists of 7 features and 891 cases, on course level. Below an overview of all features and their meaning:

* id: unique case identifier
* title : Contains the course title.
* organization : It tells which organisation is conducting the courses.
* certificate_type : It has details about what are the different certifications available in courses.
* rating : It has the ratings associated with each course.
* difficulty : It tells about how difficult or what is the level of the course.
* students_enrolled : It has the number of students that are enrolled in the course.

With the data of these features, we would like to find out if courses with a high number of student enrollments have common features that seem to be typical for popular courses. One downside of this dataset is that it is relatively small in terms of features, and thus there isn't much data on characteristics that could serve as potential predictors of popularity. We likely lack information on a lot of possible features that students could be attaching value to when choosing a course.  

## Limitations

Since this is only exploratory research, no causal relations can be determined as to what makes a course popular, we here only first observe features that might be characteristic of popular courses. However, to be able to determine whether these features are actual predictors of success, further research is needed with data of a larger variety of course featuers and with statistical testing to be able to draw conclusions. 
