# Coursera_project
This is the final project for coursera

Human Activity Recognition Using Smartphones Dataset for this project was used 

dplyr and tidyr were used to help format the data

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we (the group who collected the data) captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually.  

In part 1, I merge several different datasets. Orginally the data was split into a test and training set in which we have
now combined and made the columns headers our variables. 

In part 2 and 3, We then only took the mean and standard deviation calculations using the grep function on columns for any case of mean or std and made their names a bit cleaner so when we made the data tidy it was easier to understand what each variable meant.

In part 4, we substitued the activity numbers with the actual names of the acitivities

In part 5, we made the data tidy with the gather function from tidyr and then with dplyr made a mean column and std column for add insights


run_analysis.R is the R code for the project

CodeBook.md is the description of what the variables mean at each given point

files used:
- 'README.txt'

- 'features.txt': List of all features.

- 'train/X_train.txt': Training set.

- 'train/y_train.txt': Training labels.

- 'test/X_test.txt': Test set.

- 'test/y_test.txt': Test labels.



