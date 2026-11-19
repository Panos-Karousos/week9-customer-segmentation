# week9-customer-segmentation
Week 9 - Customer Segmentation using Clustering

This is my Week 9 Data Science Fundamentals activity on customer segmentation using clustering.

I used the Wholesale Customers dataset from Kaggle, which contains spending information for 440 customers across six product categories. I used Python, pandas and matplotlib to explore the data, check for missing values and create graphs. I also standardised the spending data before applying the clustering methods.
I tested K-means with different K values and compared the results using the elbow method and silhouette scores. I also used hierarchical clustering with Ward linkage. K-means gave better results when comparing three clusters, with a silhouette score of 0.55 compared to 0.26 for hierarchical clustering.
I found that K=2 might be more useful for general customer segmentation, although K=3 identified two customers with unusually high spending who could be worth investigating separately.
To run the project, download the repository and open `data/week9_customer_segmentation.ipynb` in VS Code with Python and Jupyter. The required libraries are pandas, matplotlib, scikit-learn and scipy. The dataset is included in the data folder.
The full reflection is in `reflection.md`.
Dataset: https://www.kaggle.com/datasets/binovi/wholesale-customers-data-set