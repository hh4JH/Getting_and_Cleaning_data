# Getting_and_Cleaning_data
This is a repository for code written for the Getting and Cleaning Data Coursera course 
through Johns Hopkins University.

# Course Project


- Unzip the source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder on your local disk

- Put run_analysis.R into you data folder say (C:\Users\yourname\Documents\R\UCI HAR Dataset\)

- In RStudio: setwd("C:\\Users\\yourname\\Documents\\R\\UCI HAR Dataset\\"), followed by: source("run_analysis.R")

- Use data <- read.table("data_set_with_the_averages.txt") to read the data. It is 180x68 because there are 30 subjects and 6 activities, thus "for each activity and each subject" means 30 * 6 = 180 rows.
