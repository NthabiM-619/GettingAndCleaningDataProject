# GettingAndCleaningDataProject
Final Project
This project is an amazing part of the data science, this project outline how companies like Fitbit, 
Nike and Jawbone Up are racing to develop the most advanced algoriths to attract new users.
A repo is created to complete this final week 4 assignment for getteing and cleaning data, 
the name of the repo is GettingAndCleaningDataProject.
firstly, I downloaded and unzipped the data file into my R directory.
Secondly, downloaded the R source code into my working directory
And then finnally, executed the R source code to generate tidy data file.

Code Explanation
The code combined training dataset and test datatest, and extrcated variables 
to create another dataset with features of each variable for activity.

Assigning of each data to variables
dataFeatures <- "X_Features.txt"
dataActivities <- "Y_activity.txt"
dataSubject <- "Subject.txt"

DATA DESCRIPTION
Thevariables in the data X are sensor signals measured in waist-mounted smartphone from 30 subjects.
And in the Y, the activities are indicating the type of the performance during the recording of the subject.

NEW DATASET
The newly created dataset is containing the variables that are calculated according to the standard deviation and the mean.
As each row is an avaerage of all activities types for all subjects.

This was following the instruction as given to complete this assignment.
There is an R Script called run_analysis thet was created to perform the following steps:
1. Merges the training and test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviatio for each measurement.
3. Uses descriptive activity names to name the activities in the data set.
4. Appropraitely labels the data set with desriptive varaible names.
5. Fromthe data set in step 4,creates a second, independent tidy data set with the average of each activity and each subject.

