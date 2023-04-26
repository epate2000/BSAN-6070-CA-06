# BSAN-6070-CA-06

Customer Segmentation Clustering

The goal of this assignment is to use K-Means clustering to help malls gather data on the spending habits based on income for different customers. This way, they can fine tune their prices, promotions, and products to fit different demographics. 

The dataset is provided in this link: https://github.com/ArinB/MSBA-CA-Data/raw/main/CA06/Mall_Customers.csv

The dataset contains the following features:

CustomerID: Unique ID for each customer
Gender: Male or Female
Age: Age of the customer
Annual Income (k$): Annual income of the customer in thousands of dollars
Spending Score (1-100): A score assigned by the mall based on customer behavior and spending nature (higher scores indicate higher spending)
This program looks to achieve five overall tasks: Load the dataset and perform exploratory data analysis (EDA), Prepare the data for clustering, Implement k-means clustering, Visualize and analyze the clusters, Write a report summarizing your findings


The assignment entails importing several different libraries and algorithms, and other techniques

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.preprocessing import StandardScaler
from sklearn.cluster import KMeans
from sklearn.metrics import silhouette_score

Once the clusters for each kind of customer is created via K-Means clustering, analyses can thus be made.
