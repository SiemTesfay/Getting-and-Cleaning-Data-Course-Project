# Getting-and-Cleaning-Data-Course-Project
This repo is created for Peer-graded Assignment: Getting and Cleaning Data Course Project. The course is online and offered via Coursera.org. 
### What is included in this Repo?
This repo has 3 file other than the 'README.md'.
  1. CODEBOOK.md
  2. run_analysis.R
  3. tide_dataset.txt
  
**NB: - Those four files are review criteria for the project grading.**

#### CODEBOOK.md
This file contains of recordes commited to the original dataset. It containes the modifications, identifiers and measurments.
#### tide_dataset.txt
Is the dataset after the modifications was commited. 
#### run_analysis.R
This is the R file that contains the script for the modification. It does:
  1. Download the dataset
  2. Read both the train and test datasets. Then,merge them into x(measurements), y(activity) and subject.
  3. Load the data(x's) feature, activity info and extract columns named 'mean'(-mean) and 'standard'(-std). Also, modify column names to be more descriptive by removing symbols like -, (, ))
  4. Extract data by selected columns(from step 3), and merge x, y(activity) and subject data. Also, replace y(activity) column to it's name by refering activity
  label (loaded step 3)
  5. Generate 'Tidy Dataset' that consists of the average (mean) of each variable for each subject and each activity. The result is shown in the file
  tidy_dataset.txt.
