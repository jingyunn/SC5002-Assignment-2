# SC5002-Assignment-2

In this project, we aim to explore and analyze two machine learning techniques: Classification and Clustering, using real-world datasets. We are working with the Mushrooms dataset from a CSV file, which contains labeled data regarding various features of mushrooms, such as cap shape, cap color, stalk root, odor, etc. The main goal is to understand the strengths and weaknesses of both techniques and improve their performance through methods like Cross-validation.

# Dataset
We have selected the Mushrooms dataset, which consists of labeled and unlabeled features. The dataset contains the following columns:

Class: The target variable, indicating whether the mushroom is poisonous (p) or edible (e).

Cap-shape, Cap-surface, Cap-color, etc.: These columns describe different features of mushrooms. All features are categorical, which makes it a good choice for classification and clustering problems.

Dataset Preview: Each row in the dataset represents a mushroom with attributes like cap shape, cap color, gill attachment, etc., and the target variable class (either 'p' for poisonous or 'e' for edible).

# Steps Taken in the Project
1) Dataset Selection:
   
We chose the Mushrooms dataset, which contains both labeled and unlabeled features, making it suitable for both classification (predicting whether a mushroom is edible or poisonous) and clustering (grouping similar mushrooms based on their attributes).

2) Data Preprocessing:
   
- Handling Missing Values: We examined the dataset for any missing or incomplete values and handled them appropriately (e.g., replacing with mean, mode, or dropping rows).
- Data Splitting: The dataset was split into training and testing sets for model evaluation. This ensures that we test the performance of our models on unseen data.

3) Model Training and Evaluation:
   
- Classification Model: We trained a classification model (e.g., Decision Trees or Logistic Regression) to predict whether the mushroom is poisonous or edible based on the features. We evaluated its performance using metrics such as accuracy.
- Clustering (K-Means): We applied the K-Means clustering algorithm with varying values of k (number of clusters) to group mushrooms into clusters based on their features. We compared the results for different k values.
- Cross-Validation: We implemented k-fold cross-validation for both models to get a more reliable estimate of their performance.

4) Analysis and Comparison:
   
- We compared the performance of the classification model with the clustering model using the Accuracy Score.
- We analyzed the effect of different initial centroids in K-Means clustering on the accuracy of the clusters.
- We discussed the limitations of the classification model, such as potential overfitting, sensitivity to data imbalances, etc.

5) Improving Model Performance:
   
- We experimented with different values of k for the K-Means algorithm to see how clustering accuracy changes with the number of clusters.
- We discussed potential improvements, such as feature scaling, using more advanced algorithms, or tuning hyperparameters for better performance.

# Insights
- Classification Insights: The classification model performed well in predicting the type of mushroom (poisonous or edible) based on the features. The model was sensitive to the quality and quantity of the features provided, and we observed how overfitting could occur if we did not perform proper cross-validation.

- Clustering Insights: The K-Means clustering algorithm showed that grouping mushrooms based on their features could be effective, but it was sensitive to the initial placement of centroids. We observed how different values of k affected the grouping of mushrooms, and how a higher k may not necessarily lead to better clustering.

- Cross-Validation Insights: Using cross-validation helped in obtaining a more generalized estimate of the model's performance, ensuring that we avoided overfitting the training data.

- Comparison of Models: We observed that classification models were better suited for predicting the target variable, while clustering was more useful for grouping similar mushrooms, especially in cases where labels were unknown.

# Conclusion
This project helped in understanding how classification and clustering models can be used to solve real-world problems. It also highlighted the importance of techniques like cross-validation and tuning the parameters of algorithms (e.g., the number of clusters in K-Means). The insights gained from this analysis can help us apply these models in various practical applications such as mushroom classification for safety or feature-based clustering for similar group identification.

# Contributions
1) Jack was responsible for dataset selection, data preprocessing, model training and evaluation.
2) Jing Yun was responsible for analysis and comparison, editing videos and readme file.
3) Min Han was responsible for improving model performance.   
