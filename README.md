# 📊 Trader Behavior Insights – Data Science Assignment  
**Candidate:** Varsha Narwariya  
**Role:** Junior Data Scientist – Trader Behavior Insights

---

## 📁 Project Structure

ds_varsha_narwariya/
├── notebook_1.ipynb # Main Google Colab notebook with full analysis
├── notebook_2.ipynb # (Optional) Additional notebook
├── csv_files/ # Uploaded + processed CSV data
│ └── *.csv
├── outputs/ # All generated charts, graphs, images
│ └── *.png / *.jpg
├── ds_report.pdf # Final project report with insights
└── README.md # Instructions & documentation


---

## 🚀 Project Objective
The goal of this assignment is to:

- Analyze historical trader behavior using Hyperliquid execution data  
- Combine it with Bitcoin fear/greed sentiment data  
- Identify how sentiment affects trader performance  
- Build visual insights, correlations, and behavioral indicators  
- Demonstrate ability to work with real-world Web3 trading data  

---

## 📦 Setup Instructions

### **1. Environment**
This project is developed entirely in **Google Colab**.  
No local installation required.

### **2. Upload Data Files**
Upload the following to the Colab notebook:

1. `Historical Trader Data.csv`
2. `Fear_Greed_Index.csv`

Or place them manually inside:
/csv_files


### **3. Install Dependencies**
Run the first cell in the notebook to install required packages:

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from pathlib import Path

▶️ How to Run the Notebook

Open notebook_1.ipynb in Google Colab

Run all cells sequentially

The notebook will:

Load and clean datasets

Merge sentiment with trading data

Generate proxy leverage metric

Produce correlation & behavioral insights

Export all graphs automatically to /outputs/

📊 Outputs Generated

All charts and insights are automatically saved inside:

/outputs/


Including:

Sentiment distribution

PnL vs sentiment

Price & size distributions

Proxy leverage visualization

Daily trade count time series

Coin trading frequency plots

Workflow diagrams

🧠 Key Analysis

The notebook includes:

Sentiment → PnL relationships

Behavioral patterns during Fear vs Greed

Distribution of trade sizes, prices, and leverage

Symbol-level trading activity

Time-series trends for volatility & trading intensity

Proxy leverage estimation due to missing leverage field

📄 Final Report

All insights, visuals, and summary findings are documented in:

ds_report.pdf

✨ Notes

Leverage field was not present in the dataset, so a proxy leverage metric was engineered using:

proxy_leverage = Size USD / Execution Price

Timestamp formats were normalized because the dataset included both Timestamp IST and time/date.

All visualizations are shown inside the notebook and saved as PNGs.


🤝 Contact

For any clarification or feedback, feel free to reach out.
