# 📊 Zomato Data Analysis Using Python
An end-to-end data analytics project using Python to explore, clean, and visualize a Zomato restaurant dataset. This project uncovers hidden business insights, consumer dining patterns, and restaurant trends across various culinary categories.

---

## 🎯 Project Objectives
The analysis answers critical industry questions, including:
* **Order Preferences**: Determining if online or offline service dominates the market.
* **Popular Categories**: Identifying which restaurant types receive the most traction and votes.
* **Spending Habits**: Finding the preferred dining budget and price range for couples.
* **Rating Correlations**: Evaluating how online delivery availability impacts customer ratings.

## 📁 Repository Structure
* `Zomato-data-.csv`: The raw dataset containing information on restaurant names, ratings, costs, and orders.
* `Zomato_Data_Analysis.ipynb`: Jupyter Notebook containing data preprocessing, analysis steps, and visualizations.

## 🛠️ Step-by-Step Implementation
1. **Importing Libraries**: Loaded essentials like Pandas, NumPy, Matplotlib, and Seaborn.
2. **Data Cleaning**: Stripped denominator strings from the rating column and converted the values into floating-point numbers for mathematical calculations.
3. **Exploratory Data Analysis (EDA)**: Count plots, bar charts, line graphs, and heatmaps were systematically generated to trace correlations.

## 📊 Key Insights Found
* **Dining Dominance:** The majority of tracked restaurants fall under the dining category and accumulate the most customer votes.
* **Budget Comfort Zone:** Most couples prefer dining locations with an approximate cost of 300 rupees.
* **The Rating Gap:** Restaurants accepting online orders consistently secure higher ratings compared to offline-only spots.
* **Behavioral Shifts:** Heatmap correlations reveal that customers favor ordering online from cafes, but choose to visit dining restaurants in person.

## 🚀 How to Run Locally

### 1. Clone the Repository
```bash
git clone
cd YOUR_REPOSITORY_NAME
```

### 2. Install Required Packages
Make sure you have Python installed, then run:
```bash
pip install pandas numpy matplotlib seaborn notebook
```

### 3. Open the Notebook
Launch Jupyter Notebook to view and run the code:
```bash
jupyter notebook
```
Click on `Zomato_Data_Analysis.ipynb` inside your browser to explore the full data journey!
