##This is the course project for the Getting and Cleaning Data Coursera course. The R script, run_analysis.R, does the following:

*Download the dataset if it does not already exist in the working directory
*Load the activity and feature info
*Loads the training set(xtrain)
*Loads the activity and subject data for the dataset, and merges those columns with the xtrain set and store it in a variable trainset.
*Loads the test dataset(xtest)
*Load the activity and the subject data for the dataset,and merge those columns with the xtest set and store it in a variable testset. 
*Merge the testset and the trainset and store it in a variable newset
*Select only those columns which have either,mean or the std deviation and store it in eden.
*Change the numbers in the activities column to the names in the descriptive activities.
