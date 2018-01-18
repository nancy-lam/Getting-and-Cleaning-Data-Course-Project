A- Download source data https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and unzip it to R

B- Reading files

   - Reading trainings tables
   - Reading testing tables
   - Reading feature vector
   - Reading activity labels
   - Assigning column names

C- Create one R script called run_analysis.R that does the following

1. Merging the training and the test sets to create one data set.

   - Concatenate individual data tables to make single data table

   - Remove individual data tables to save memory

   - Assign column names

2. Extracting only the measurements on the mean and standard deviation for each measurement

   - Determine columns of data set to keep based on column name...

   - Keep data in these columns only

3. Uses descriptive activity names to name the activities in the data set

   - Replace activity values with named factor levels

4. Appropriately labels the data set with descriptive variable names.

   - Get column names

   - Remove special characters

   - Expand abbreviations and clean up names

   - Correct typo

   - Use new labels as column names

5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

   - Group by subject and activity and summarise using mean

   - Output to file "tidy_data.txt"


