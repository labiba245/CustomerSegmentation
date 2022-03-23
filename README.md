# Customer Segmentation
## Objective
Customer segmentation is done to divide customers into different clusters so that a business can tailor their marketing campaigns for each different cluster. 
## Code and Resources Used

Python version: 3.8

Packages used: pandas, matplotlib, seaborn, dabl, sklearn

Data source: https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python

## Data

Then dataframe contains five columns:
- CustomerID
- Age
- Gender
- Annual Income (k$)
- Spending score (1-100)

Spending score is the score given to customers by the mall based on how much they spent in the mall. The more a customer spends, the higher his spending score.


## Exploratory Data Analysis
![Density Plot of Age](Age_DensityPlot.png)
![Density Plot of Income][Income_DensityPlot.png]
![Histogram of Spending Score][SpendingScore_Histogram.png]
![Income Distribution by gender][Income_Gender.png]
![Spending Score Distribution by gender][SpendingScore_Gender.png]

## Customer Segmentation
The purpose of customer segmentation is to divide the customers based on thier age, income and spending score using an unsupervised machine learning algorithm called k-Means Clustering. To find the optimal number of clusters, the elbow method has been used. 

The results of clustering are as follows:
![Age SpendingScore](https://user-images.githubusercontent.com/41455772/159687782-81c67c76-0077-4eb9-a38b-eb5915b8c14c.png)

![AnnualIncome SpendingScore](https://user-images.githubusercontent.com/41455772/159687808-8221ff15-8a4b-4e5e-85f1-fd0d0edd1c34.png)

![3dcluster](https://user-images.githubusercontent.com/41455772/159687835-907042b6-f670-4e37-b6ce-e7ae8b8f1c81.png)

