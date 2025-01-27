# Customer Analytics and Clustering Project
## Overview
This project focuses on analyzing customer data to derive insights, build a lookalike model, and perform customer segmentation using clustering techniques. The tasks are designed to enhance business decision-making and improve customer targeting.

## Project Structure
### Task 1: Exploratory Data Analysis (EDA) and Business Insights
Objective: Explore the dataset and derive meaningful business insights.
Deliverables:
Jupyter Notebook/Python script with EDA code.
PDF report summarizing five key business insights.
### Task 2: Lookalike Model
Objective: Build a lookalike model to recommend three similar customers for each of the first 20 customers (C0001–C0020).
**Approach:**
Utilize both customer profile and transaction data.
Assign similarity scores to recommendations.
**Deliverables:**
Jupyter Notebook/Python script for model development.
CSV file (Lookalike.csv) with mappings: <CustomerID, [(SimilarCustomerID, Score), ...]>.
### Task 3: Customer Segmentation / Clustering
Objective: Perform clustering to segment customers based on profile and transaction data.
**Approach:**
Experiment with clustering algorithms (e.g., K-Means, DBSCAN).
Calculate metrics like Davies-Bouldin Index (DB Index).
Visualize clusters.
**Deliverables:**
Jupyter Notebook/Python script for clustering.
Report on clustering results (clusters, DB Index, metrics, visualizations).
Files
## Notebooks/Scripts:
**1. EDA.ipynb:** Contains EDA and business insights code. 

**2. Lookalike_Model.ipynb:** Implements the lookalike model. 

**3. Clustering.ipynb:** Contains clustering code and visualizations. 

**Reports:** 

**1. Business_Insights.pdf:** EDA insights report. 

**2. Clustering_Report.pdf:** Clustering results and analysis. 

**Output:** 

Lookalike.csv: Lookalike model results.
## How to Run 
### Clone the repository:
```git clone https://github.com/Shivi4590/DataScienceAssignment.git```
```cd customer-analytics```

### Install required libraries
```pip install -r requirements.txt```

### Run Jupyter Notebooks for each task:
```jupyter notebook```

## Key Metrics
1. EDA: Insights derived from visualizations and statistical analysis. 

2. Lookalike Model: Recommendations with similarity scores for customer targeting. 

3. Clustering: Segmentation using Davies-Bouldin Index and visualizations. 

## Results
I. EDA Insights: Business insights based on customer and transaction data. 

II. Lookalike Model: Top 3 similar customers for the first 20 customers. 

III. Clustering: Optimal clusters formed with evaluation metrics. 
## License

This project is licensed under the [MIT License](LICENSE).

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)



