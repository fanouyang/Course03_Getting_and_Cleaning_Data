# Getting-and-Cleaning-Data
Getting and Cleaning Data course project

This is the course project for the Getting and Cleaning Data Coursera course. The R script - run_analysis.R - is used to get the desired dataset

1. Download the dataset and save files in the working directory
2. Load the activity and feature info
3. Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
4. Loads the activity and subject data for each dataset, and merges those columns with the dataset
5. Merges the two datasets
5. Converts the activity and subject columns into factors
6. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject .The result is shown in the file final_data.txt.