# Food Delivery Data Integration

## Overview
This project integrates food delivery data from multiple sources into a single clean dataset for analysis. The objective is to combine transactional, user, and restaurant data and prepare a final dataset that acts as the source of truth for all analytical questions.

---

## Data Sources
- **orders.csv** – Order transaction data  
- **users.json** – User details including city and membership type  
- **restaurants.sql** – Restaurant details including cuisine and ratings  

---

## Methodology
- Loaded data from CSV, JSON, and SQL formats using Pandas and SQLite  
- Performed **left joins** to retain all order records  
- Cleaned duplicate columns and standardized data  
- Created time-based features for trend and seasonality analysis  

---

## Output
- **final_food_delivery_dataset.csv**  

---

## Files in Repository
- `Food_Delivery_Data_Integration.ipynb`
- `final_food_delivery_dataset.csv`
- `README.md`

---

## How to Run
Open the Jupyter Notebook and run all cells sequentially.

