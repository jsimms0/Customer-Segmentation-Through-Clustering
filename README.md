# Customer Segmentation Through Clustering
Customer segmentation through unsupervised clustering to create, analyze, and profile five distinct customer segments.

#### Project Overview
This project aims to segment customers of a grocery company into distinct groups using unsupervised machine learning techniques. This type of analysis helps to improve business performance by determining paths to best refine product offerings, create targeted marketing strategies, perform informed customer outreach, and improve overall customer engagement. 

#### Goals
1. Analyze overall customer statistics.
2. Segment the grocery company's customer base into distinct groups.
3. Reduce the dimensionality of the dataset for more efficient clustering.
4. Analyze the patterns within clusters to inform marketing and product strategies.

#### Data Overview
The dataset comprises 2,240 records, which were reduced to 2,216 after cleaning for missing values. It contains a total of 29 attributes that fall under four major categories: Customer Information (e.g., ID, Year_Birth), Products (e.g., Wines, Fruits), Promotion (e.g., NumDealsPurchases), and Place (e.g., NumWebPurchases). Features also include customer income, family size, and responses to previous marketing campaigns.

#### Key Steps
1. **Data Cleaning & Feature Engineering**:
   - Parse date features and calculate customer age.
   - Engineer new features such as 'Spent,' 'Living_With,' and 'Is_Parent.'
   - Drop redundant features like 'Dt_Customer' and 'ID.'
  
2. **Data Preprocessing**:
   - Standardize the dataset.
   - Label-encode categorical variables.
   - Apply scaling techniques, specifically Standard Scaler.

3. **Dimensionality Reduction**:
   - Utilize Principal Component Analysis (PCA) for reducing data complexity.

4. **Data Visualization & Cluster Analysis**:
   - Generate correlation matrices, pairplot analyses, and other visualizations to understand feature interactions and cluster patterns.

5. **Clustering & Profiling**:
   - Apply Agglomerative Clustering to segment the reduced dataset.
   - Characterize each cluster based on original features to inform actionable strategies.

#### Results
1. A total of five clusters were identified as optimal, contrasting an earlier finding of four clusters.
2. Clusters exhibit a well-distributed range, with Cluster 0 being the most frequent and Cluster 4 the least.
3. Specific characteristics like family structure, spending habits, and income levels were profiled for each cluster.
4. Varied spending patterns across clusters indicate opportunities for targeted marketing.
5. Current marketing campaigns were found to be largely ineffective, but deals have shown strong performance, particularly among high-spending groups.

#### Conclusions
1. High-spend clusters (Clusters 1 and 4) are more receptive to deals and should be the focus of additional targeted campaigns.
2. Cluster 0 is primarily composed of parents and represents a low-spend group, offering a potential area for specialized marketing.
3. There is a clear need for the redesign of current campaigns, particularly to increase efficacy for specific clusters.
4. The segmentation provides actionable insights for crafting tailored marketing strategies and refining product offerings.

