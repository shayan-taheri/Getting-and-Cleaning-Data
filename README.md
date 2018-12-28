# The Getting and Cleaning Data Project @ Coursera:

This project is for getting and cleaning data presented in a Coursera course.
The main executing script `run_analysis.R` in this package performs the following tasks:

1. Downloading the "UCI HAR Dataset" if it does not already exist in the working directory.
2. Loading the activity and feature information.
3. Loading both the training and test datasets. Only those columns that reflect a mean or a standard deviation stay in the working environment.
4. Loading the activity and subject data for each dataset. Next, they are merged with those columns with the dataset.
5. Merging of the two datasets.
6. Conversion of the `activity` and `subject` columns into factors.
7. Creation of a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.

The processed data are presented in the `tidy.txt` file.