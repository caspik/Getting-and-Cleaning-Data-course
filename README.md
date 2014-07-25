Getting-and-Cleaning-Data-course-project
================================
The project contains a file run_analysis.R that does the following:

- Merges the training and the test sets to create one data set.
- Extracts only the measurements on the mean and standard deviation for each measurement.
- Uses descriptive activity names to name the activities in the data set
- Labels the data set with descriptive activity names.
- Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

To run the project you will need to complete the following steps:
- Download and unzip the source data. Unzipped data should be an ```UCI HAR Dataset``` folder.
- Run run_analysis.R within a directory with ```UCI HAR Dataset``` folder.
- Running the script results in a creation of tidy_data.txt.

Note:
The following libraries are required to run the script: ```data.table``` and ```reshape2```.
