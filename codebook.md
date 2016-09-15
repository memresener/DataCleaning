#Code Book

##Data Set
Consists of 68 columns and 180 rows, the first two pertain to the test subject and the activity performed, the rest are the measurements gathered from the phone.
The details of the original data set can be found (here)[http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones] the 

#### Added Variables

A data.table named `tidy.txt` is set with the following first two columns.

| column       | description                                              |
| ------------ | -------------------------------------------------------- |
| subject      | Identifier of the subject                                |
| activity     | Label of the activity                                    |


#### Variables

A data.table named `tidy` is set with the following columns.  All information is retrieved from the original data set. A file named tidy.txt is written from run_analysis.R.
**A prefix of "t" denotes time domain data and "f" denotes frequency domain**
**A suffix of "...X" denotes X axis data and so on**
|Variable Names               | 
|-----------------------------| 
| subject                     | 
| activities                  | 
| tBodyAcc.mean...X           | 
| tBodyAcc.mean...Y           | 
| tBodyAcc.mean...Z           | 
| tBodyAcc.std...X            | 
| tBodyAcc.std...Y            | 
| tBodyAcc.std...Z            | 
| tGravityAcc.mean...X        | 
| tGravityAcc.mean...Y        | 
| tGravityAcc.mean...Z        | 
| tGravityAcc.std...X         | 
| tGravityAcc.std...Y         | 
| tGravityAcc.std...Z         | 
| tBodyAccJerk.mean...X       | 
| tBodyAccJerk.mean...Y       | 
| tBodyAccJerk.mean...Z       | 
| tBodyAccJerk.std...X        | 
| tBodyAccJerk.std...Y        | 
| tBodyAccJerk.std...Z        | 
| tBodyGyro.mean...X          | 
| tBodyGyro.mean...Y          | 
| tBodyGyro.mean...Z          | 
| tBodyGyro.std...X           | 
| tBodyGyro.std...Y           | 
| tBodyGyro.std...Z           | 
| tBodyGyroJerk.mean...X      | 
| tBodyGyroJerk.mean...Y      | 
| tBodyGyroJerk.mean...Z      | 
| tBodyGyroJerk.std...X       | 
| tBodyGyroJerk.std...Y       | 
| tBodyGyroJerk.std...Z       | 
| tBodyAccMag.mean..          | 
| tBodyAccMag.std..           | 
| tGravityAccMag.mean..       | 
| tGravityAccMag.std..        | 
| tBodyAccJerkMag.mean..      | 
| tBodyAccJerkMag.std..       | 
| tBodyGyroMag.mean..         | 
| tBodyGyroMag.std..          | 
| tBodyGyroJerkMag.mean..     | 
| tBodyGyroJerkMag.std..      | 
| fBodyAcc.mean...X           | 
| fBodyAcc.mean...Y           | 
| fBodyAcc.mean...Z           | 
| fBodyAcc.std...X            | 
| fBodyAcc.std...Y            | 
| fBodyAcc.std...Z            | 
| fBodyAccJerk.mean...X       | 
| fBodyAccJerk.mean...Y       | 
| fBodyAccJerk.mean...Z       | 
| fBodyAccJerk.std...X        | 
| fBodyAccJerk.std...Y        | 
| fBodyAccJerk.std...Z        | 
| fBodyGyro.mean...X          | 
| fBodyGyro.mean...Y          | 
| fBodyGyro.mean...Z          | 
| fBodyGyro.std...X           | 
| fBodyGyro.std...Y           | 
| fBodyGyro.std...Z           | 
| fBodyAccMag.mean..          | 
| fBodyAccMag.std..           | 
| fBodyBodyAccJerkMag.mean..  | 
| fBodyBodyAccJerkMag.std..   | 
| fBodyBodyGyroMag.mean..     | 
| fBodyBodyGyroMag.std..      | 
| fBodyBodyGyroJerkMag.mean.. | 
| fBodyBodyGyroJerkMag.std..  | 

#### Download Raw Data

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip.
See readme for citation.
