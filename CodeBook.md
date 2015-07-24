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

## Identifiers

* `subject` - ID of the test subject
* `activity` - Type of activity (measurements)
* 

## Measurements

<br>1	tBodyAccMeanX
<br>2	tBodyAccMeanY
<br>3	tBodyAccMeanZ
<br>4	tBodyAccStdX
<br>5	tBodyAccStdY
6	tBodyAccStdZ
7	tGravityAccMeanX
8	tGravityAccMeanY
9	tGravityAccMeanZ
10	tGravityAccStdX
11	tGravityAccStdY
12	tGravityAccStdZ
13	tBodyAccJerkMeanX
14	tBodyAccJerkMeanY
15	tBodyAccJerkMeanZ
16	tBodyAccJerkStdX
17	tBodyAccJerkStdY
18	tBodyAccJerkStdZ
19	tBodyGyroMeanX
20	tBodyGyroMeanY
21	tBodyGyroMeanZ
22	tBodyGyroStdX
23	tBodyGyroStdY
24	tBodyGyroStdZ
25	tBodyGyroJerkMeanX
26	tBodyGyroJerkMeanY
27	tBodyGyroJerkMeanZ
28	tBodyGyroJerkStdX
29	tBodyGyroJerkStdY
30	tBodyGyroJerkStdZ
31	tBodyAccMagMean
32	tBodyAccMagStd
33	tGravityAccMagMean
34	tGravityAccMagStd
35	tBodyAccJerkMagMean
36	tBodyAccJerkMagStd
37	tBodyGyroMagMean
38	tBodyGyroMagStd
39	tBodyGyroJerkMagMean
40	tBodyGyroJerkMagStd
41	fBodyAccMeanX
42	fBodyAccMeanY
43	fBodyAccMeanZ
44	fBodyAccStdX
45	fBodyAccStdY
46	fBodyAccStdZ
47	fBodyAccJerkMeanX
48	fBodyAccJerkMeanY
49	fBodyAccJerkMeanZ
50	fBodyAccJerkStdX
51	fBodyAccJerkStdY
52	fBodyAccJerkStdZ
53	fBodyGyroMeanX
54	fBodyGyroMeanY
55	fBodyGyroMeanZ
56	fBodyGyroStdX
57	fBodyGyroStdY
58	fBodyGyroStdZ
59	fBodyAccMagMean
60	fBodyAccMagStd
61	fBodyBodyAccJerkMagMean
62	fBodyBodyAccJerkMagStd
63	fBodyBodyGyroMagMean
64	fBodyBodyGyroMagStd
65	fBodyBodyGyroJerkMagMean
66	fBodyBodyGyroJerkMagStd

## Activity Labels

* `WALKING` (value `1`): subject performed activity - walking during the test
* `WALKING_UPSTAIRS` (value `2`): subject performed activity -walking up a staircase during the test
* `WALKING_DOWNSTAIRS` (value `3`): subject performed activity - walking down a staircase during the test
* `SITTING` (value `4`): subject performed activity -sitting during the test
* `STANDING` (value `5`): subject performed activity - standing during the test
* `LAYING` (value `6`): subject performed activity - laying down during the test
