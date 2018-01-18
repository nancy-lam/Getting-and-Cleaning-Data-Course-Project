A- Download source data https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and unzip it to R

B- Reading files

   - Reading trainings tables
   - Reading testing tables
   - Reading feature vector
   - Reading activity labels
   - Assigning column names

C- Create one R script called run_analysis.R that does the following

1. Merging the training and the test sets to create one data set.

# concatenate individual data tables to make single data table

# remove individual data tables to save memory

# assign column names

2. Extracting only the measurements on the mean and standard deviation for each measurement

# determine columns of data set to keep based on column name...

# ... and keep data in these columns only

3. Uses descriptive activity names to name the activities in the data set

# replace activity values with named factor levels

4. Appropriately labels the data set with descriptive variable names.

# get column names

# remove special characters

# expand abbreviations and clean up names

# correct typo

# use new labels as column names

5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

# group by subject and activity and summarise using mean

# output to file "tidy_data.txt"


