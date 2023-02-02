# Assignment4

Name: Divya Pothuru 
NetworkId:DXP62920
Video Link: https://drive.google.com/file/d/1EiyJWsTsAVKsi40uW9FPw8gHb-VuqFr5/view?usp=share_link

1.. Data Manipulation
a. Read the provided CSV file ‘data.csv’.
b. https://drive.google.com/drive/folders/1h8C3mLsso-R-sIOLsvoYwPLzy2fJ4IOF?usp=sharing
c. Show the basic statistical description about the data.
d. Check if the data has null values.
i. Replace the null values with the mean
e. Select at least two columns and aggregate the data using: min, max, count, mean.
f. Filter the dataframe to select the rows with calories values between 500 and 1000.
g. Filter the dataframe to select the rows with calories values > 500 and pulse < 100.
h. Create a new “df_modified” dataframe that contains all the columns from df except for
“Maxpulse”.
i. Delete the “Maxpulse” column from the main df dataframe
j. Convert the datatype of Calories column to int datatype.
k. Using pandas create a scatter plot for the two columns (Duration and Calories)
SOLUTION:
========
We have imported the modules pandas and matplotlib.pyplot and then reading the csv file and then performed all the above questions of the data duration and calories
<img width="944" alt="image" src="https://user-images.githubusercontent.com/122486644/216225518-39cf99a5-80bb-4481-9f30-f2f667cbe8bd.png">




2. Linear Regression
a) Import the given “Salary_Data.csv”
b) Split the data in train_test partitions, such that 1/3 of the data is reserved as test subset.
c) Train and predict the model.
d) Calculate the mean_squared error
e) Visualize both train and test data using scatter plot.
SOLUTION:
=========

first we have imported the csv file and then split the dataset of both training set and test set and then fitting Simple Linear Regression to the training set and then predicting the test set values and then calculating mean squared error and then Visualising the Training set results and test set results.
Then it displays the graphs of both training set and test set results graph..
Then output is as follows:
Training set:
![image](https://user-images.githubusercontent.com/122486644/216214760-23c497c9-bd85-4cce-ae14-28bd2c886808.png)
Test set:
![image](https://user-images.githubusercontent.com/122486644/216214810-b36fed04-25d6-467c-adbb-e6efc35a81bb.png)
Mean squared error:
<img width="453" alt="image" src="https://user-images.githubusercontent.com/122486644/216214855-f7dbd7fc-086c-4cab-90bf-466ab6478df7.png">




