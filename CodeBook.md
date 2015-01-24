This code book describes all the variables and summaries calculated using the R script, along with units, and any other relevant information to clean up the data.

The data source

Original data is avaliable from: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Data set information is avaliable from: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Specifically, the dataset consists of the followings:

      'README.txt'

      'features_info.txt': Shows information about the variables used on the feature vector.

      'features.txt': List of all features.

      'activity_labels.txt': Links the class labels with their activity name.

      'train/X_train.txt': Training set.

      'train/y_train.txt': Training labels.

      'test/X_test.txt': Test set.

      'test/y_test.txt': Test labels.

      'train/subject_train.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30.

      'train/Inertial Signals/total_acc_x_train.txt': The acceleration signal from the smartphone accelerometer X axis in standard gravity units 'g'.The similar description applies to  the 'total_acc_y_train.txt' and 'total_acc_z_train.txt' files for the Y and Z axis.

      'train/Inertial Signals/body_acc_x_train.txt': The body acceleration signal obtained by subtracting the gravity from the total acceleration.

      'train/Inertial Signals/body_gyro_x_train.txt': The angular velocity vector measured by the gyroscope for each window sample. The units are radians/second.

Purposes of cleaning of the data：

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.


