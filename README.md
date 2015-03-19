
# Repo content

Repository contains next files: 
* CodeBook.md - Code book descroption file fro output dataset variables
* README.md - this document with run flow description. 
* run_analysis.R - R script for performing data analysis and produce output dataset as file.

# Prepare to run

Script requires packages:
* plyr
* LaF

So you need to install these packages:
```{r}
install.packages("plyr")
install.packages("LaF")
```

# Runnins analysis script

To run analysis script do the following steps:

1. set working directory in place where run_analysis.R is located
2. run following command in R console
```{r}
source("run_analysis.R")
```
3. After run variable "resultData" will contains resultind data set. Also data set will be written to file defined in "outputTable" variable (function write.table() is used with row.name=FALSE)

# Interpret the resuls

Read CodeBook.md for result variables description and data manipulation.

# Analysing alghorithm

Scripts performs actions according to next algorithm:

1. Download and unzip data if it's not downloaded yet.
2. Read metadata: activity map, features list
3. define variables to be read from main dataset (mean and standard deviation of features)
4. Read train dataset, merge with subject and action columns and provide corect names.
5. Read test dataset, merge with subject and action columns and provide corect names.
6. Combine datasets from item 4 and 5 using rowbind to obtain resulting dataset.
7. Calculate mean for all features variables from dataset by each subject and action. 
8. Save the result from item 8 into output dataset named "resultData" and write to file (by default - "data/output.table").

