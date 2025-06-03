**🗓 Day - 9 :Understanding of Unsupervised Learning and Clustering 🚀**


Date:29/05/2025
![WhatsApp Image 2025-05-29 at 10 09 15 PM (2)](https://github.com/user-attachments/assets/9b082d5e-1aec-475c-917d-badd356f6f3e)

Unsupervised Learning is a machine learning approach where the model is trained on unlabeled data.
The algorithm tries to discover patterns, groupings, or structure in the input data without being given explicit labels or outputs.

**Key Characteristics:**
No labeled outputs.

Goal is to explore data and find hidden structures.

Common tasks: Clustering, Dimensionality Reduction, Anomaly Detection.

![WhatsApp Image 2025-05-29 at 10 09 15 PM (1)](https://github.com/user-attachments/assets/80e1aefb-6cb4-4630-8829-2eb82377e57c)

**Supervised vs Unsupervised**

| Feature       | Supervised Learning        | Unsupervised Learning          |
| ------------- | -------------------------- | ------------------------------ |
| Data          | Labeled                    | Unlabeled                      |
| Output Known? | Yes                        | No                             |
| Goal          | Predict output             | Discover patterns or groupings |
| Examples      | Classification, Regression | Clustering, PCA                |


![WhatsApp Image 2025-05-29 at 10 09 17 PM (2)](https://github.com/user-attachments/assets/f06aeebb-a66d-4925-8796-db32bc17b123)

Clustering is the process of grouping a set of data points such that:

Points in the same group (cluster) are more similar to each other.

Points in different clusters are dissimilar.

It is a core task in unsupervised learning used to identify natural groupings in data.

![WhatsApp Image 2025-05-29 at 10 09 15 PM](https://github.com/user-attachments/assets/c370371f-a0a5-4caf-8cae-5bad84942c0f)
![WhatsApp Image 2025-05-29 at 10 09 16 PM (1)](https://github.com/user-attachments/assets/3c28fe2a-6ee5-445d-b939-2cc13c27c0d9)

![WhatsApp Image 2025-05-29 at 10 09 17 PM (1)](https://github.com/user-attachments/assets/fb7327bc-4b54-403d-b507-4ccdb631cc0d)

![WhatsApp Image 2025-05-29 at 10 09 17 PM](https://github.com/user-attachments/assets/47eb8e11-b3c2-46fc-a89e-bcbf1700effd)

**1. ✅ K-Means Clustering**
Partitioning algorithm that divides data into k clusters.

Works by minimizing the distance between data points and their cluster centroids.

Requires specifying k (number of clusters) in advance.

Fast and efficient, but sensitive to outliers and shape of data.

![WhatsApp Image 2025-05-29 at 10 09 16 PM (3)](https://github.com/user-attachments/assets/ca6cf077-ba01-414d-ae81-5b806835859b)

**2. 🧱 DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**
Clusters data based on density of points.

Groups together closely packed points and marks low-density points as noise/outliers.

Doesn’t require number of clusters beforehand.

Can find arbitrarily shaped clusters and handles noise well.

![WhatsApp Image 2025-05-29 at 10 09 16 PM (2)](https://github.com/user-attachments/assets/4abf7c0e-e381-43f1-aa8b-d49fc6acccb4)

**K-Means vs DBSCAN**
| Feature             | K-Means                | DBSCAN                         |
| ------------------- | ---------------------- | ------------------------------ |
| Clusters Shape      | Spherical              | Arbitrary                      |
| Need to specify `k` | Yes                    | No                             |
| Handles Outliers    | Poor                   | Very good                      |
| Based on Density    | No                     | Yes                            |
| Performance         | Fast on large datasets | Slower on large noisy datasets |

**3. 🌲 Hierarchical Clustering**

Builds a tree of clusters (dendrogram).

Two types:

Agglomerative: Bottom-up approach (merges clusters).

Divisive: Top-down approach (splits clusters).

No need to specify number of clusters initially.

Good for visualizing relationships among data points.

![WhatsApp Image 2025-05-29 at 10 09 19 PM (1)](https://github.com/user-attachments/assets/d1cc2e88-7bf5-4131-9750-7debac252c3c)
![WhatsApp Image 2025-05-29 at 10 09 19 PM](https://github.com/user-attachments/assets/e2839f66-feb6-471b-9ff8-e1be64635b60)

**💼 Applications of Clustering**

📦 Customer Segmentation in marketing.

🛒 Market Basket Analysis for recommending products.

📸 Image Compression by grouping similar pixel intensities.

🔍 Anomaly Detection in fraud and cybersecurity.

📚 Document Clustering for organizing news, research, or search results.

🎯 Personalized Recommendations in apps and platforms.

**Project**
![WhatsApp Image 2025-05-29 at 10 09 18 PM](https://github.com/user-attachments/assets/914d2d77-18d3-4cd9-98ab-6ac7a5ad83e6)

