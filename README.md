
# 📊 Kickstarter Project Analysis: Data Manipulation and Visualization

## 🔍 Overview

This project explores and visualizes Kickstarter project data to uncover patterns in campaign outcomes, launch trends, and funding dynamics. Using Python’s data manipulation and visualization libraries, the project transforms raw datasets into interpretable insights that can support creators, analysts, and researchers in understanding success factors in crowdfunding.

## 📁 Dataset

- **Source**: [Kaggle - Kickstarter Projects Dataset](https://www.kaggle.com/datasets/kemical/kickstarter-projects)
- **File used**: `kickstarter.csv`

Each row represents a unique Kickstarter campaign, including metadata such as project name, category, goal amount, amount pledged, country, and the campaign's success state.

## ⚙️ Key Steps

### 1. Data Cleaning & Preprocessing
- Converted `launched` and `deadline` columns into datetime format
- Extracted year and month from launch dates
- Filtered out inconsistent or missing values for accurate visualizations

### 2. Exploratory Data Analysis (EDA)
- Visualized the number of launched campaigns over time
- Analyzed success rates by main and sub-categories
- Explored geographical trends across countries
- Compared goals and pledges by project state (successful, failed, canceled)

### 3. Visualization Techniques
- Line plots to show trends in monthly project launches
- Bar plots and pie charts for category and state distributions
- Boxplots and scatter plots for financial insights (goal vs. pledged)
- Interactive dashboards using Holoviews and Panel for dynamic exploration

## 🛠️ Tools & Technologies

- Python 3.x
- Pandas for data manipulation
- Matplotlib and Seaborn for static plots
- Holoviews & Panel for interactive dashboards

## 👤 Author

Yi Hsiang (Royce) Yen  
MS in Business Analytics, University of Minnesota  
