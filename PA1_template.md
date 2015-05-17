# Reproducible Research: Peer Assessment 1


## Loading and preprocessing the data
Using the activities.csv file found with our course, we'll load the data into a variable.

The variables included in this dataset are:

1. steps: Number of steps taking in a 5-minute interval (missing values are coded as NA )
2. date: The date on which the measurement was taken in YYYY-MM-DD format
3. interval: Identifier for the 5-minute interval in which measurement was taken

'''{r}
data = read.csv('activity.csv', header = T)
names(data)
'''


## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
