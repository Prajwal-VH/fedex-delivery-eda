# fedex-eda


# Optimizing FedEx Logistics Through Data Analysis

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the SCMS Delivery History dataset to understand shipment patterns, transportation modes, freight costs, and delivery performance.

The dataset contains 10,324 records and 33 columns related to medical-product supply chain operations.

## Objectives
- Analyze shipment distribution across countries and transportation modes.
- Identify high-volume product groups and vendors.
- Examine freight costs in relation to shipment weight and transportation mode.
- Evaluate delivery performance and identify late-delivery patterns.
- Develop data-driven business recommendations for logistics optimization.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Plotly
- Jupyter Notebook

## Key Findings
- South Africa had the highest number of records, with 1,406.
- Air was the most frequently recorded shipment mode, with 6,113 records.
- ARV was the largest product group, with 8,550 records.
- Of 10,324 records, 1,186 shipments were classified as late.
- Ocean shipments had a late-delivery rate of 17.52%, followed by Truck at 16.08%.
- Shipment weight and freight cost had a weak positive correlation of 0.232.

## Business Recommendations
- Investigate the causes of late deliveries.
- Review scheduling and transit times for Ocean and Truck shipments.
- Evaluate transportation options to identify potential cost savings.
- Improve the completeness and accuracy of logistics data.
- Use shipment trends to support operational planning.

## Project Files
- `FedEx EDA notebook.ipynb` — Data inspection, preprocessing, visualizations, insights, and recommendations.

## Dataset Note
The source file is named `SCMS_Delivery_History_Dataset.csv` and concerns medical-product supply chain operations. The project uses the assignment's FedEx logistics framing while analyzing the actual source data.

## Conclusion
This project demonstrates how Python-based EDA can uncover shipment trends, delivery challenges, and freight cost patterns to support data-driven logistics decisions.
