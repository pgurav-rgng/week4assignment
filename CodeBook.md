
## Getting and Cleaning Data - peer assessment project

## About Files read:  
1. Merging the training and the test sets to create one data set.   
  1.1 Reading  8 files 3 from training set, 3 from testing set and 2 from the top folder
    Reading trainings tables   -3 
    Reading testing tables   - 3
    Reading feature vector   - 1
    Reading activity labels  - 1

## About variables:   
* `x_train`, `y_train`, `x_test`, `y_test`, `subject_train` and `subject_test` contain the data from the downloaded files.
* `x_data`, `y_data` and `subject_data` merge the previous datasets to further analysis.
* `features` contains the correct names for the `x_data` dataset, which are applied to the column names stored in

## About R script
File with R code "run_analysis.R" perform 5 following steps (in accordance assigned task of course work)

run_analysis.R performs the data preparation and then followed by the 5 steps required as described in the course project's definition:
   - Merges the training and the test sets to create one data set.
   - Extracts only the measurements on the mean and standard deviation for each measurement.
   - Uses descriptive activity names to name the activities in the data set
   - Appropriately labels the data set with descriptive variable names.
   - From the data set in step 4, creates a second, independent tidy data set with the average of          each variable for each activity and each subject.
   - FinalData.txt is the exported final data after going through all the sequences described above.



