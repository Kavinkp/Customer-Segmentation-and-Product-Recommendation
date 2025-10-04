# Customer-Segmentation-and-Product-Recommendation

## Overview
This project focuses on **customer segmentation and product recommendation** using transaction data.  
The goal is to understand customer behavior, identify meaningful groups (clusters), and recommend relevant products for each segment.

## Objectives
- Segment customers based on their purchasing behavior.  
- Identify high-value customer groups.  
- Recommend products tailored to each segment.  
- Visualize missing values, anomalies, and trends in the dataset.  

## Tech Stack
- **Python**  
- **Jupyter Notebook**  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Yellowbrick, Plotly  

## Dataset
- The dataset contains transaction-level details such as:
  - InvoiceNo – Transaction ID  
  - CustomerID – Unique customer identifier  
  - StockCode – Product code  
  - Quantity, UnitPrice – Purchase details  
  - Transaction_Status – Marked as Completed or Cancelled  


## Key Steps
1. **Data Cleaning**
   - Removed duplicates  
   - Handled missing values  
   - Dropped anomalous stock codes  
   - Added Transaction_Status column  

2. **Exploratory Data Analysis (EDA)**
   - Distribution of sales, top products, top customers  
   - Missing value analysis with bar charts  
   - Cancelled vs completed transaction analysis  

3. **Customer Segmentation**
   - Used **KMeans clustering**  
   - Determined optimal clusters via **Elbow Method** and **Silhouette Score**  
   - Principal Component Analysis (PCA) for dimensionality reduction  

4. **Product Recommendation**
   - Identified popular products within each segment  
   - Generated segment-based recommendations  

## Visualizations
- Missing value percentages (barh chart)  
- Elbow plot and silhouette scores (via Yellowbrick)  
- Cluster visualizations (2D PCA plots)  
- Product recommendation heatmaps  

## Results
- Customers were segmented into distinct clusters (e.g., high-value, discount-seeking, occasional buyers).  
- Each cluster was mapped to its preferred products, enabling targeted recommendations.  

