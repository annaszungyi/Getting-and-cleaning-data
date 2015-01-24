#CodeBook

##Data source
Original data: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Description of the dataset: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

## Data
The UCI HAR Dataset contains the following files:
*README.txt
*features_info.txt: Shows information about the variables used on the feature vector.
*features.txt: List of all features.
*activity_labels.txt: Links the class labels with their activity name.
*train/X_train.txt: Training set.
*train/y_train.txt': Training labels.
*test/X_test.txt': Test set.
*test/y_test.txt': Test labels.

## Transformation steps

*Merges the training and the test sets to create one data set.
*Extracts only the measurements on the mean and standard deviation for each measurement.
*Uses descriptive activity names to name the activities in the data set
*Appropriately labels the data set with descriptive activity names.
*Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

##run_anaysis.R

*Require libraries: reshapre2 and data.table
*Load test and train data
*Load the features and activity labels
*Extract the mean and standard deviation column names and data
*Process the data
*Merge data set


  