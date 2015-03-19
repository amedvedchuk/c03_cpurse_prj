
# General desription

Output result set contains average of each variable for each activity and each subject.

Variables with prefix "MEAN." was calculated as mean() by each subject and activity from corresponding feature variables from files:
* "data/incoming/UCI HAR Dataset/train/X_train.txt"
* "data/incoming/UCI HAR Dataset/test/X_test.txt"

The meaning of underlying feature variables described in detail in file "data/incoming/UCI HAR Dataset/features_info.txt" and "data/incoming/UCI HAR Dataset/features.txt".

Please note that brackets ("()") was removed from variable names and dashes ("-") was replaced by dot ("."). 
So for example if you need to address to variable "tBodyAcc-mean()-X" from original data you should use variable "MEAN.tBodyAcc.mean.X" from this codebook and so on.

# Output variable list

ID|Variable|Type|Description
---|---------------|------------|-------------------------------------------------------
1.   |subject | numeric | An identifier of the subject who carried out the experiment; range - 1:30
2.   |activity | character |  An activity label; possile values: WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING
3.	|MEAN.tBodyAcc.mean.X | numeric | mean by subject and activity of corresponding feature variable
4.	|MEAN.tBodyAcc.mean.Y | numeric | mean by subject and activity of corresponding feature variable
5.	|MEAN.tBodyAcc.mean.Z | numeric | mean by subject and activity of corresponding feature variable
6.	|MEAN.tBodyAcc.std.X | numeric | mean by subject and activity of corresponding feature variable
7.	|MEAN.tBodyAcc.std.Y | numeric | mean by subject and activity of corresponding feature variable
8.	|MEAN.tBodyAcc.std.Z | numeric | mean by subject and activity of corresponding feature variable
9.	|MEAN.tGravityAcc.mean.X | numeric | mean by subject and activity of corresponding feature variable
10.	|MEAN.tGravityAcc.mean.Y | numeric | mean by subject and activity of corresponding feature variable
11.	|MEAN.tGravityAcc.mean.Z | numeric | mean by subject and activity of corresponding feature variable
12.	|MEAN.tGravityAcc.std.X | numeric | mean by subject and activity of corresponding feature variable
13.	|MEAN.tGravityAcc.std.Y | numeric | mean by subject and activity of corresponding feature variable
14.	|MEAN.tGravityAcc.std.Z | numeric | mean by subject and activity of corresponding feature variable
15.	|MEAN.tBodyAccJerk.mean.X | numeric | mean by subject and activity of corresponding feature variable
16.	|MEAN.tBodyAccJerk.mean.Y | numeric | mean by subject and activity of corresponding feature variable
17.	|MEAN.tBodyAccJerk.mean.Z | numeric | mean by subject and activity of corresponding feature variable
18.	|MEAN.tBodyAccJerk.std.X | numeric | mean by subject and activity of corresponding feature variable
19.	|MEAN.tBodyAccJerk.std.Y | numeric | mean by subject and activity of corresponding feature variable
20.	|MEAN.tBodyAccJerk.std.Z | numeric | mean by subject and activity of corresponding feature variable
21.	|MEAN.tBodyGyro.mean.X | numeric | mean by subject and activity of corresponding feature variable
22.	|MEAN.tBodyGyro.mean.Y | numeric | mean by subject and activity of corresponding feature variable
23.	|MEAN.tBodyGyro.mean.Z | numeric | mean by subject and activity of corresponding feature variable
24.	|MEAN.tBodyGyro.std.X | numeric | mean by subject and activity of corresponding feature variable
25.	|MEAN.tBodyGyro.std.Y | numeric | mean by subject and activity of corresponding feature variable
26.	|MEAN.tBodyGyro.std.Z | numeric | mean by subject and activity of corresponding feature variable
27.	|MEAN.tBodyGyroJerk.mean.X | numeric | mean by subject and activity of corresponding feature variable
28.	|MEAN.tBodyGyroJerk.mean.Y | numeric | mean by subject and activity of corresponding feature variable
29.	|MEAN.tBodyGyroJerk.mean.Z | numeric | mean by subject and activity of corresponding feature variable
30.	|MEAN.tBodyGyroJerk.std.X | numeric | mean by subject and activity of corresponding feature variable
31.	|MEAN.tBodyGyroJerk.std.Y | numeric | mean by subject and activity of corresponding feature variable
32.	|MEAN.tBodyGyroJerk.std.Z | numeric | mean by subject and activity of corresponding feature variable
33.	|MEAN.tBodyAccMag.mean | numeric | mean by subject and activity of corresponding feature variable
34.	|MEAN.tBodyAccMag.std | numeric | mean by subject and activity of corresponding feature variable
35.	|MEAN.tGravityAccMag.mean | numeric | mean by subject and activity of corresponding feature variable
36.	|MEAN.tGravityAccMag.std | numeric | mean by subject and activity of corresponding feature variable
37.	|MEAN.tBodyAccJerkMag.mean | numeric | mean by subject and activity of corresponding feature variable
38.	|MEAN.tBodyAccJerkMag.std | numeric | mean by subject and activity of corresponding feature variable
39.	|MEAN.tBodyGyroMag.mean | numeric | mean by subject and activity of corresponding feature variable
40.	|MEAN.tBodyGyroMag.std | numeric | mean by subject and activity of corresponding feature variable
41.	|MEAN.tBodyGyroJerkMag.mean | numeric | mean by subject and activity of corresponding feature variable
42.	|MEAN.tBodyGyroJerkMag.std | numeric | mean by subject and activity of corresponding feature variable
43.	|MEAN.fBodyAcc.mean.X | numeric | mean by subject and activity of corresponding feature variable
44.	|MEAN.fBodyAcc.mean.Y | numeric | mean by subject and activity of corresponding feature variable
45.	|MEAN.fBodyAcc.mean.Z | numeric | mean by subject and activity of corresponding feature variable
46.	|MEAN.fBodyAcc.std.X | numeric | mean by subject and activity of corresponding feature variable
47.	|MEAN.fBodyAcc.std.Y | numeric | mean by subject and activity of corresponding feature variable
48.	|MEAN.fBodyAcc.std.Z | numeric | mean by subject and activity of corresponding feature variable
49.	|MEAN.fBodyAcc.meanFreq.X | numeric | mean by subject and activity of corresponding feature variable
50.	|MEAN.fBodyAcc.meanFreq.Y | numeric | mean by subject and activity of corresponding feature variable
51.	|MEAN.fBodyAcc.meanFreq.Z | numeric | mean by subject and activity of corresponding feature variable
52.	|MEAN.fBodyAccJerk.mean.X | numeric | mean by subject and activity of corresponding feature variable
53.	|MEAN.fBodyAccJerk.mean.Y | numeric | mean by subject and activity of corresponding feature variable
54.	|MEAN.fBodyAccJerk.mean.Z | numeric | mean by subject and activity of corresponding feature variable
55.	|MEAN.fBodyAccJerk.std.X | numeric | mean by subject and activity of corresponding feature variable
56.	|MEAN.fBodyAccJerk.std.Y | numeric | mean by subject and activity of corresponding feature variable
57.	|MEAN.fBodyAccJerk.std.Z | numeric | mean by subject and activity of corresponding feature variable
58.	|MEAN.fBodyAccJerk.meanFreq.X | numeric | mean by subject and activity of corresponding feature variable
59.	|MEAN.fBodyAccJerk.meanFreq.Y | numeric | mean by subject and activity of corresponding feature variable
60.	|MEAN.fBodyAccJerk.meanFreq.Z | numeric | mean by subject and activity of corresponding feature variable
61.	|MEAN.fBodyGyro.mean.X | numeric | mean by subject and activity of corresponding feature variable
62.	|MEAN.fBodyGyro.mean.Y | numeric | mean by subject and activity of corresponding feature variable
63.	|MEAN.fBodyGyro.mean.Z | numeric | mean by subject and activity of corresponding feature variable
64.	|MEAN.fBodyGyro.std.X | numeric | mean by subject and activity of corresponding feature variable
65.	|MEAN.fBodyGyro.std.Y | numeric | mean by subject and activity of corresponding feature variable
66.	|MEAN.fBodyGyro.std.Z | numeric | mean by subject and activity of corresponding feature variable
67.	|MEAN.fBodyGyro.meanFreq.X | numeric | mean by subject and activity of corresponding feature variable
68.	|MEAN.fBodyGyro.meanFreq.Y | numeric | mean by subject and activity of corresponding feature variable
69.	|MEAN.fBodyGyro.meanFreq.Z | numeric | mean by subject and activity of corresponding feature variable
70.	|MEAN.fBodyAccMag.mean | numeric | mean by subject and activity of corresponding feature variable
71.	|MEAN.fBodyAccMag.std | numeric | mean by subject and activity of corresponding feature variable
72.	|MEAN.fBodyAccMag.meanFreq | numeric | mean by subject and activity of corresponding feature variable
73.	|MEAN.fBodyBodyAccJerkMag.mean | numeric | mean by subject and activity of corresponding feature variable
74.	|MEAN.fBodyBodyAccJerkMag.std | numeric | mean by subject and activity of corresponding feature variable
75.	|MEAN.fBodyBodyAccJerkMag.meanFreq | numeric | mean by subject and activity of corresponding feature variable
76.	|MEAN.fBodyBodyGyroMag.mean | numeric | mean by subject and activity of corresponding feature variable
77.	|MEAN.fBodyBodyGyroMag.std | numeric | mean by subject and activity of corresponding feature variable
78.	|MEAN.fBodyBodyGyroMag.meanFreq | numeric | mean by subject and activity of corresponding feature variable
79.	|MEAN.fBodyBodyGyroJerkMag.mean | numeric | mean by subject and activity of corresponding feature variable
80.	|MEAN.fBodyBodyGyroJerkMag.std | numeric | mean by subject and activity of corresponding feature variable
81.	|MEAN.fBodyBodyGyroJerkMag.meanFreq | numeric | mean by subject and activity of corresponding feature variable
