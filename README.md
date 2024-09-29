CryptoClustering: Predicting Cryptocurrency Clusters Based on 24-Hour and 7-Day Price Changes
Overview
In this project, you will apply your Python skills and unsupervised learning techniques to determine if cryptocurrencies are influenced by 24-hour or 7-day price changes. Specifically, you will use the K-means clustering algorithm and Principal Component Analysis (PCA) to group cryptocurrencies and explore the impact of reducing feature dimensions.

Repository Setup
Create a new GitHub repository named CryptoClustering.
Clone the repository to your local machine.
Push your code changes to GitHub regularly.
Instructions
Data Preparation
Load the crypto_market_data.csv into a pandas DataFrame.
Generate summary statistics and visualize the data.
Data Normalization
Use StandardScaler() from scikit-learn to normalize the data.
Create a new DataFrame with the scaled data and set the "coin_id" index.
K-Means Clustering on Scaled Data
Use the elbow method to find the optimal value for k (number of clusters).
Initialize and fit the K-means model using the scaled data.
Visualize the clusters with a scatter plot using hvPlot, with price_change_percentage_24h on the x-axis and price_change_percentage_7d on the y-axis.
Principal Component Analysis (PCA)
Perform PCA to reduce the dataset to 3 principal components.
Calculate and visualize the total explained variance for these components.
Use the elbow method to determine the best value for k using the PCA-transformed data.
Cluster the cryptocurrencies using K-means on the PCA data and visualize the results.
Visualization and Comparison
Create composite plots to compare the elbow curves and cluster results from the original scaled data and the PCA-transformed data.
Analyze and document the impact of reducing the number of features in clustering.
Final Deliverables
Elbow Curves: Visual comparison of inertia for different k values (with and without PCA).
Scatter Plots: Comparison of clusters formed using original features vs PCA-reduced features.
Conclusion: Discuss the effect of reducing features for clustering.
Coding Guidelines
Follow Python best practices (PEP8) for variable naming, DRY principles, and function structure.
Ensure your code is well-commented for readability.
Include detailed commit messages throughout the project.
Deployment
Push your final project to the CryptoClustering GitHub repository.
Submit the GitHub repository link as the final deliverable.
This challenge will help you practice unsupervised learning techniques and get a deeper understanding of clustering in real-world financial data.
