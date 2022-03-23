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
<img width="900" alt="SpendingScore_Histogram" src="https://user-images.githubusercontent.com/41455772/159688101-42511740-4528-45a8-bf1c-93ca36715a6a.png">
<img width="892" alt="Income_Gender" src="https://user-images.githubusercontent.com/41455772/159688109-2a942a8f-90c6-4542-ba03-489b97b815fb.png">
<img width="914" alt="SpendingScore_Gender" src="https://user-images.githubusercontent.com/41455772/159688115-bcca9496-b0fa-4f88-ab38-83a7148dbd69.png">
l<img width="940" alt="Age_DensityPlot" src="https://user-images.githubusercontent.com/41455772/159688065-7a9ae1a7-4069-4be3-a80a-fa2545ef2e62.png">
<img width="935" alt="Income_DensityPlot" src="https://user-images.githubusercontent.com/41455772/159688083-528c2d97-0ca9-4c8a-b26d-011d62e19bc1.png">

## Customer Segmentation
The purpose of customer segmentation is to divide the customers based on thier age, income and spending score using an unsupervised machine learning algorithm called k-Means Clustering. To find the optimal number of clusters, the elbow method has been used. 

The results of clustering are as follows:
![Age SpendingScore](https://user-images.githubusercontent.com/41455772/159687782-81c67c76-0077-4eb9-a38b-eb5915b8c14c.png)

![AnnualIncome SpendingScore](https://user-images.githubusercontent.com/41455772/159687808-8221ff15-8a4b-4e5e-85f1-fd0d0edd1c34.png)

![3dcluster](https://user-images.githubusercontent.com/41455772/159687835-907042b6-f670-4e37-b6ce-e7ae8b8f1c81.png)

