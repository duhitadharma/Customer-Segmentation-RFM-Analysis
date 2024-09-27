# Customer-Segmentation-RFM-Analysis
# Customer Segmentation using RFM Analysis

## Overview
This project performs customer segmentation using RFM (Recency, Frequency, Monetary) analysis to identify different customer groups based on their purchasing behavior. The goal is to better understand the customer base and tailor marketing strategies accordingly.

## Data Description
The dataset used in this analysis contains online retail data, including:
- **InvoiceNo**: Transaction ID
- **StockCode**: Product code
- **Description**: Product description
- **Quantity**: Number of units purchased
- **InvoiceDate**: Date of transaction
- **UnitPrice**: Price per unit
- **CustomerID**: ID of the customer
- **Country**: Country of the customer

## Analysis Process
1. **Data Cleaning**: Handling missing values, filtering out invalid entries.
2. **RFM Calculation**: Calculating Recency, Frequency, and Monetary values for each customer.
3. **Customer Segmentation**: Assigning RFM scores and segmenting customers into categories like:
   - **Champions**
   - **Loyal Customers**
   - **Potential Loyalists**
   - **At Risk**
   - **Need Attention**
4. **Insights and Visualization**: Visualizing the distribution of customers across segments.

## Results
- **Number of Customers per Segment**: Visualized as bar charts.
- **Revenue Contribution by Segment**: Displayed as pie charts.

## Future Work
- Applying machine learning models such as clustering (e.g., K-means) to find hidden patterns in customer behavior.
- Exploring other segmentation methods like demographic segmentation.

## Usage
- Clone the repository and open the Jupyter notebook to explore the analysis.
- Use the data to run your own customer segmentation.

## License
[MIT License](LICENSE)
