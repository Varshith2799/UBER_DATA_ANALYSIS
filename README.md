# UBER_DATA_ANALYSIS

This project performs an exploratory data analysis (EDA) of Uber ride data using Python libraries like Pandas, Matplotlib, and Seaborn. The dataset was obtained from a [GeeksforGeeks]([https://www.geeksforgeeks.org/](https://media.geeksforgeeks.org/wp-content/uploads/20240919115958/UberDataset.csv)). The goal is to understand ride patterns, frequent locations, trip purposes, and ride distances.

## 📁 Dataset

- **File**: `UBER_DATA.csv`
- **Records**: 1,156 Uber rides
- **Columns**:
  - `START_DATE`, `END_DATE`: Timestamps for ride start and end
  - `CATEGORY`: Type of ride (`Business` or `Personal`)
  - `START`, `STOP`: Pickup and drop locations
  - `MILES`: Distance of the trip
  - `PURPOSE`: Reason for the trip (e.g., `Meeting`, `Customer Visit`)

## 🔍 Project Objectives

- Convert timestamp columns to datetime format
- Extract features like hour, day, and month
- Identify trends in ride categories and purposes
- Find most frequent routes and busiest days
- Visualize data through plots (bar plots, histograms, heatmaps)

## 📊 Key Findings

- Business trips dominate over personal rides
- Peak ride hours and weekdays can be identified
- Some trips have missing purposes which can be imputed or analyzed
- Fort Pierce was the most frequent starting location
- Longest ride was over 60 miles

## 🛠 Tools Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## 🚀 How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/Varshith2799/Uber_Data_Analysis.git
   cd Uber_Data_Analysis
