# Mall_Customers_Segmentation

The goal of this project is simply to understand customers and separate them into different groups according to their preferences often known as market segmentation.

## Description

We have some basic data about the mall customers like Customer ID, age, gender, annual income, and spending score. In this case, the Marketing team wants to identify some patterns in these data and to groups of customers accordingly.

## Output of the project
In this project, we want to identify customers' preferences by their annual income and spending score. And to separate them into different groups we use clustering with K-Means algorithm. After cleaning the dataset, we find the optimal number of clusters is between 4 and 6 therefore we are selecting 5 as the number of clusters to divide our dataset.

The following graph shows the optimal number of clusters:

![Unknown-3](https://user-images.githubusercontent.com/86167177/129039154-be20bbf8-ed8a-43ec-9734-806bd83e6857.jpg)

After the K-Means algorithm finished its work, we plot the results as seen down below:

![Unknown-4](https://user-images.githubusercontent.com/86167177/129041772-879cbdb2-602e-4b1d-8aed-a6d785003a21.jpg)

From the results above, we can identify the groups as:
- Cluster 1 : Groups of people whose salary isn't pretty high yet have a high spending score.
- Cluster 2 : Groups of people whose salary and spending score are moderate
- Cluster 3 : Groups of people whose salary is high and spend a lot in the mall
- Cluster 4 : Groups of people whose salary isn't pretty high and not spending much in the mall
- CLuster 5 : Groups of people whose salary is high yet have a low spending score

Using the info, the Marketing team can make better approaches to each group of customers, run target advertisements to reach more sales, and make more strategic decisions to increase profits.



















