**🗓 Day - 8 : Classification Models & Evaluation Metrics🚀**

Date:27/05/2025

**🧠 Classification Models**

Classification models are supervised machine learning algorithms that predict discrete class labels (e.g., yes/no, spam/ham, positive/negative). These are widely used in fields like medical diagnosis, fraud detection, and sentiment analysis.

**1. 🔹 Logistic Regression**

Purpose: Predicts the probability that a given input belongs to a particular category.

Despite its name, it's used for classification, not regression.

Uses the sigmoid function to map any real-valued number into a probability between 0 and 1.

**Equation:**
 
Pros:

Simple and fast

Interpretable coefficients

Use Case:

Email spam detection

Disease classification (yes/no)

**2. 🔹 K-Nearest Neighbors (KNN)**

Purpose: Classifies a data point based on the majority class of its K nearest neighbors.

**Working:**

Store all data during training

For a new point, find the K closest training samples using distance metrics (e.g., Euclidean distance)

Assign the majority class among them

Pros:

Simple and intuitive

No training phase (lazy learner)

Cons:

Slow with large datasets

Sensitive to noisy data and irrelevant features

**3. 🔹 Decision Tree**

Purpose: Uses a tree structure to make decisions based on features.

**How it works:**

Split the dataset using the best feature (based on Gini Impurity or Information Gain)

Repeat recursively to form a tree

Pros:

Easy to visualize and interpret

Handles both numerical and categorical data

Cons:

Can overfit if not pruned

Unstable with small data changes

**4. 🔹 Random Forest**

Purpose: An ensemble of decision trees that improves performance through bagging.

**How it works:**

Builds many decision trees on random subsets of data

Uses majority voting to decide the final class

Pros:

More accurate and robust than single trees

Handles overfitting better

Cons:

Less interpretable than a single tree

Computationally intensive

**📏 Evaluation Metrics**

📊 Classification Metrics
Metric	Description
Accuracy	
Correct Predictions
Total Predictions
Total Predictions
Correct Predictions
​
 
Precision	
TP
TP + FP
TP + FP
TP
​
  – How many predicted positives were correct
Recall (Sensitivity)	
TP
TP + FN
TP + FN
TP
​
  – How many actual positives were caught
F1 Score	Harmonic mean of Precision and Recall: 
2
⋅
𝑃
⋅
𝑅
𝑃
+
𝑅
P+R
2⋅P⋅R
​
 
Confusion Matrix	Table showing TP, TN, FP, FN counts
ROC-AUC Score	Measures performance across all classification thresholds

📉 Regression Metrics (for context)
Metric	Description
MAE (Mean Absolute Error)	Average absolute difference between predicted and actual
MSE (Mean Squared Error)	Average squared difference (penalizes larger errors)
RMSE (Root Mean Squared Error)	Square root of MSE
R² Score	Proportion of variance explained by the model
