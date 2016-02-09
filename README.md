This repo contains

1) a tidy dataset

2) a code book describing the data, varaianldes and transformatiosn that ere prerformed

3) a link to a Github repository with the script for performing the analysis


The R-script on Human Activity Recognition Using Smartphones Dataset  “run_analyis.R” does the following 

Gets the files needed for analysis.  Loads the activity and feature information  and labels the appropriate columns. Loads both the training and test datasets and labels the columns. Reads the ids of the test and train subjects and the activities and labels the dataframes columns accordingly.
Combines the test subject ids , test activity ids, and the test data into a test_data dataframe.  
Combines the train subject ids, test activity ids, and the test data into a train_data dataframe.  
Combines the test data and the train data into one dataframe.
The next steps subset the columns that only apply to the mean or standard deviations of the measurements taken.  The variable names are renamed from their abbreviations to expanded descriptions. 
The data is then manipulated to forma  dtaframe with mean data. 
A new tidy dataset  is created called ”tidy_data.txt”.  
