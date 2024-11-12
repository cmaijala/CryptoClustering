
![kanchanara-dVAW3YDHtSw-unsplash](https://github.com/user-attachments/assets/1ae1f649-dc06-46a5-9fd2-93a494e865a0)

Photo by <a href="https://unsplash.com/@kanchanara?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Kanchanara</a> on <a href="https://unsplash.com/photos/person-using-black-laptop-computer-dVAW3YDHtSw?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
      

# CryptoClustering
### University of Minnesota Crypto Clustering Challenge Module 19



# Crypto Clustering Analysis

In this project, I applied Python and unsupervised learning techniques to cluster cryptocurrencies based on their 24-hour and 7-day price changes.

## Steps:

1. **Data Loading & Initial Analysis**:  
   I loaded the `crypto_market_data.csv` into a DataFrame, generated summary statistics, and visualized the data.

2. **Data Preparation**:  
   I scaled the data using `StandardScaler` and created a new DataFrame with normalized data, setting the "coin_id" as the index.

3. **K-means Clustering (Original Data)**:  
   I applied the elbow method to determine the optimal number of clusters (k) for the data and performed K-means clustering using the identified k value.

4. **PCA for Dimensionality Reduction**:  
   I reduced the data to three principal components using PCA and analyzed the explained variance of the components.

5. **K-means Clustering (PCA Data)**:  
   I repeated the elbow method and K-means clustering on the PCA-reduced data, compared the results to the original data, and visualized the clusters.

## Key Insights:
- The best k value was determined both for the original scaled data and the PCA-reduced data.
- The clustering results were visualized using scatter plots with color-coded clusters and interactive hover features.

### Questions Answered:
- What is the best value for k?
- What is the total explained variance of the principal components?
- What impact does using fewer features in K-means clustering have?

This project demonstrates how unsupervised learning can be applied to cryptocurrency data to uncover patterns in price change behaviors.

## References:
- OpenAI. *ChatGPT*. Retrieved from https://chat.openai.com. Assistance provided in the development of clustering techniques and PCA analysis.
- Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.
 
