# Social Media Engagement Analysis

## Overview

This repository contains a comprehensive analysis of social media engagement data. The analysis focuses on understanding how different types of user interactions (e.g., reactions, comments, shares) vary across social media posts and identifying patterns using clustering techniques. The primary goal is to provide insights that can help optimize content strategies for better engagement.

## Files in this Repository

### 1. IS&Digital Innovation 2024.ipynb
- **Description**: This Jupyter Notebook contains the full analysis of the social media engagement data. It includes data cleaning, feature selection, standardization, clustering using K-Means, and visualization of the results.
- **Key Sections**:
  - **Data Import and Cleaning**: Loading the dataset and handling missing values.
  - **Exploratory Data Analysis (EDA)**: Initial exploration of the data to understand its structure and main characteristics.
  - **Feature Selection**: Choosing relevant features for clustering.
  - **Clustering**: Applying K-Means clustering to identify patterns in user interactions.
  - **Visualization**: Using PCA to reduce dimensions and visualize clusters.
  - **Evaluation**: Calculating silhouette scores and using the elbow method to determine the optimal number of clusters.

### 2. Live.csv
- **Description**: This CSV file contains the raw social media engagement data used in the analysis. The dataset includes various metrics such as the number of reactions, comments, shares, likes, loves, wows, hahas, sads, and angrys for different social media posts.
- **Columns**:
  - status_id: Unique identifier for each post.
  - status_type: Type of post (e.g., video, photo).
  - status_published: Timestamp when the post was published.
  - num_reactions: Total number of reactions.
  - num_comments: Number of comments.
  - num_shares: Number of shares.
  - num_likes: Number of likes.
  - num_loves: Number of loves.
  - num_wows: Number of wows.
  - num_hahas: Number of hahas.
  - num_sads: Number of sads.
  - num_angrys: Number of angrys.
  - Additional columns that were dropped during data cleaning due to having null values.

## How to Use

1. **Clone the Repository**: git clone https://github.com/vir3132/Data-Sci.git
2. 2. **Install Dependencies**:
- Ensure you have Python and Jupyter Notebook installed.
- Install the required libraries by running:
  ```
  pip install numpy pandas matplotlib seaborn scikit-learn
  ```

3. **Run the Notebook**:
- Open the Jupyter Notebook:
  ```
  jupyter notebook IS&Digital Innovation 2024.ipynb
  ```
- Follow the steps in the notebook to reproduce the analysis.

## Insights and Strategic Application

The analysis provides actionable insights into how different types of content perform in terms of user engagement. 
By understanding these patterns, social media managers can tailor their content strategies to maximize engagement and achieve specific goals such as increasing visibility, 
fostering community interaction, or building emotional connections with the audience.

