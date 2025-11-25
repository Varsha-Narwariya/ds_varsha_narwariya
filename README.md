# 📊 Trader Behavior Insights – Data Science Assignment  
**Candidate:** Varsha Narwariya  
**Role:** Junior Data Scientist – Trader Behavior Insights

---

## 📁 Project Structure

ds_varsha_narwariya/

├── notebook_1.ipynb 

├── csv_files/

│ └── *.csv

├── outputs/

│ └── *.png / *.jpg

├── ds_report.pdf 

└── README.md 


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

No external libraries beyond standard data science stack are required.
