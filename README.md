# Data Science Project: California Housing Analysis

## Problem / Research Question
What factors most influence housing prices in California, and how does location affect property values?

## Dataset Source and Usage Permissions
The dataset (`housing.csv`) is the classic California Housing dataset, provided as part of the CISC7204 coursework. It is used strictly for educational and analytical purposes.

## Methods and Tools Used
- Python (Pandas, Matplotlib)
- Data Cleaning: Handled missing values by dropping null rows (`dropna()`).
- Exploratory Data Analysis (EDA) and data visualization.

## Key Findings and Limitation
**Key Finding:** There is a strong positive correlation between median income and house value. Furthermore, properties located near the coast tend to have significantly higher median values.
**Limitation:** The dataset contains capped values (e.g., many houses are exactly at $500,001). This may limit the accuracy of predicting extremely expensive properties in future modeling.

## Instructions for Running the Analysis
1. Clone this repository or download the notebook.
2. Ensure you have Python installed. Install the required packages by running: `pip install -r requirements.txt`
3. Open the Jupyter Notebook and run all cells sequentially to reproduce the visualizations.
