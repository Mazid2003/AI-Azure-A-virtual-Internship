**🗓 Day - 8 : Classification Models & Evaluation Metrics🚀**

Date:27/05/2025

**🧠 Classification Models**

![WhatsApp Image 2025-05-27 at 10 44 05 PM](https://github.com/user-attachments/assets/c0a29712-3c0f-489d-ba8d-8c078a4170f8)

Classification models are supervised machine learning algorithms that predict discrete class labels (e.g., yes/no, spam/ham, positive/negative). These are widely used in fields like medical diagnosis, fraud detection, and sentiment analysis.

**1. 🔹 Logistic Regression**

![WhatsApp Image 2025-05-27 at 10 44 07 PM (1)](https://github.com/user-attachments/assets/62e21f45-e7cd-41e0-b1f0-b2d296b06864)

Purpose: Predicts the probability that a given input belongs to a particular category.

Despite its name, it's used for classification, not regression.

Uses the sigmoid function to map any real-valued number into a probability between 0 and 1.

**Equation:**

P(Y = 1 | X) = 1 / (1 + e^-(β0 + β1*X1 + β2*X2 + ... + βn*Xn))

**Explanation:**

P(Y = 1 | X) → Probability that the output is class 1 given input features X

β0 → Intercept (bias term)

β1, β2, ..., βn → Coefficients for features X1, X2, ..., Xn

e → Euler's number (≈ 2.718)
 
**Pros:**

Simple and fast

Interpretable coefficients

**Use Case:**

Email spam detection

Disease classification (yes/no)

**2. 🔹 K-Nearest Neighbors (KNN)**

![WhatsApp Image 2025-05-27 at 10 44 07 PM](https://github.com/user-attachments/assets/55765ca8-6d26-4454-b4b7-b7b226375e8e)

Purpose: Classifies a data point based on the majority class of its K nearest neighbors.

**Working:**

Store all data during training

For a new point, find the K closest training samples using distance metrics (e.g., Euclidean distance)

Assign the majority class among them

**Pros:**

Simple and intuitive

No training phase (lazy learner)

**Cons:**

Slow with large datasets

Sensitive to noisy data and irrelevant features

**3. 🔹 Decision Tree**

![WhatsApp Image 2025-05-27 at 10 44 06 PM (1)](https://github.com/user-attachments/assets/8d01795a-78bd-4503-86eb-98f7fea94230)

Purpose: Uses a tree structure to make decisions based on features.

**How it works:**

Split the dataset using the best feature (based on Gini Impurity or Information Gain)

Repeat recursively to form a tree

**Pros:**

Easy to visualize and interpret

Handles both numerical and categorical data

**Cons:**

Can overfit if not pruned

Unstable with small data changes

**4. 🔹 Random Forest**

![WhatsApp Image 2025-05-27 at 10 44 06 PM](https://github.com/user-attachments/assets/d02932a1-443d-4355-8045-bfc5eccb5a6f)

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

![WhatsApp Image 2025-05-27 at 10 44 05 PM (1)](https://github.com/user-attachments/assets/654f5569-7dc1-4276-b22b-bf4ec01c3a7e)

**📊 Classification Metrics**
   
| Metric                   | Description                                                |
| ------------------------ | ---------------------------------------------------------- |
| **Accuracy**             | Total Predictions/Correct Predictions(TP+TN/TP+TN+FP+FN)   |                  
| **Precision**            | TP/TP+FP– How many predicted positives were correct        |
| **Recall (Sensitivity)** | TP/TP + FN – How many actual positives were caught         |
| **F1 Score**             | 2.P.R/P + R – Harmonic mean of Precision and Recall        |
| **Confusion Matrix**     | Table showing TP, TN, FP, FN counts                        |
| **ROC-AUC Score**        | Measures performance across all classification thresholds  |


**📉 Regression Metrics (for context)**
| Metric                             | Description                                              |
| ---------------------------------- | -------------------------------------------------------- |
| **MAE (Mean Absolute Error)**      | Average absolute difference between predicted and actual |
| **MSE (Mean Squared Error)**       | Average squared difference (penalizes larger errors)     |
| **RMSE (Root Mean Squared Error)** | Square root of MSE                                       |
| **R² Score**                       | Proportion of variance explained by the model            |
