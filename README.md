Association Rule Mining (Apriori Algorithm)

Dataset: Groceries Dataset

Description:
     
The Groceries dataset consists of transactional records with attributes such as Member_number, Date, and itemDescription, representing items purchased in each shopping visit. In this experiment, the data is preprocessed by grouping transactions using Member_number and Date to form unique baskets. A manual implementation of the Apriori algorithm is applied to generate frequent itemsets by calculating support for item combinations and filtering them using a minimum support threshold. Association rules are then derived by computing confidence and lift, ensuring only strong relationships are retained. The output shows 586 frequent itemsets and 267 association rules, indicating meaningful purchasing patterns. For example, the rule (UHT-milk → other vegetables) has a confidence of approximately 49% and lift greater than 1, showing a positive association. Visualizations such as bar charts, scatter plots, and network graphs are used to interpret item frequency and relationships, making the results useful for market basket analysis and recommendation systems.

Dimensionality Reduction (PCA)

Dataset: Iris Dataset

Description:
      
The Iris dataset contains numerical features including Sepal Length, Sepal Width, Petal Length, and Petal Width, used for demonstrating dimensionality reduction through Principal Component Analysis (PCA). The dataset is first preprocessed to handle missing and inconsistent values, after which PCA is applied to transform the original features into a smaller set of uncorrelated principal components. The explained variance ratio is calculated as [0.72, 0.23, 0.03, 0.008], indicating that the first two components capture approximately 95% of the total variance. Based on this, the optimal number of components is selected as 2, reducing the dataset from (150, 4) to (150, 2) while preserving most of the information. This dimensionality reduction simplifies the dataset, improves computational efficiency, and removes redundancy, making it more suitable for further analysis and modeling.


# 24ADI003_24BAD022_EXP-08
