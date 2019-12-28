# week4assignment
Peer-graded-Assignment-Getting-and-Cleaning-Data-Course-Project

Download data for the project from this link and unzip it.Make that folder available in the path while running the code

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip


 run_analysis.R code file does the following:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.


## About this R script

1. Merging the training and the test sets to create one data set.   
  1.1 Reading  8 files 3 from training set, 3 from testing set and 2 from the top folder
    Reading trainings tables   -3 
    Reading testing tables   - 3
    Reading feature vector   - 1
    Reading activity labels  - 1
    
    Assigning column names while reading the files
    Merging all data in one set   
    
2. Extracting only the measurements on the mean and standard deviation for each measurement   
  Reading column names  
  Create vector for defining ID, mean and standard deviation   
  Making nessesary subset from setAllInOne   
  
3. Using descriptive activity names to name the activities in the data set   

4. Appropriately labeling the data set with descriptive variable names   

5. Creating a final tidy data set with the average of each variable for each activity and each subject   
  Writing second tidy data set in txt file
  
  
  