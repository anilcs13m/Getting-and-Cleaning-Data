Getting and Cleaning Data Course of Coursera project
====================================================
all the code and process related to the Getting and Cleaning Data course by Coursera


* First, unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and rename the folder with "data".
* Make sure the folder "data" and the analysis.R script are both in the current working directory.
* Second, use source("analysis.R") command. 
* Third, you will find two output files are generated in the current working directory:
  - merged_data.txt: it contains a data frame called cleanedData.
  - data_means.txt: it contains a data frame called result.
* Finally, use data <- read.table("data_means.txt") command to read the file. 
