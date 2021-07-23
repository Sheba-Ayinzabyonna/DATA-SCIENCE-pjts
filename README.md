                    # Women Tech Series Program - Data Science Track
                    Exploratory Data Analysis Assignment.
Exploratory Data Analysis refers to the critical process of performing initial investigations on data so as to discover patterns, to spot anomalies, to test hypotheses and check assumptions with the help of summary statistics and graphical representations.
After downloading the white variant of Wine Quality data set (https://archive.ics.uci.edu/ml/datasets/wine+quality) from the UCI Machine Learning Repository, data was seperated by delimiter.
First l had to import the following libraries, pandas, numpy, seaborn, matplotlib - the pyplot was also imported from the matplotlib.
Data was read from the white variant of the Wine Quality dataset 
Used the head() and tail() functions to read the data of the pandas library. 
      The top 5 rows were displayed with the head() function 
      The bottom 5 rows were displayed with the tail() function
I was able to determine the total number of rows and columns in the dataset 
Columns and rows were identified with the corresponding data types and there was no null values
Statistics data summary was also achieved.
Used the unique function considering the quality column as the dependent variable
I used the corr() function to find the correlations and visualised the correlation matrix using the heatmap in seaborn. Seaborn is a visualization library in python which is built on top of matplotlib.
       The strong positive and strong negative correlations were listed
A box plot for the data was plotted because it provides an insight into distribution properties of the data
