Getting-and-Cleaning-Data-Project
=================================

Course Project
==============
create R script called run_analysis.R with the following functionalities:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.
6. Creates output file "tidy_data.txt" in the working directory

Steps to work on this course project

- Download the data source from the URL https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
- Save it in a folder on your local drive
- Extract the zip file "UCI HAR Dataset", a new folder will be created.
- Set the current working directory as "UCI HAR Dataset" using as setwd() function by providing the full path
- After coding the script, save the file run_analysis.R in the parent folder of "UCI HAR Dataset"
- Run source("run_analysis.R")in R
- This will generate a new output file tiny_data.txt in your working directory.

Dependencies

Two packages reshape2 and data.table are required. The installation of both the packages will happen while running the script "run_analysis.R"
