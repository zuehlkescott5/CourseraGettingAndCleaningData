# CourseraGettingAndCleaningData

## This README is to describe the process of script run_analysis.R, which is the final project of Coursera Data Science module 3, Getting and Cleaning Data.

### Files in this repo

* README.md
* CodeBook.md
* run_analysis.R

### run_analysis.R objectives

* You should create one R script called run_analysis.R that does the following: 

** Merges the training and the test sets to create one data set.
** Extracts only the measurements on the mean and standard deviation for each measurement.
** Uses descriptive activity names to name the activities in the data set
** Appropriately labels the data set with descriptive variable names.
** From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

### run_analysis.R goals

#### Step 1:

Read test and training files, then comibne to create test, training files complete with subjects, labels, and data.

#### Step 2:

Filter out all features other than mean and standard deviation columns of all data.

#### Step 3:

Replace activity keys with activity labels from activity_labels.txt file.

#### Step 4:

Rename all feature columns with easier-to-read column names.  This will be tidy.txt.

#### Step 5:

Create a new data frame by finding the mean for each combination of subject and label. It's done by aggregate() function
Final step:

Write the new tidy set into a text file called tidy2.txt, formatted similarly to the original files.