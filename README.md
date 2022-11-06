# Module_10_Challenge
Financial Python programming with unsupervised learning...
In this Challenge, the financial Python programming with unsupervised learning skills were combined to deliver and arrive at the conclusion.

The CSV file provided for this challenge contains price change data of cryptocurrencies in different periods. The steps for this challenge are broken out into the following sections:

    Import the Data (provided in the starter code)
    Prepare the Data (provided in the starter code)
    Find the Best Value for k Using the Original Data
    Cluster Cryptocurrencies with K-means Using the Original Data
    Optimize Clusters with Principal Component Analysis
    Find the Best Value for k Using the PCA Data
    Cluster the Cryptocurrencies with K-means Using the PCA Data
    Visualize and Compare the Results

The following libraries and dependencies were imported, with the visualization plots providing effective support to understand and appreciating the final outcome.
import pandas as pd
import hvplot.pandas
from pathlib import Path
import numpy as np
import matplotlib.pyplot as plt
from scipy.spatial.distance import cdist
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler
from sklearn.datasets import make_blobs
import plotly.express as px

The optimal number of clusters were arrived at - we used the K-Means algorithm with the best value for k( K-Means model) &  also perform a principal component analysis (PCA)  to reduce the features to three principal components. In order words, Clusters were Optimized with Principal Component Analysis.The total explained variance of the three principal components were  calculated and explained. The Cluster Cryptocurrencies with K-means Using the PCA Data were performed.

Finally, visually analyzed the cluster results by contrasting the outcome with and without using the optimization techniques.
