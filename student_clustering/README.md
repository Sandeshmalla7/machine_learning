# Student Clustering Project
## Overview
This project implements K-Means clustering to analyze the relationship between CGPA and IQ scores of students. The dataset consists of 200 entries, each containing a student's CGPA and IQ value.

### Dependencies

-Python 3.x

-Pandas

-NumPy

-Matplotlib

-Scikit-learn

#### Dataset
The dataset used is student_clustering.csv, which contains the following columns:


-cgpa: CGPA of the student

-iq: IQ score of the student

##### Steps

-Import Libraries: Loads necessary libraries for data manipulation and visualization.

-Load Dataset: Reads the CSV file into a Pandas DataFrame.

-Exploratory Data Analysis:
-Displays the first few rows of the dataset.
-Visualizes the data using a scatter plot to identify potential clusters.

-Calculates the Within-Cluster Sum of Squares (WCSS) to determine the optimal number of clusters.
-Applies the K-Means algorithm to cluster the data into 4 groups.


-Plots the clusters with distinct colors for better visual differentiation.


###### How to Run

-Ensure all dependencies are installed.

-Place the student_clustering.csv file in the same directory as the script.

Run the script to see the clustering results and visualizations.

