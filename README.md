# Overview
This is a guide to the "Getting and Cleaning Data" course project which transforms the raw dataset from Human Activity Recognition (HAR) into a summarized tidy dataset. 

Given below is the manifest of files included in this project:
+ Readme.md - Gives a list of the files for this course project and how they relate to each other.
+ run_analysis.R - This is the R script which transforms the HAR dataset (downloaded from the UCI website) into a summarized tidy dataset.  In particular, it executes the following steps:
	1. Merges the training and the test sets to create one data set
	2. Extracts only the measurements on the mean and standard deviation for each measurement. 
	3. Adds descriptive activity names for each observation in the data set.  Also adds the ID of the human subject for a given observation.
	4. Updates the dataset variable (column) names so they are more descriptive 
	5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject
+ code_book.md - 

# Instructions on How to Create the Tidy Dataset
1) Download the Human Activity Recognition dataset from this location to your working folder:
       [https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)
    
2) In your working folder, extract the contents of the previously downloaded .zip file into a new child folder named "UCI HAR Dataset".  All the associated data files should now be in that or its subfolders.

3) Retrieve the run_analysis.R script into your working folder from Github at this location:
    https://github.com/dmsimler/Getting-and-Cleaning-Data-Course-Project

4) Open the run_analysis.R script in R-Studio.

5) Before running the script, update the location specified in the setwd command (at the top of the script) to your working folder location.

6) Run the run_analysis.R script.  There should be no errors.

7) When the script has finished, there should be a file named "" containing the tidy dataset summarizing key measurements from the original HAR dataset.  