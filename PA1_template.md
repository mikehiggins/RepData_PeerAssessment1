# Reproducible Research: Peer Assessment 1


## Loading and preprocessing the data
Source file is CSV format in a zipped archive. First will unzip and then read the csv file into a dataframe.

```r
setwd("~/datascience/represearch/repdataProject")
dataFile <- "activity.zip"
dataFile <- unzip(dataFile)
```


```r
df <- read.csv(dataFile)
```

## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
