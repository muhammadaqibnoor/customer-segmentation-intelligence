# Customer Segmentation & Intelligence System

An interactive Data Science project that analyzes customer purchasing behavior using RFM analysis, K-Means clustering, and Customer Lifetime Value (CLV) metrics.

## Project Overview

This project segments customers into meaningful groups based on their purchasing behavior and provides actionable business insights through an interactive Streamlit dashboard.

## Key Features

- Data cleaning and exploratory data analysis (EDA)
- Recency, Frequency, Monetary (RFM) analysis
- RFM-based customer segmentation
- K-Means clustering
- Elbow Method and Silhouette Score evaluation
- PCA dimensionality reduction
- Customer Lifetime Value (CLV) analysis
- Interactive Streamlit dashboard
- Revenue and customer segment visualizations
- Customer data filtering and CSV download

## Customer Segments

The K-Means model identifies four customer groups:

1. Champions
2. Loyal Customers
3. Hibernating Customers
4. Recent Low-Spenders

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Plotly
- Streamlit
- Jupyter Notebook

## Project Structure

```text
customer-segmentation-intelligence/
├── data/
├── notebooks/
├── src/
├── models/
├── reports/
├── images/
├── dashboard/
│   └── app.py
├── .gitignore
└── requirements.txt
```

## How to Run

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit dashboard:

```bash
python -m streamlit run dashboard/app.py
```

## Dataset

UCI Online Retail Dataset:

https://archive.ics.uci.edu/dataset/352/online+retail

## Business Value

The project helps businesses identify high-value customers, understand purchasing behavior, improve customer retention, and develop targeted marketing strategies.

## Author

Data Science Portfolio Project