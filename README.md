**Cryptocurrency unsupervised machine learning project**

This project focuses on clustering cryptocurrencies using unsupervised learning techniques, specifically K-Means clustering combined with Principal Component Analysis (PCA) for dimensionality reduction. The goal was to group cryptocurrencies based on their 24-hour and 7-day price change percentages, allowing for better market trend analysis.

I began by standardizing the data to ensure consistency, followed by applying PCA to reduce the number of features while retaining the most significant variance. Using the Elbow Method, I determined the optimal number of clusters before running K-Means on both the raw and PCA-transformed datasets.

To enhance readability, I color-coded clusters, making differentiation clearer in scatter plots. Additionally, we created composite plots, overlaying Elbow curves and cluster visuals before and after PCA, helping to assess the impact of dimensionality reduction on clustering results. Throughout the process, we fine-tuned visualization settings, adjusting line styles, transparency, and text formatting to improve clarity. The results showed that PCA helped refine cluster separation, making the groupings more distinct and meaningful.
