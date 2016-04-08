# run_analysis.R_JeffGonlin
Coursera Data Cleaning Week 4 Assignment
In this exercise we look at data from 30 volunteers engaged in 6 activities collected on mobile phones.
Original study can be sourced here:  http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The aim is to make one combined and tidy data set.  Steps taken include:
- combine 3 pairs of 'test' and 'train' data sets
- replace activity codes with activity names
- replace "V1, V2 ..."  type column names with descriptive names
- make tidy all column names
- identify columns with measurements relating to mean and standard deviaiation
- extract the mean and standadrd deviation data to form a separate data set
- group and average mean and standard deviation measurements by subject and activity

Included in this repo you should find:
- Read me
- Codebook for this assignment in both Word and MD formats
- run_analysis.R  to provide the code itself
- tidy_data_grouped_averaged_saved  provides the mean & std dev measurements grouped by subject and activity
- an annotated instruction list in Word containing code with comments
