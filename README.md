## Getting and Cleaning Data Project

* Unzip the source in some dir
  ( https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip )

* Copy run_analysis.R to the same dir

* In R or RStudio set workdirectory on need dir: setwd("path\to\dir")

* source("run_analysis.R")

* Run the R script, it will read the dataset and write these files:

  merged_clean_data.txt

  data_set_with_the_averages.txt

  The script normally runs for ~30 seconds, but the exact number depends on your system.
