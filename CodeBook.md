##Code Book
This is a code book that describes the variables, data, and any transformations or work that you performed to clean up the data.

#Dataset
Datasets being used are datasets from University of California Irvie in which the experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years.  Six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) have been perform by peoples who are wearing a smartphone (Samsung Galaxy S II) on the waist. All the data are captured using its embedded accelerometer and gyroscopemade of the smartphone 

#Raw Data transformation

<br /> The raw data sets are processed with the script run_analysis.R script to create a tidy data set.

<br />Merge training and test sets Test and training data, subject ids and activity ids are merged to obtain a single data set. <br />Variables are labelled with the names assigned by original collectors.

<br />Extract mean and standard deviation variables Keep only the values of estimated mean and standard deviation .

<br />Get descriptive activity names A new column is added to intermediate data set with the activity description.

<br />Get abel variables appropriately Labels given from the original collectors were changed to get valid/more descriptive R names

<br />Create a tidy data set From the intermediate data set is created a final tidy data set where numeric variables are averaged for each activity and each subject.
