# 🍽️ Zomato Data Analysis Using Python

## Project Overview
This project analyzes **Zomato's restaurant dataset** to uncover insights about:
- Customer preferences  
- Restaurant trends  
- Online vs offline order behavior  
- Pricing patterns for couples  
- Restaurant type popularity  

The aim is to help make **data-driven business decisions** in the food industry.

---

## Key Insights
- **Dining** restaurants are the most common and most voted category.
- Majority of restaurants **do not accept online orders**.
- Ratings mostly fall between **3.5 to 4**.
- Couples prefer restaurants with an approximate cost of **₹300**.
- **Online orders** tend to receive higher ratings compared to offline orders.
- Cafes mainly receive **online orders**, while dining restaurants primarily get **offline orders**.

---

##  Technologies Used
- **Python** 🐍
- **Pandas** – Data manipulation
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical plots

---

## Dataset
The dataset contains:
- Restaurant details (name, location, type)
- Ratings and votes
- Online order availability
- Price range
- Approximate cost for two people

---

## Steps in Implementation
1. **Import Libraries** – Pandas, NumPy, Matplotlib, Seaborn.
2. **Load Dataset** – Read CSV file into Pandas DataFrame.
3. **Data Cleaning** – Convert ratings to float, remove unnecessary characters, check for missing values.
4. **Exploratory Data Analysis**  
   - Popular restaurant types  
   - Votes distribution by type  
   - Online vs offline order count  
   - Ratings distribution  
   - Price preferences for couples  
5. **Visualization** – Bar charts, histograms, box plots, heatmaps.

---

##  Visualizations
- **Count Plots** – Restaurant type popularity  
- **Line Plot** – Votes by restaurant type  
- **Histogram** – Ratings distribution  
- **Box Plot** – Online vs offline rating comparison  
- **Heatmap** – Order mode preferences by restaurant type  

---

##  How to Run the Project
```bash
# Clone the repository
git clone https://github.com/YOUR-USERNAME/zomato-data-analysis.git

# Navigate to project folder
cd zomato-data-analysis

# Install dependencies
pip install -r requirements.txt

# Run the script
python zomato_analysis.py

