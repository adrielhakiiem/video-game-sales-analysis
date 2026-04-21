# Video Game Sales Analysis

## Overview
This project analyzes global video game sales data to identify the key factors influencing commercial success across time, platforms, genres, regions, and critic scores.

The analysis focuses on uncovering industry trends and patterns using exploratory data analysis (EDA) and statistical interpretation.

## Objectives
- Analyze how video game sales evolved over time
- Examine the relationship between critic scores and sales
- Compare platform performance across regions
- Identify genre preferences across global markets

## Dataset
- Source: Kaggle (Video Game Sales Dataset)
- Covers approximately 20 years of data
- Features include:
  - Global and regional sales (NA, EU, JP, Other)
  - Platform, genre, release year
  - Critic scores

## Methodology

### Data Preprocessing
- Cleaned dataset and handled missing values
- Selected relevant features for analysis

### Exploratory Data Analysis (EDA)
- Sales trends over time
- Number of games released per year
- Average sales per game

### Correlation Analysis
- Heatmaps and regression analysis
- Weak positive correlation between critic scores and sales (r ≈ 0.24)

### Comparative Analysis
- Platform performance (PS2 identified as top-selling platform)
- Genre performance across regions
- Regional sales distribution

## Key Insights
- Global sales peaked between 2006–2009 and declined after 2010 due to digital distribution shifts
- Critic scores have limited impact on sales (weak correlation)
- North America and Europe dominate global sales
- Japan shows strong preference for RPGs
- Action, Sports, and Shooter genres lead globally

## Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## Project Structure
- games-sales.ipynb
- Report_Ku_TT3L_Group_D.pdf
- dataset/
- README.md

## How to Run
1. Open Jupyter Notebook
2. Run: games-sales.ipynb

## Highlights
- Multi-dimensional analysis across time, platform, genre, and region
- Applied correlation and trend analysis to real-world dataset
- Generated insights aligned with real industry behavior

## Future Improvements
- Include digital sales data for better accuracy
- Apply predictive modeling (e.g., sales forecasting)
- Build an interactive dashboard (Power BI or Streamlit)
- 
