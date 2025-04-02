# SC5002-Assignment-2

In this project, we aim to explore and analyze two machine learning techniques: Classification and Clustering, using real-world datasets. We are working with the Mushrooms dataset from a CSV file, which contains labeled data regarding various features of mushrooms, such as cap shape, cap color, stalk root, odor, etc. The main goal is to understand the strengths and weaknesses of both techniques and improve their performance through methods like Cross-validation.

# Dataset
Class: The mushroom is classified as either edible (denoted by "e") or poisonous (denoted by "p").

Cap-related Features:

Cap shape: The cap can be bell-shaped (b), conical (c), convex (x), flat (f), knobbed (k), or sunken (s).

Cap surface: The surface of the cap can be fibrous (f), grooved (g), scaly (y), or smooth (s).

Cap color: The cap can be brown (n), buff (b), cinnamon (c), gray (g), green (r), pink (p), purple (u), red (e), white (w), or yellow (y).

Gill-related Features:

Gill attachment: The gills may be attached (a), descending (d), free (f), or notched (n).

Gill spacing: The gills can be close (c), crowded (w), or distant (d).

Gill size: The gills can be either broad (b) or narrow (n).

Gill color: The gills may be black (k), brown (n), buff (b), chocolate (h), gray (g), green (r), orange (o), pink (p), purple (u), red (e), white (w), or yellow (y).

Stalk-related Features:

Stalk shape: The stalk can be enlarging (e) or tapering (t).

Stalk root: The stalk root can be bulbous (b), club-shaped (c), cup-shaped (u), equal (e), rhizomorphs (z), rooted (r).

Stalk surface above the ring: The surface above the ring can be fibrous (f), scaly (y), silky (k), or smooth (s).

Stalk surface below the ring: The surface below the ring can be fibrous (f), scaly (y), silky (k), or smooth (s).

Stalk color above the ring: The color above the ring can be brown (n), buff (b), cinnamon (c), gray (g), orange (o), pink (p), red (e), white (w), or yellow (y).

Stalk color below the ring: The color below the ring can be brown (n), buff (b), cinnamon (c), gray (g), orange (o), pink (p), red (e), white (w), or yellow (y).

Veil-related Features:

Veil type: The veil can be partial (p) or universal (u).

Veil color: The color of the veil can be brown (n), orange (o), white (w), or yellow (y).

Ring number: The mushroom may have none (n), one (o), or two (t) rings.

Ring type: The ring type can be cobwebby (c), evanescent (e), flaring (f), large (l), none (n), pendant (p), sheathing (s), or zone (z).

Miscellaneous Features:

Bruises: The mushroom may have bruises (t) or no bruises (f).

Odor: The odor can be almond (a), anise (l), creosote (c), fishy (y), foul (f), musty (m), none (n), pungent (p), or spicy (s).

Spore print color: The spore print color can be black (k), brown (n), buff (b), chocolate (h), green (r), orange (o), purple (u), white (w), or yellow (y).

Population: The population may be abundant (a), clustered (c), numerous (n), scattered (s), several (v), or solitary (y).

Habitat: The habitat can be grasses (g), leaves (l), meadows (m), paths (p), urban areas (u), waste (w), or woods (d).

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
