# Getting-Cleaning-Data
#R script: run_analysis.R
#Database:https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
#For preparing for the tasks, the following initial tasks are as follows:
# Download zipped file as "instancia.zip"
# Unzip the file to "UCI HAR Dataset" & create "results" folders to store final results
# Read text & convert to data frame
# Define function "gettables" to read data & build database & save the result in a folder
# Define function "getdata" to extract data
# Define function "savedata" to write data as a .csv file

# Other tasks!
#1) Merges the training and the test sets to create one data set.
#2) Extracts only the measurements on the mean and standard deviation for each measurement. 
#3) Uses descriptive activity names to name the activities in the data set
#4) Appropriately labels the data set with descriptive variable names. 
#5) Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

# The final result is in the file name- tidy_dataset.csv; tidydataset.txt (text file version)
