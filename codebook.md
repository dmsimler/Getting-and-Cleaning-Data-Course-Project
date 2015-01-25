# Overview

# Codebook

* subjectID	
* activityName	
* tBodyAcc_mean_X_actmean	
* tBodyAcc_mean_Y_actmean	
* tBodyAcc_mean_Z_actmean	
* tBodyAcc_std_X_actmean	
* tBodyAcc_std_Y_actmean	
* tBodyAcc_std_Z_actmean	
* tGravityAcc_mean_X_actmean	
* tGravityAcc_mean_Y_actmean	
* tGravityAcc_mean_Z_actmean	
* tGravityAcc_std_X_actmean	
* tGravityAcc_std_Y_actmean	
* tGravityAcc_std_Z_actmean	
* tBodyAccJerk_mean_X_actmean	
* tBodyAccJerk_mean_Y_actmean	
* tBodyAccJerk_mean_Z_actmean	
* tBodyAccJerk_std_X_actmean	
* tBodyAccJerk_std_Y_actmean	
* tBodyAccJerk_std_Z_actmean	
* tBodyGyro_mean_X_actmean	
* tBodyGyro_mean_Y_actmean	
tBodyGyro_mean_Z_actmean	
tBodyGyro_std_X_actmean	
tBodyGyro_std_Y_actmean	
tBodyGyro_std_Z_actmean	
tBodyGyroJerk_mean_X_actmean	
tBodyGyroJerk_mean_Y_actmean	
tBodyGyroJerk_mean_Z_actmean	
tBodyGyroJerk_std_X_actmean	
tBodyGyroJerk_std_Y_actmean	
tBodyGyroJerk_std_Z_actmean	
tBodyAccMag_mean_actmean	
tBodyAccMag_std_actmean	
tGravityAccMag_mean_actmean	
tGravityAccMag_std_actmean	
tBodyAccJerkMag_mean_actmean	
tBodyAccJerkMag_std_actmean	
tBodyGyroMag_mean_actmean	
tBodyGyroMag_std_actmean	
tBodyGyroJerkMag_mean_actmean	
tBodyGyroJerkMag_std_actmean	
fBodyAcc_mean_X_actmean	
fBodyAcc_mean_Y_actmean	
fBodyAcc_mean_Z_actmean	
fBodyAcc_std_X_actmean	
fBodyAcc_std_Y_actmean	
fBodyAcc_std_Z_actmean	
fBodyAcc_meanFreq_X_actmean	
fBodyAcc_meanFreq_Y_actmean	
fBodyAcc_meanFreq_Z_actmean	
fBodyAccJerk_mean_X_actmean	
fBodyAccJerk_mean_Y_actmean	
fBodyAccJerk_mean_Z_actmean	
fBodyAccJerk_std_X_actmean	
fBodyAccJerk_std_Y_actmean	
fBodyAccJerk_std_Z_actmean	
fBodyAccJerk_meanFreq_X_actmean	
fBodyAccJerk_meanFreq_Y_actmean	
fBodyAccJerk_meanFreq_Z_actmean	
fBodyGyro_mean_X_actmean	
fBodyGyro_mean_Y_actmean	
fBodyGyro_mean_Z_actmean	
fBodyGyro_std_X_actmean	
fBodyGyro_std_Y_actmean	
fBodyGyro_std_Z_actmean	
fBodyGyro_meanFreq_X_actmean	
fBodyGyro_meanFreq_Y_actmean	
fBodyGyro_meanFreq_Z_actmean	
fBodyAccMag_mean_actmean	
fBodyAccMag_std_actmean	
fBodyAccMag_meanFreq_actmean	
fBodyBodyAccJerkMag_mean_actmean	
fBodyBodyAccJerkMag_std_actmean	
fBodyBodyAccJerkMag_meanFreq_actmean	
fBodyBodyGyroMag_mean_actmean	
fBodyBodyGyroMag_std_actmean	
fBodyBodyGyroMag_meanFreq_actmean	
fBodyBodyGyroJerkMag_mean_actmean	
fBodyBodyGyroJerkMag_std_actmean	
fBodyBodyGyroJerkMag_meanFreq_actmean


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