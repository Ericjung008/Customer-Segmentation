# Customer Segmentation
This is a project assigned to me during [theDevMasters](https://www.thedevmasters.com) bootcamp.<br> 

## Introduction
Companies hope to retain regular customers and attract new customers. Loyalty programs, special offers, and price-focused advertising are a few marketing strategies companies apply to increase their customer base. However, different marketing strategies must be taken based on the customer's purchasing behavior. Random advertisement is not only costly but also causes a decrease in potential revenue due to a low response rate. With RFM analysis and clustering techniques, specific marketing strategies can be directed towards those who are interested.

## Objective
The objective of this project is to segment similiar customers into groups and highlight their characteristics by using two methods:
* RFM Segmentation
* KMeans Clustering

## Metric 
The Elbow Method was used as the evaluation metric for this project. The optimal number of clusters is chosen based on the elbow position.

<img width="447" alt="Screen Shot 2020-07-26 at 10 36 51 PM" src="https://user-images.githubusercontent.com/51253177/88507113-88779500-cf90-11ea-9ac6-015adbbfd38d.png">

## Approach
The following steps were taken to complete the project:
1. Import libraries and dataset.
2. Export dataset into SQL database.
3. Import dataset from SQL database.
4. Create an RFM table.
5. Group customers based on their segment scores.
6. Transform and normalize RFM table.
7. Find optimal number of clusters.
8. Create a min-max table.
9. Visualize clusters.
10. Label clusters.

## Technologies
Applications: Jupyter Notebook, MySQL<br>
Programming Language: Python 3.7.4<br>
Libraries: Numpy, Pandas, Sqlite3, Datetime, Scipy, Matplotlib, Seaborn, Plotly, Squarify, IPython, Scikit-learn <br>

## Project Files
[README](https://github.com/Ericjung008/Customer-Segmentation/blob/master/README.md)<br>
[Project](https://github.com/Ericjung008/Customer-Segmentation/blob/master/Customer%20Segmentation.ipynb)<br>
[SQL Database](https://github.com/Ericjung008/Customer-Segmentation/blob/master/segmentation.db)<br>
[Dataset](https://github.com/Ericjung008/Customer-Segmentation/blob/master/data.csv)<br>
