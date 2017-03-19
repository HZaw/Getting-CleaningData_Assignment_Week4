# Getting&CleaningData_Assignment_week4

 Repo was created to finish the assignment for week 4 of Getting and Cleaning Data course.
* 1. download and unzip the data file into your R working directory.
* 2. download the R source code into your R working directory.
* 3. execute R source code to create a tidy data file.

## Data description
The variables in the data X are sensor signals measured while the variable in the data Y indicates activity type the subjects performed during recording.

## Explanation of code
The training dataset and test dataset were combined by code and extracted partial variables to create another dataset with the averages of each variable for each activity.

## Creating new dataset based on mean and standard deviation
The new dataset was created for all variables based on the mean and standard deviation. 
Each row of the dataset is an average of each activity type for all subjects.

## According to the instructions, following codes were created
1.Load training and test dataset into R environment.
2.Load variable names into R environment.
3.Load subject index into R environment.
4.Merges the training and the test sets to create one data set.
Use command cbind and rbind to combine training and test set
5.Extracts only the measurements on the mean and standard deviation for each measurement.
Use grepl command to get column indexes for variable name contains "mean()" or "std()"
6.Uses descriptive activity names to name the activities in the data set
Convert activity labels to characters and add a new column as factor
7.Appropriately labels the data set with descriptive variable names.
Give the selected descriptive names to variable columns
8.From the data set in step 7, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
Finally, the aggregate and order functions were used to create a new tidy dataset.
