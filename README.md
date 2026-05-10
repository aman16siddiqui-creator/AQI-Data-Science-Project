**Project Title:** AQI-Data-Science-Project

**Student Name:** Aman Siddiqui

**Registration Number:** 2280104

**Dataset Name:** Global Urban Air Quality Index Dataset (2015–2025) 

**Problem Statement:**

Air pollution is a critical global health issue. This project aims to:

• Analyze global AQI data to identify pollution patterns across cities and countries

• Classify air quality into meaningful categories (Good to Hazardous) using KNN and Naive Bayes

• Discover natural pollution groupings using K-Means clustering

• Visualize high-dimensional pollution data using PCA

**Tools and Libraries Used:**

• pandas 

• numpy

• matplotlib 

• seaborn  

• sklearn.model_selection 

• sklearn.preprocessing 

• sklearn.neighbors

• sklearn.naive_bayes

• sklearn.metrics 

• sklearn.cluster 

• sklearn.decomposition 

**How to Run the Notebook:**

• Open Google Colab 

• Upload the dataset file

• Open `AQI_Data_Science_Project.ipynb`

• Run all cells in order

• Ensure all outputs and charts are visible

**Summary of Main Findings:**

**AQI Distribution:** "Very Unhealthy" was the most common category; the distribution was nearly uniform.

**Country Rankings:** India had the highest average AQI (~168); all countries were closely clustered (160–168).

**No Meaningful Correlations:** All feature-to-AQI correlations were near zero, confirmed by the heatmap.

**KNN Performance:** Best accuracy of ~25% at k=7 — poor due to lack of real feature-AQI relationships.

**Naive Bayes Performance:** Better at 38.66%, benefiting from the data's independent feature behavior.

**K-Means:** Identified 3 meaningful pollution clusters (low/medium/high).

**PCA:** Explained only 21.4% variance — expected for synthetic, uncorrelated data.

Screenshots of Important Charts

Report File Location


Report File
