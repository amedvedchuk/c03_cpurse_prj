
Output result set contains average of each variable for each activity and each subject.

Variables with prefix "MEAN." was calculated as mean() by each subject and activity from corresponding feature variables from files:
* "data/incoming/UCI HAR Dataset/train/X_train.txt"
* "data/incoming/UCI HAR Dataset/test/X_test.txt"

The meaning of underlying feature variables described in detail in file "data/incoming/UCI HAR Dataset/features_info.txt" and "data/incoming/UCI HAR Dataset/features.txt".

Please note that brackets ("()") was removed from variable names and dashes ("-") was replaced by dot ("."). 
So for example if you need to address to variable "tBodyAcc-mean()-X" from original data you should use variable "MEAN.tBodyAcc.mean.X" from this codebook and so on.


1   subject - An identifier of the subject who carried out the experiment; range - 1:30
2   activity -  An activity label; possile values:
        WALKING
        WALKING_UPSTAIRS
        WALKING_DOWNSTAIRS
        SITTING
        STANDING
        LAYING
3	MEAN.tBodyAcc.mean.X - mean by subject and activity of corresponding feature variable
4	MEAN.tBodyAcc.mean.Y - mean by subject and activity of corresponding feature variable
5	MEAN.tBodyAcc.mean.Z - mean by subject and activity of corresponding feature variable
6	MEAN.tBodyAcc.std.X - mean by subject and activity of corresponding feature variable
7	MEAN.tBodyAcc.std.Y - mean by subject and activity of corresponding feature variable
8	MEAN.tBodyAcc.std.Z - mean by subject and activity of corresponding feature variable
9	MEAN.tGravityAcc.mean.X - mean by subject and activity of corresponding feature variable
10	MEAN.tGravityAcc.mean.Y - mean by subject and activity of corresponding feature variable
11	MEAN.tGravityAcc.mean.Z - mean by subject and activity of corresponding feature variable
12	MEAN.tGravityAcc.std.X - mean by subject and activity of corresponding feature variable
13	MEAN.tGravityAcc.std.Y - mean by subject and activity of corresponding feature variable
14	MEAN.tGravityAcc.std.Z - mean by subject and activity of corresponding feature variable
15	MEAN.tBodyAccJerk.mean.X - mean by subject and activity of corresponding feature variable
16	MEAN.tBodyAccJerk.mean.Y - mean by subject and activity of corresponding feature variable
17	MEAN.tBodyAccJerk.mean.Z - mean by subject and activity of corresponding feature variable
18	MEAN.tBodyAccJerk.std.X - mean by subject and activity of corresponding feature variable
19	MEAN.tBodyAccJerk.std.Y - mean by subject and activity of corresponding feature variable
20	MEAN.tBodyAccJerk.std.Z - mean by subject and activity of corresponding feature variable
21	MEAN.tBodyGyro.mean.X - mean by subject and activity of corresponding feature variable
22	MEAN.tBodyGyro.mean.Y - mean by subject and activity of corresponding feature variable
23	MEAN.tBodyGyro.mean.Z - mean by subject and activity of corresponding feature variable
24	MEAN.tBodyGyro.std.X - mean by subject and activity of corresponding feature variable
25	MEAN.tBodyGyro.std.Y - mean by subject and activity of corresponding feature variable
26	MEAN.tBodyGyro.std.Z - mean by subject and activity of corresponding feature variable
27	MEAN.tBodyGyroJerk.mean.X - mean by subject and activity of corresponding feature variable
28	MEAN.tBodyGyroJerk.mean.Y - mean by subject and activity of corresponding feature variable
29	MEAN.tBodyGyroJerk.mean.Z - mean by subject and activity of corresponding feature variable
30	MEAN.tBodyGyroJerk.std.X - mean by subject and activity of corresponding feature variable
31	MEAN.tBodyGyroJerk.std.Y - mean by subject and activity of corresponding feature variable
32	MEAN.tBodyGyroJerk.std.Z - mean by subject and activity of corresponding feature variable
33	MEAN.tBodyAccMag.mean - mean by subject and activity of corresponding feature variable
34	MEAN.tBodyAccMag.std - mean by subject and activity of corresponding feature variable
35	MEAN.tGravityAccMag.mean - mean by subject and activity of corresponding feature variable
36	MEAN.tGravityAccMag.std - mean by subject and activity of corresponding feature variable
37	MEAN.tBodyAccJerkMag.mean - mean by subject and activity of corresponding feature variable
38	MEAN.tBodyAccJerkMag.std - mean by subject and activity of corresponding feature variable
39	MEAN.tBodyGyroMag.mean - mean by subject and activity of corresponding feature variable
40	MEAN.tBodyGyroMag.std - mean by subject and activity of corresponding feature variable
41	MEAN.tBodyGyroJerkMag.mean - mean by subject and activity of corresponding feature variable
42	MEAN.tBodyGyroJerkMag.std - mean by subject and activity of corresponding feature variable
43	MEAN.fBodyAcc.mean.X - mean by subject and activity of corresponding feature variable
44	MEAN.fBodyAcc.mean.Y - mean by subject and activity of corresponding feature variable
45	MEAN.fBodyAcc.mean.Z - mean by subject and activity of corresponding feature variable
46	MEAN.fBodyAcc.std.X - mean by subject and activity of corresponding feature variable
47	MEAN.fBodyAcc.std.Y - mean by subject and activity of corresponding feature variable
48	MEAN.fBodyAcc.std.Z - mean by subject and activity of corresponding feature variable
49	MEAN.fBodyAcc.meanFreq.X - mean by subject and activity of corresponding feature variable
50	MEAN.fBodyAcc.meanFreq.Y - mean by subject and activity of corresponding feature variable
51	MEAN.fBodyAcc.meanFreq.Z - mean by subject and activity of corresponding feature variable
52	MEAN.fBodyAccJerk.mean.X - mean by subject and activity of corresponding feature variable
53	MEAN.fBodyAccJerk.mean.Y - mean by subject and activity of corresponding feature variable
54	MEAN.fBodyAccJerk.mean.Z - mean by subject and activity of corresponding feature variable
55	MEAN.fBodyAccJerk.std.X - mean by subject and activity of corresponding feature variable
56	MEAN.fBodyAccJerk.std.Y - mean by subject and activity of corresponding feature variable
57	MEAN.fBodyAccJerk.std.Z - mean by subject and activity of corresponding feature variable
58	MEAN.fBodyAccJerk.meanFreq.X - mean by subject and activity of corresponding feature variable
59	MEAN.fBodyAccJerk.meanFreq.Y - mean by subject and activity of corresponding feature variable
60	MEAN.fBodyAccJerk.meanFreq.Z - mean by subject and activity of corresponding feature variable
61	MEAN.fBodyGyro.mean.X - mean by subject and activity of corresponding feature variable
62	MEAN.fBodyGyro.mean.Y - mean by subject and activity of corresponding feature variable
63	MEAN.fBodyGyro.mean.Z - mean by subject and activity of corresponding feature variable
64	MEAN.fBodyGyro.std.X - mean by subject and activity of corresponding feature variable
65	MEAN.fBodyGyro.std.Y - mean by subject and activity of corresponding feature variable
66	MEAN.fBodyGyro.std.Z - mean by subject and activity of corresponding feature variable
67	MEAN.fBodyGyro.meanFreq.X - mean by subject and activity of corresponding feature variable
68	MEAN.fBodyGyro.meanFreq.Y - mean by subject and activity of corresponding feature variable
69	MEAN.fBodyGyro.meanFreq.Z - mean by subject and activity of corresponding feature variable
70	MEAN.fBodyAccMag.mean - mean by subject and activity of corresponding feature variable
71	MEAN.fBodyAccMag.std - mean by subject and activity of corresponding feature variable
72	MEAN.fBodyAccMag.meanFreq - mean by subject and activity of corresponding feature variable
73	MEAN.fBodyBodyAccJerkMag.mean - mean by subject and activity of corresponding feature variable
74	MEAN.fBodyBodyAccJerkMag.std - mean by subject and activity of corresponding feature variable
75	MEAN.fBodyBodyAccJerkMag.meanFreq - mean by subject and activity of corresponding feature variable
76	MEAN.fBodyBodyGyroMag.mean - mean by subject and activity of corresponding feature variable
77	MEAN.fBodyBodyGyroMag.std - mean by subject and activity of corresponding feature variable
78	MEAN.fBodyBodyGyroMag.meanFreq - mean by subject and activity of corresponding feature variable
79	MEAN.fBodyBodyGyroJerkMag.mean - mean by subject and activity of corresponding feature variable
80	MEAN.fBodyBodyGyroJerkMag.std - mean by subject and activity of corresponding feature variable
81	MEAN.fBodyBodyGyroJerkMag.meanFreq - mean by subject and activity of corresponding feature variable
