# Overview
This is a guide to the "Getting and Cleaning Data" course project which transforms the raw dataset from Human Activity Recognition (HAR) into a summarized tidy dataset. 

Given below is the manifest of files included in this project:
+ **Readme.md** - Gives a list of the files for this course project and how they relate to each other.
+ **run_analysis.R** - This is the R script which transforms the HAR dataset (downloaded from the UCI website) into a summarized tidy dataset.  In particular, it executes the following steps:
	1. Merges the training and the test sets to create one data set
	2. Extracts only the measurements on the mean and standard deviation for each measurement. 
	3. Adds descriptive activity names for each observation in the data set.  Also adds the ID of the human subject for a given observation.
	4. Updates the dataset variable (column) names so they are more descriptive 
	5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject
+ **codebook.md** - This is project codebook which describes the variables in the final tidy dataset and the transformations that were performed on the original raw data to get there.  In particular, it contains the following sections of note:
	1. Codebook - Lists all the variables in the final tidy dataset
	2. Instructions on How to Create the Tidy Dataset - Provides step-by-step instructions on how to obtain the HAR dataset and transform it into the target tidy dataset using the run_analysis.R script.
+ **har_summarized_dataset.txt** - This is the summarized tidy dataset which contains 180 rows and 81 columns.  For a detailed description of each column (variable) please consult code_book.md.
