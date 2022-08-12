# Unsupervised-Learning-Challenge
This repository shows my skills on unsupervised machine learning.


## Myopia Clusters

In this assignment, I applied unsupervised learning by fitting data to a model and using clustering algorithms to place data into groups. I then created a visualization and presented my findings on distinct groups of patients that would be better to analyze separately.  This assignment comprised of four parts.

## Part 1: Prepare the Data
This step involves importing the CSV and reading it using Pandas dataframe.  As this assignment pertains to unsupervised machine learning, the target column "MYOPIC" was dropped in my dataframe to prevent bias.  The dataset was tested for null values and results showed that there are no null values in the dataset.  The dataset values are then standardized so that columns that contain larger values do not influence the outcome more than columns with smaller values. 

## Part 2: Apply Dimensionality Reduction
This step involves perform dimensionality reduction with PCA.  The **PCA results changed the number of features from 14 to 9**.  The dataset is further reduced with t-SNE and a scatter plot was created to visualize the t-SNE output.  The results showed that there are **distinct clusters**.

## Part 3: Perform a Cluster Analysis with K-means
This step involves creating an elbow plot to identify the best number of clusters.  Based on the elbow plot, the **value of K is 3**.
<br>
![image](https://user-images.githubusercontent.com/91984732/184450612-fb7049b8-708d-48f1-9381-213bd3351749.png)

The model was run at K value of 3 and plot was created to visualize the clusters.
<br>
![image](https://user-images.githubusercontent.com/91984732/184450853-4e8904fd-0cd0-4732-99c8-f55b3d551a0d.png)
<br>
![image](https://user-images.githubusercontent.com/91984732/184451304-5014950b-8a76-4e8e-b7ae-4c133758eeb7.png)


## Part 4: Make a Recommendation
Based on the machine learning results, there are **three distinct groups or clusters of patients** that would be better to analyze separately. <br> The elbow plot showed a **K value of 3**.




