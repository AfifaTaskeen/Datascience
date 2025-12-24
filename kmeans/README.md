# K-Means Clustering – Customer Segmentation

## Project Overview
This project demonstrates the application of the K-Means clustering algorithm to segment mall customers into distinct groups based on their annual income and spending behavior. The objective is to identify meaningful customer segments that can help businesses understand customer patterns and improve targeted marketing strategies.

## Dataset
- **Name:** Mall Customer Segmentation Dataset
- **Source:** Kaggle
- **Number of Records:** 200
- **Features Used:**
  - Age
  - Annual Income (k$)
  - Spending Score (1–100)

## Tools and Technologies
- **Programming Language:** Python
- **Platform:** Google Colab
- **Libraries Used:**
  - pandas
  - scikit-learn
  - matplotlib

## Methodology
1. The dataset was uploaded and loaded into Google Colab.
2. Relevant numerical features were selected for clustering.
3. Feature scaling was applied using StandardScaler to normalize the data.
4. K-Means clustering was implemented to group customers into clusters.
5. The Elbow Method was used to determine the optimal number of clusters.
6. Clusters were visualized and analyzed to interpret customer behavior.

## Results
The customers were successfully grouped into **five distinct clusters**, each representing a different type of customer segment based on income and spending patterns. These clusters provide valuable insights into customer behavior and purchasing capacity.

## Files in This Folder
- `Mall_Customers.csv` – Original dataset
- `Mall_Customers_Clustered.csv` – Dataset with assigned cluster labels
- `Untitled15.ipynb` – Google Colab notebook containing the implementation
- `README.md` – Project documentation

## Conclusion
The K-Means clustering algorithm proved effective in segmenting customers into meaningful groups. Such segmentation can support data-driven decision-making and help businesses design personalized marketing strategies.

## Author
Afifa Taskeen
