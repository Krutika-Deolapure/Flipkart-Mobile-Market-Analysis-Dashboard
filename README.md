# Flipkart Mobile Market Analysis Dashboard

This project provides a comprehensive analysis of the Flipkart mobile phone market using a dataset containing detailed product information and a Power BI dashboard for interactive visualization. The goal is to help stakeholders understand current trends, pricing, and product distribution across various brands and segments.

## Dataset Overview

The dataset contains information about mobile phones from multiple brands, with attributes such as:

- **Brand**: The manufacturer of the mobile phone (e.g., OPPO, Samsung, Apple, etc.)
- **Model**: The specific model name or number.
- **Color**: Available color variants.
- **Memory**: RAM size (e.g., 4 GB, 6 GB).
- **Storage**: Internal storage size (e.g., 64 GB, 128 GB).
- **Rating**: Average customer rating (out of 5).
- **Selling Price**: Current market price.
- **Original Price**: Launch or MRP price.

### Key Features

- **Total Products, Brands, Average Price & Rating**  
  Top-level summary indicators to give a quick overview of the dataset:
  - **Total Products**: Number of unique mobile phone models.
  - **Average Price**: Mean selling price across all products.
  - **Average Rating**: Mean customer rating.
  - **Total Brands**: Number of brands represented.

- **Products by Price Segment**  
  Pie chart showing distribution across four price segments:
  - Budget (≤10K)
  - Mid-Range (10K–20K)
  - Premium (20K–40K)
  - Flagship (>40K)

- **Product Offerings by Brand**  
  Bar chart showing the number of models offered by each brand.

- **Price vs Rating Analysis**  
  Scatter plot visualizing the relationship between selling price and average rating for each brand.

- **Storage Distribution by Brand**  
  Stacked bar chart showing which brands offer which storage variants.

- **Interactive Filters**  
  Slicers to filter data by:
  - Brand
  - Price Segment
  - Memory Segment
  - Storage Segment
