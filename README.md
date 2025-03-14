# Product-Recommendation-System
This project focuses on building an Item-to-Item Recommendation System for a large-scale e-commerce dataset containing approximately 700,000 records. Various recommendation algorithms were explored, and after evaluation, the K-Nearest Neighbors (KNN) model was selected for deployment due to its high accuracy.

# Models Implemented
We experimented with the following recommendation techniques:

1.K-Nearest Neighbors (KNN) - Basic Model ✅ (Finalized for Deployment)

2.Cosine Similarity-Based Recommendation

3.Single Value Decomposition (SVD)

4.Alternating Least Squares (ALS)

After testing and evaluating all models, the KNN-based recommendation model was chosen for deployment as it provided the best balance of accuracy and efficiency.

# Deployment Details
The selected KNN model is deployed using Streamlit.
The application takes Product ID as input and returns the Top 5 recommended products based on item-to-item similarity.

# Application Screenshot
![image](https://github.com/user-attachments/assets/e98195ec-a324-41bd-9c99-c0c6f89896c3)
