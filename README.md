Logistics Shipment Data Analysis

Project Overview
This project explores and analyzes a large-scale logistics shipment dataset containing over 263,000 shipment records.

The objective of this analysis is to clean the dataset, engineer useful features, and extract operational insights related to shipmemt value, cargo size, and destination port actvity.

Data Description
The dataset includes the following fields:
name - shipment or product identifier
price - shipment cost/value
weight - shipment weight
length - shipment length
width - shipmet width
height - shipment height
shipment date - date of shipment
destionation port - port receiving the shipment

Total records: 263,821 rows
Total columns - 8

Tools & Technologies Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

Data Preparation 
The following data cleaning steps were performed:
- Checked dataset shape and structure.
- Inspected missing values.
- Filled numerical missing values (weight, length) using median imputation.
- Removed rows with missing critical shipment information(shipment date, destination port).
- Engineered a new feature: shipemnt volume.

Key Analysis Performed
- Shipment count by destination port.
- Average shipment price per port.
- Destribution of shipment prices.
- Shipment size (volume)destribution.
- Identification of larestr shipmemt by volume.
- Summary statistics for sipment weiht and pricing.

  Key Insights
  - Certain destination ports handle significantly higher shipment volumes.
  - Shipment prices show high variability, with noticable high-value outliers.
  - Cargo sizes vary widely, indicating differences in shipment categories.
  - Some ports are associated with higher average shipment values.
 
  Conclusion
  Thus project demonstrates prectical skills in
  - Data cleaning and preprocessing
  - Handling missing values
  - Features engineering
  - Aggregation and grouping
  - Business-focused data interpretaion

    It reflects my growing ability to explore, clean, analyze, and derive insigts from real-world operational datasets.
