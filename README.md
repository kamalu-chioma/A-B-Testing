# A/B Testing - Project

## By: Chioma Kamalu

### Overview
This repository contains an IPython Notebook (IPYNB) file showcasing an A/B Testing project conducted by Chioma Kamalu. A/B Testing is a statistical/experimental technique used to analyze different marketing strategies, aiming to identify the most effective approach in terms of conversion, click-through rate (CTR), and return on investment (ROI).

### Project Aim
The primary goal of this project is to determine the marketing strategy that yields the highest conversion visually. The analysis focuses on two campaigns: Control Campaign and Test Campaign. Various metrics such as impressions, website clicks, content viewed, products added to cart, and purchases are examined to make informed decisions.

### Tools Used for A/B Testing
The project involves utilizing tools like Google Analytics, Adobe Target, Hubspot, etc., to monitor and analyze marketing strategies on an E-commerce site.

### Data Preparation
- The datasets include details on campaign names, datestamps, amount spent, impressions, reach, website clicks, searches, content viewed, products added to cart, and purchases.
- The data undergoes preprocessing, including renaming columns and handling null values.

### A/B Testing Analysis
1. **Visualizing Metrics:**
   - Scatter plots are created to visualize the relationship between key metrics, such as impressions vs. amount spent and content viewed vs. website clicks.
  
2. **Comparing Campaigns:**
   - Pie charts are employed to compare metrics between Control and Test Campaigns, including searches, website clicks, content viewed, products added to cart, amount spent, and purchases.
  
3. **Decision Making:**
   - Analysis indicates that the Test Campaign outperforms in certain metrics (e.g., website clicks), while the Control Campaign excels in others (e.g., products added to cart).
   - The control campaign demonstrates higher sales and a lower marketing spend, making it the preferred choice.

### Recommendations
The Control Campaign is identified as the more successful strategy based on the analysis. However, insights from the Test Campaign, especially regarding conversion rate, can be leveraged to enhance the Control Campaign further, potentially increasing ROI.

### Repository Structure
- `A_B_Testing_Project.ipynb`: The IPython Notebook containing the code, analysis, and visualizations.
- `control_group.csv` and `test_group.csv`: Datasets used for the A/B Testing analysis.

### Dependencies
The project utilizes Python with libraries such as Pandas, datetime, and plotly for data manipulation, visualization, and analysis.


