# DataCleaning
Data tidying script for Samsung gyro data. Files are imported from the working directory, make sure filenames match the source to run correctly. Data source listed below.

####Required modules:
dplyr
Tested with R 3.1. 

####Data From:
Jorge L. Reyes-Ortiz(1,2), Davide Anguita(1), Alessandro Ghio(1), Luca Oneto(1) and Xavier Parra(2)
1 - Smartlab - Non-Linear Complex Systems Laboratory
DITEN - Università degli Studi di Genova, Genoa (I-16145), Italy. 
2 - CETpD - Technical Research Centre for Dependency Care and Autonomous Living
Universitat Politècnica de Catalunya (BarcelonaTech). Vilanova i la Geltrú (08800), Spain
activityrecognition '@' smartlab.ws
[http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones]

###Operation
readCombine() returns a tidied data frame named "tidy". The script merges the .txt files for test and training data available at the source. Subject and activity columns are appended, the columns only with the mean and std. deviation values are selected and the mean for each subject/activity pair is reported.



