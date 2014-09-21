Getting-and-Cleaning-Data-Project
=================================

Course Project

create R script called run_analysis.R with the following functionalities:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.
6. Creates outfile "tidy_data.txt"

Steps to work on this course project

Download the data source from the URL https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
and save into a folder on your local drive. After extracting the zip file "UCI HAR Dataset folder" will be created.
create the script file - run_analysis.R in the parent folder of UCI HAR Dataset, then set it as your working directory 
using setwd() function in RStudio.
Run source("run_analysis.R"), then it will generate a new file tiny_data.txt in your working directory.

Dependencies

reshape2 and data.table packages. The installation of both the packages will happen while running the script "run_analysis.R"
