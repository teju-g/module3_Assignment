Project for Getting and Cleaning Data


Parameters for the project

The purpose of this project is to demonstrate ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis.



Source data for the project is taken from below url:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Download this directory and extract to R working directory.

R script called run_analysis.R does the following.

Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set.
Appropriately labels the data set with descriptive activity names.
Creates a second, independent tidy data set with the average of each variable for each activity and each subject.


Steps to reproduce this project

Open R Studio.
Change the parameter of the setwd function call to the working directory/folder (i.e., the folder where these the R script file is saved).
Run the R script run_analysis.r from R Studio Console.

This create a file name Tidy.txt in working directory.