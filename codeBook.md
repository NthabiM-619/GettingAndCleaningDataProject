Data

The tidydata.txt data file is a text file that is containing the spacr separated values.
The first row contains the names of the variables which are listed and described in the variables section.
The following rows contains the values of these variables.

VARIABLES
Each row contains a given subject and activity, 79 averaged signal measurements.

IDENTIFIERS
subject
subject identifiers, integer, ranges, from 1 - 30

actvity
Activity identifiers, string with 6 possible values:
WALKING_DOWNSTAIRS: subject was walking sownstairs
SITTING: subject was sitting
WALKING: the subject was walking
WALKING_UPSTAIRS: subject was walking upstairs
SATNDING: the subjec was standing
LAYING: subject was laying the measurements average.

The tidy data contains 6 rows(Averaged based on activity) and 68 columns (66 variables and activity labels)

subject activity timeBodyAccelerometer-mean()-X
timeBodyAccelerometer-mean()-Y timeBodyAccelerometer-mean()-Z
timeGravityAccelerometer-mean()-X timeGravityAccelerometer-mean()-Y
timeGravityAccelerometer-mean()-Z timeBodyAccelerometerJerk-mean()-X
timeBodyAccelerometerJerk-mean()-Y timeBodyAccelerometerJerk-mean()-Z
timeBodyGyroscope-mean()-X timeBodyGyroscope-mean()-Y
timeBodyGyroscope-mean()-Z timeBodyGyroscopeJerk-mean()-X
timeBodyGyroscopeJerk-mean()-Y timeBodyGyroscopeJerk-mean()-Z
timeBodyAccelerometerMagnitude-mean()
timeGravityAccelerometerMagnitude-mean()
timeBodyAccelerometerJerkMagnitude-mean() timeBodyGyroscopeMagnitude-mean()
timeBodyGyroscopeJerkMagnitude-mean() frequencyBodyAccelerometer-mean()-X
 frequencyBodyAccelerometer-mean()-Y frequencyBodyAccelerometer-mean()-Z
 frequencyBodyAccelerometerJerk-mean()-X
frequencyBodyAccelerometerJerk-mean()-Y
frequencyBodyAccelerometerJerk-mean()-Z frequencyBodyGyroscope-mean()-X
 frequencyBodyGyroscope-mean()-Y frequencyBodyGyroscope-mean()-Z
 frequencyBodyAccelerometerMagnitude-mean()
frequencyBodyAccelerometerJerkMagnitude-mean()
frequencyBodyGyroscopeMagnitude-mean()
frequencyBodyGyroscopeJerkMagnitude-mean()

The dplyr package was used to get the script of the tidy independent data set.
