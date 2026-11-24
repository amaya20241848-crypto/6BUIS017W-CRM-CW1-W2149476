S&P 500 Stock Segmentation – 6BUIS017W Coursework

Project overview

This project analyses S&P 500 shares using weekly returns, weekly beta and adapted Recency, Frequency and Monetary (RFM) measures. It applies Ward hierarchical clustering and K-means clustering to compare risk-and-return segments with trading-activity segments.

Analysis period

Daily market data: 1 January 2021 to 31 December 2024
Benchmark: S&P 500 Index (^GSPC)
Feature observation date: 31 December 2024

Main notebook

CW1_CRM&CM(1).ipynb
- The notebook contains the data acquisition, validation, feature engineering, clustering, evaluation, visualisations and sector-composition analysis.

Supporting data files

sp500_ticker_list.csv – S&P 500 ticker selection snapshot
share_inclusion_exclusion_log.csv – share selection and exclusion records
daily_validation_summary.csv – daily data validation summary
task1_feature_table.csv – Task 1 feature table
task2_feature_table_with_clusters.csv – feature table with baseline cluster assignments
share_cluster_assignments.csv – share-level cluster assignments
task3_sector_cluster_data.csv – data used for sector-composition analysis

Reproducibility

The notebook documents the analysis workflow, feature definitions, data validation, clustering methods and evaluation. Run the notebook in Google Colab, following the cells in order. The required data files should be available in the notebook's working environment.

Data sources

S&P 500 constituent information: Wikipedia, List of S&P 500 companies
Historical share and benchmark market data: Yahoo Finance, accessed through yfinance

