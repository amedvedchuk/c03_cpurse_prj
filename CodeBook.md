
# General desription

Output result set contains average of each variable for each activity and each subject.

Variables with prefix "MEAN" was calculated as mean() by each subject and activity from corresponding feature variables from files:
* "data/incoming/UCI HAR Dataset/train/X_train.txt"
* "data/incoming/UCI HAR Dataset/test/X_test.txt"

The meaning of underlying feature variables described in detail in files: 
* "data/incoming/UCI HAR Dataset/features_info.txt" 
* "data/incoming/UCI HAR Dataset/features.txt".

**Please note!** Brackets ("()") and dashes ("-") was removed from original variable names.
So for example if you need to address to variable "tBodyAcc-mean()-X" from original data you should use variable "MEANtBodyAccmeanX" from this codebook and so on.

# Output variable list

ID|Variable|Type|Description
---|---------------|------------|-------------------------------------------------------
1.   |subject | numeric | An identifier of the subject who carried out the experiment; range - 1:30
2.   |activity | character |  An activity label; possile values: WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING
3.	|MEANtBodyAccmeanX | numeric | mean by subject and activity of corresponding feature variable
4.	|MEANtBodyAccmeanY | numeric | mean by subject and activity of corresponding feature variable
5.	|MEANtBodyAccmeanZ | numeric | mean by subject and activity of corresponding feature variable
6.	|MEANtBodyAccstdX | numeric | mean by subject and activity of corresponding feature variable
7.	|MEANtBodyAccstdY | numeric | mean by subject and activity of corresponding feature variable
8.	|MEANtBodyAccstdZ | numeric | mean by subject and activity of corresponding feature variable
9.	|MEANtGravityAccmeanX | numeric | mean by subject and activity of corresponding feature variable
10.	|MEANtGravityAccmeanY | numeric | mean by subject and activity of corresponding feature variable
11.	|MEANtGravityAccmeanZ | numeric | mean by subject and activity of corresponding feature variable
12.	|MEANtGravityAccstdX | numeric | mean by subject and activity of corresponding feature variable
13.	|MEANtGravityAccstdY | numeric | mean by subject and activity of corresponding feature variable
14.	|MEANtGravityAccstdZ | numeric | mean by subject and activity of corresponding feature variable
15.	|MEANtBodyAccJerkmeanX | numeric | mean by subject and activity of corresponding feature variable
16.	|MEANtBodyAccJerkmeanY | numeric | mean by subject and activity of corresponding feature variable
17.	|MEANtBodyAccJerkmeanZ | numeric | mean by subject and activity of corresponding feature variable
18.	|MEANtBodyAccJerkstdX | numeric | mean by subject and activity of corresponding feature variable
19.	|MEANtBodyAccJerkstdY | numeric | mean by subject and activity of corresponding feature variable
20.	|MEANtBodyAccJerkstdZ | numeric | mean by subject and activity of corresponding feature variable
21.	|MEANtBodyGyromeanX | numeric | mean by subject and activity of corresponding feature variable
22.	|MEANtBodyGyromeanY | numeric | mean by subject and activity of corresponding feature variable
23.	|MEANtBodyGyromeanZ | numeric | mean by subject and activity of corresponding feature variable
24.	|MEANtBodyGyrostdX | numeric | mean by subject and activity of corresponding feature variable
25.	|MEANtBodyGyrostdY | numeric | mean by subject and activity of corresponding feature variable
26.	|MEANtBodyGyrostdZ | numeric | mean by subject and activity of corresponding feature variable
27.	|MEANtBodyGyroJerkmeanX | numeric | mean by subject and activity of corresponding feature variable
28.	|MEANtBodyGyroJerkmeanY | numeric | mean by subject and activity of corresponding feature variable
29.	|MEANtBodyGyroJerkmeanZ | numeric | mean by subject and activity of corresponding feature variable
30.	|MEANtBodyGyroJerkstdX | numeric | mean by subject and activity of corresponding feature variable
31.	|MEANtBodyGyroJerkstdY | numeric | mean by subject and activity of corresponding feature variable
32.	|MEANtBodyGyroJerkstdZ | numeric | mean by subject and activity of corresponding feature variable
33.	|MEANtBodyAccMagmean | numeric | mean by subject and activity of corresponding feature variable
34.	|MEANtBodyAccMagstd | numeric | mean by subject and activity of corresponding feature variable
35.	|MEANtGravityAccMagmean | numeric | mean by subject and activity of corresponding feature variable
36.	|MEANtGravityAccMagstd | numeric | mean by subject and activity of corresponding feature variable
37.	|MEANtBodyAccJerkMagmean | numeric | mean by subject and activity of corresponding feature variable
38.	|MEANtBodyAccJerkMagstd | numeric | mean by subject and activity of corresponding feature variable
39.	|MEANtBodyGyroMagmean | numeric | mean by subject and activity of corresponding feature variable
40.	|MEANtBodyGyroMagstd | numeric | mean by subject and activity of corresponding feature variable
41.	|MEANtBodyGyroJerkMagmean | numeric | mean by subject and activity of corresponding feature variable
42.	|MEANtBodyGyroJerkMagstd | numeric | mean by subject and activity of corresponding feature variable
43.	|MEANfBodyAccmeanX | numeric | mean by subject and activity of corresponding feature variable
44.	|MEANfBodyAccmeanY | numeric | mean by subject and activity of corresponding feature variable
45.	|MEANfBodyAccmeanZ | numeric | mean by subject and activity of corresponding feature variable
46.	|MEANfBodyAccstdX | numeric | mean by subject and activity of corresponding feature variable
47.	|MEANfBodyAccstdY | numeric | mean by subject and activity of corresponding feature variable
48.	|MEANfBodyAccstdZ | numeric | mean by subject and activity of corresponding feature variable
49.	|MEANfBodyAccmeanFreqX | numeric | mean by subject and activity of corresponding feature variable
50.	|MEANfBodyAccmeanFreqY | numeric | mean by subject and activity of corresponding feature variable
51.	|MEANfBodyAccmeanFreqZ | numeric | mean by subject and activity of corresponding feature variable
52.	|MEANfBodyAccJerkmeanX | numeric | mean by subject and activity of corresponding feature variable
53.	|MEANfBodyAccJerkmeanY | numeric | mean by subject and activity of corresponding feature variable
54.	|MEANfBodyAccJerkmeanZ | numeric | mean by subject and activity of corresponding feature variable
55.	|MEANfBodyAccJerkstdX | numeric | mean by subject and activity of corresponding feature variable
56.	|MEANfBodyAccJerkstdY | numeric | mean by subject and activity of corresponding feature variable
57.	|MEANfBodyAccJerkstdZ | numeric | mean by subject and activity of corresponding feature variable
58.	|MEANfBodyAccJerkmeanFreqX | numeric | mean by subject and activity of corresponding feature variable
59.	|MEANfBodyAccJerkmeanFreqY | numeric | mean by subject and activity of corresponding feature variable
60.	|MEANfBodyAccJerkmeanFreqZ | numeric | mean by subject and activity of corresponding feature variable
61.	|MEANfBodyGyromeanX | numeric | mean by subject and activity of corresponding feature variable
62.	|MEANfBodyGyromeanY | numeric | mean by subject and activity of corresponding feature variable
63.	|MEANfBodyGyromeanZ | numeric | mean by subject and activity of corresponding feature variable
64.	|MEANfBodyGyrostdX | numeric | mean by subject and activity of corresponding feature variable
65.	|MEANfBodyGyrostdY | numeric | mean by subject and activity of corresponding feature variable
66.	|MEANfBodyGyrostdZ | numeric | mean by subject and activity of corresponding feature variable
67.	|MEANfBodyGyromeanFreqX | numeric | mean by subject and activity of corresponding feature variable
68.	|MEANfBodyGyromeanFreqY | numeric | mean by subject and activity of corresponding feature variable
69.	|MEANfBodyGyromeanFreqZ | numeric | mean by subject and activity of corresponding feature variable
70.	|MEANfBodyAccMagmean | numeric | mean by subject and activity of corresponding feature variable
71.	|MEANfBodyAccMagstd | numeric | mean by subject and activity of corresponding feature variable
72.	|MEANfBodyAccMagmeanFreq | numeric | mean by subject and activity of corresponding feature variable
73.	|MEANfBodyBodyAccJerkMagmean | numeric | mean by subject and activity of corresponding feature variable
74.	|MEANfBodyBodyAccJerkMagstd | numeric | mean by subject and activity of corresponding feature variable
75.	|MEANfBodyBodyAccJerkMagmeanFreq | numeric | mean by subject and activity of corresponding feature variable
76.	|MEANfBodyBodyGyroMagmean | numeric | mean by subject and activity of corresponding feature variable
77.	|MEANfBodyBodyGyroMagstd | numeric | mean by subject and activity of corresponding feature variable
78.	|MEANfBodyBodyGyroMagmeanFreq | numeric | mean by subject and activity of corresponding feature variable
79.	|MEANfBodyBodyGyroJerkMagmean | numeric | mean by subject and activity of corresponding feature variable
80.	|MEANfBodyBodyGyroJerkMagstd | numeric | mean by subject and activity of corresponding feature variable
81.	|MEANfBodyBodyGyroJerkMagmeanFreq | numeric | mean by subject and activity of corresponding feature variable
