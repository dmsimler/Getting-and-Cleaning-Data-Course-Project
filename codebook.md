# Codebook
Given below is the list of columns in the final tidy dataset saved to the file "har_summarized_dataset.txt".  In total there are 81 different columns and 180 rows, with each row representing a summary of observations for the given subject and activity.
**Note:** The actual calculated variables (columns 3-81) are means aggregated over the values for those measures for a particular subject (1-30) for a particular activity (laying, standing, etc.).

**subjectID - Column 1**
+ Identifies the subject for whom the given observation was made
+ It is an integer between 1 and 30 

**activityName - Column 2**
+ Identifies the type of physical activity being performed when the measurements were taken
+ It is a factor with one of the following 6 levels:
	- LAYING
	- SITTING
	- STANDING
	- WALKING
	- WALKING_DOWNSTAIRS
	- WALKING_UPSTAIRS

**tBodyAcc_mean_X_actmean - Column 3** 
+ Represents the mean measure in the X-direction of the body linear acceleration measured by the phone accelerometer
+ A numeric representing a time domain signal

**tBodyAcc_mean_Y_actmean - Column 4**
+ Represents the mean measure in the Y-direction of the body linear acceleration measured by the phone accelerometer
+ A numeric representing a time domain signal

**tBodyAcc_mean_Z_actmean - Column 5**
+ Represents the mean measure in the Z-direction of the body linear acceleration measured by the phone accelerometer
+ A numeric representing a time domain signal

**tBodyAcc_std_X_actmean - Column 6**
+ Represents the standard deviation of measures in the X-direction of the body linear acceleration measured by the phone accelerometer
+ A numeric representing a time domain signal

**tBodyAcc_std_Y_actmean - Column 7**
+ Represents the standard deviation of measures in the Y-direction of the body linear acceleration measured by the phone accelerometer
+ A numeric representing a time domain signal

**tBodyAcc_std_Z_actmean - Column 8**
+ Represents the standard deviation of measures in the Z-direction of the body linear acceleration measured by the phone accelerometer
+ A numeric representing a time domain signal

**tGravityAcc_mean_X_actmean - Column 9**
+ Represents the mean of measures in the X-direction of the acceleration due to gravity measured by the phone accelerometer
+ A numeric representing a time domain signal

**tGravityAcc_mean_Y_actmean - Column 10**
+ Represents the mean of measures in the Y-direction of the acceleration due to gravity measured by the phone accelerometer
+ A numeric representing a time domain signal

**tGravityAcc_mean_Z_actmean - Column 11**	
+ Represents the mean of measures in the Z-direction of the acceleration due to gravity measured by the phone accelerometer
+ A numeric representing a time domain signal

**tGravityAcc_std_X_actmean - Column 12**
+ Represents the standard deviation of measures in the X-direction of the acceleration due to gravity measured by the phone accelerometer
+ A numeric representing a time domain signal

**tGravityAcc_std_Y_actmean - Column 13**
+ Represents the standard deviation of measures in the Y-direction of the acceleration due to gravity measured by the phone accelerometer
+ A numeric representing a time domain signal

**tGravityAcc_std_Z_actmean - Column 14**
+ Represents the standard deviation of measures in the Z-direction of the acceleration due to gravity measured by the phone accelerometer
+ A numeric representing a time domain signal

**tBodyAccJerk_mean_X_actmean - Column 15**
+ Represents the mean of measures in the X-direction of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone accelerometer
+ A numeric representing a time domain signal

**tBodyAccJerk_mean_Y_actmean - Column 16**
+ Represents the mean of measures in the Y-direction of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone accelerometer
+ A numeric representing a time domain signal

**tBodyAccJerk_mean_Z_actmean - Column 17**
+ Represents the mean of measures in the Z-direction of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone accelerometer
+ A numeric representing a time domain signal

**tBodyAccJerk_std_X_actmean - Column 18**	
+ Represents the standard deviation of measures in the X-direction of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone accelerometer
+ A numeric representing a time domain signal

**tBodyAccJerk_std_Y_actmean - Column 19**
+ Represents the standard deviation of measures in the Y-direction of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone accelerometer
+ A numeric representing a time domain signal

**tBodyAccJerk_std_Z_actmean - Column 20**
+ Represents the standard deviation of measures in the Z-direction of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone accelerometer
+ A numeric representing a time domain signal

**tBodyGyro_mean_X_actmean - Column 21**
+ Represents the mean measure in the X-direction of the body linear acceleration measured by the phone gyroscope
+ A numeric representing a time domain signal

**tBodyGyro_mean_Y_actmean - Column 22**
+ Represents the mean measure in the Y-direction of the body linear acceleration measured by the phone gyroscope
+ A numeric representing a time domain signal

**tBodyGyro_mean_Z_actmean - Column 23**
+ Represents the mean measure in the Z-direction of the body linear acceleration measured by the phone gyroscope
+ A numeric representing a time domain signal

**tBodyGyro_std_X_actmean - Column 24**
+ Represents the standard deviation of measures in the X-direction of the body linear acceleration measured by the phone gyroscope
+ A numeric representing a time domain signal

**tBodyGyro_std_Y_actmean - Column 25**
+ Represents the standard deviation of measures in the Y-direction of the body linear acceleration measured by the phone gyroscope
+ A numeric representing a time domain signal

**tBodyGyro_std_Z_actmean - Column 26**
+ Represents the standard deviation of measures in the Z-direction of the body linear acceleration measured by the phone gyroscope
+ A numeric representing a time domain signal

**tBodyGyroJerk_mean_X_actmean - Column 27**
+ Represents the mean of measures in the X-direction of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone gyroscope
+ A numeric representing a time domain signal

**tBodyGyroJerk_mean_Y_actmean - Column 28**
+ Represents the mean of measures in the Y-direction of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone gyroscope
+ A numeric representing a time domain signal

**tBodyGyroJerk_mean_Z_actmean - Column 29**
+ Represents the mean of measures in the Z-direction of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone gyroscope
+ A numeric representing a time domain signal

**tBodyGyroJerk_std_X_actmean - Column 30**
+ Represents the standard deviation of measures in the X-direction of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone gyroscope
+ A numeric representing a time domain signal

**tBodyGyroJerk_std_Y_actmean - Column 31**	
+ Represents the standard deviation of measures in the Y-direction of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone gyroscope
+ A numeric representing a time domain signal

**tBodyGyroJerk_std_Z_actmean - Column 32**
+ Represents the standard deviation of measures in the Z-direction of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone gyroscope
+ A numeric representing a time domain signal

**tBodyAccMag_mean_actmean - Column 33**
+ Represents the mean measure of the magnitude of the body linear acceleration measured by the phone accelerometer
+ A numeric representing a time domain signal

**tBodyAccMag_std_actmean - Column 34**
+ Represents the standard deviation of measures of the magnitude of the body linear acceleration measured by the phone accelerometer
+ A numeric representing a time domain signal

**tGravityAccMag_mean_actmean - Column 35**
+ Represents the mean of measures of the magnitude of the acceleration due to gravity measured by the phone accelerometer
+ A numeric representing a time domain signal

**tGravityAccMag_std_actmean - Column 36**
+ Represents the standard deviation of measures of the magnitude of the acceleration due to gravity measured by the phone accelerometer
+ A numeric representing a time domain signal

**tBodyAccJerkMag_mean_actmean - Column 37**
+ Represents the mean of measures of the magnitude of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone accelerometer
+ A numeric representing a time domain signal

**tBodyAccJerkMag_std_actmean - Column 38**
+ Represents the standard deviation of measures of the magnitude of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone accelerometer
+ A numeric representing a time domain signal

**tBodyGyroMag_mean_actmean - Column 39**
+ Represents the mean of measures of magnitude of the body linear acceleration measured by the phone gyroscope
+ A numeric representing a time domain signal

**tBodyGyroMag_std_actmean - Column 40**
+ Represents the standard deviation of measures of magnitude of the body linear acceleration measured by the phone gyroscope
+ A numeric representing a time domain signal

**tBodyGyroJerkMag_mean_actmean - Column 41**
+ Represents the mean of measures of magnitude of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone gyroscope
+ A numeric representing a time domain signal

**tBodyGyroJerkMag_std_actmean - Column 42**
+ Represents the standard deviation of measures of magnitude of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone gyroscope
+ A numeric representing a time domain signal

**fBodyAcc_mean_X_actmean - Column 43**
+ Represents the mean measure in the X-direction of the body linear acceleration measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyAcc_mean_Y_actmean - Column 44**
+ Represents the mean measure in the Y-direction of the body linear acceleration measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyAcc_mean_Z_actmean - Column 45**
+ Represents the mean measure in the Z-direction of the body linear acceleration measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyAcc_std_X_actmean - Column 46**
+ Represents the standard deviaton of measures in the X-direction of the body linear acceleration measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyAcc_std_Y_actmean - Column 47**
+ Represents the standard deviaton of measures in the Y-direction of the body linear acceleration measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyAcc_std_Z_actmean - Column 48**
+ Represents the standard deviaton of measures in the Z-direction of the body linear acceleration measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyAcc_meanFreq_X_actmean - Column 49**
+ Represents the weighted mean frequency of measure in the X-direction of the body linear acceleration measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyAcc_meanFreq_Y_actmean - Column 50**
+ Represents the weighted mean frequency of measure in the Y-direction of the body linear acceleration measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyAcc_meanFreq_Z_actmean - Column 51**	
+ Represents the weighted mean frequency of measure in the Z-direction of the body linear acceleration measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyAccJerk_mean_X_actmean - Column 52**
+ Represents the mean of measures in the X-direction of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyAccJerk_mean_Y_actmean - Column 53**
+ Represents the mean of measures in the Y-direction of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyAccJerk_mean_Z_actmean - Column 54**
+ Represents the mean of measures in the Z-direction of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyAccJerk_std_X_actmean - Column 55**	
+ Represents the standard deviation of measures in the X-direction of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyAccJerk_std_Y_actmean - Column 56**
+ Represents the standard deviation of measures in the Y-direction of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyAccJerk_std_Z_actmean - Column 57**
+ Represents the standard deviation of measures in the Z-direction of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyAccJerk_meanFreq_X_actmean - Column 58**
+ Represents the weighted mean frequency of measures in the X-direction of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyAccJerk_meanFreq_Y_actmean - Column 59**
+ Represents the weighted mean frequency of measures in the Y-direction of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyAccJerk_meanFreq_Z_actmean - Column 60**
+ Represents the weighted mean frequency of measures in the Z-direction of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyGyro_mean_X_actmean - Column 61**
+ Represents the mean measure in the X-direction of the body linear acceleration measured by the phone gyroscope
+ A numeric representing a frequency domain signal in Hertz

**fBodyGyro_mean_Y_actmean - Column 62**
+ Represents the mean measure in the Y-direction of the body linear acceleration measured by the phone gyroscope
+ A numeric representing a frequency domain signal in Hertz

**fBodyGyro_mean_Z_actmean - Column 63**
+ Represents the mean measure in the Z-direction of the body linear acceleration measured by the phone gyroscope
+ A numeric representing a frequency domain signal in Hertz

**fBodyGyro_std_X_actmean - Column 64**
+ Represents the standard deviation of measures in the X-direction of the body linear acceleration measured by the phone gyroscope
+ A numeric representing a frequency domain signal in Hertz

**fBodyGyro_std_Y_actmean - Column 65**
+ Represents the standard deviation of measures in the Y-direction of the body linear acceleration measured by the phone gyroscope
+ A numeric representing a frequency domain signal in Hertz

**fBodyGyro_std_Z_actmean - Column 66**
+ Represents the standard deviation of measures in the Z-direction of the body linear acceleration measured by the phone gyroscope
+ A numeric representing a frequency domain signal in Hertz

**fBodyGyro_meanFreq_X_actmean - Column 67**
+ Represents the weighted mean frequency of measures in the X-direction of the body linear acceleration measured by the phone gyroscope
+ A numeric representing a frequency domain signal in Hertz

**fBodyGyro_meanFreq_Y_actmean - Column 68**
+ Represents the weighted mean frequency of measures in the Y-direction of the body linear acceleration measured by the phone gyroscope
+ A numeric representing a frequency domain signal in Hertz

**fBodyGyro_meanFreq_Z_actmean - Column 69**
+ Represents the weighted mean frequency of measures in the Z-direction of the body linear acceleration measured by the phone gyroscope
+ A numeric representing a frequency domain signal in Hertz

**fBodyAccMag_mean_actmean - Column 70**
+ Represents the mean measure of the magnitude of the body linear acceleration measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyAccMag_std_actmean - Column 71**
+ Represents the standard deviation of measures of the magnitude of the body linear acceleration measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyAccMag_meanFreq_actmean - Column 72**
+ Represents the weighted mean frequency of measures of the magnitude of the body linear acceleration measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyBodyAccJerkMag_mean_actmean - Column 73**
+ Represents the mean of measures of the magnitude of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyBodyAccJerkMag_std_actmean - Column 74**
+ Represents the standard deviaton of measures of the magnitude of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyBodyAccJerkMag_meanFreq_actmean - Column 75**
+ Represents the weighted mean frequency of measures of the magnitude of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone accelerometer
+ A numeric representing a frequency domain signal in Hertz

**fBodyBodyGyroMag_mean_actmean - Column 76**
+ Represents the mean of measures of the magnitude of the body linear acceleration measured by the phone gyroscope
+ A numeric representing a frequency domain signal in Hertz

**fBodyBodyGyroMag_std_actmean - Column 77**
+ Represents the standard deviation of measures of the magnitude of the body linear acceleration measured by the phone gyroscope
+ A numeric representing a frequency domain signal in Hertz

**fBodyBodyGyroMag_meanFreq_actmean - Column 78**
+ Represents the weighted mean frequency of measures of the magnitude of the body linear acceleration measured by the phone gyroscope
+ A numeric representing a frequency domain signal in Hertz

**fBodyBodyGyroJerkMag_mean_actmean - Column 79**
+ Represents the mean of measures of the magnitude of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone gyroscope
+ A numeric representing a frequency domain signal in Hertz

**fBodyBodyGyroJerkMag_std_actmean - Column 80**
+ Represents the standard deviation of measures of the magnitude of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone gyroscope
+ A numeric representing a frequency domain signal in Hertz

**fBodyBodyGyroJerkMag_meanFreq_actmean - Column 81**
+ Represents the weighted mean frequency of measures of the magnitude of jerk signals derived in time from the body linear acceleration and angular velocity measured by the phone gyroscope
+ A numeric representing a frequency domain signal in Hertz



# Transformations
The original Human Activity Recognition raw dataset was transformed into the tidy dataset described above in the following steps given below and executed in the project's associated run_analysis.R script:

1. Merge the training and the test sets to create one data set
2. Extract only the measurements on the mean and standard deviation for each measurement. 
3. Add descriptive activity names for each observation in the data set.  Also adds the ID of the human subject for a given observation.
4. Update the dataset variable (column) names so they are more descriptive 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject

