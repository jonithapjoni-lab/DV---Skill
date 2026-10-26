##House Sale Data Analysis

##Project Overview
House Sale Data Analysis is a Python-based data analysis project that explores house sale data to understand property characteristics, pricing, renovation history, and unusual house-price values.

##Objectives
- Explore key property features such as bedrooms, living area, grade, and year built.
- Visualize distributions in the dataset.
- Create useful features such as sale year, property age, and renovation status.
- Calculate price per square foot for living area and lot area.
- Check missing values and handle zero-bedroom and zero-bathroom entries.
- Identify house-price outliers using the Interquartile Range (IQR) method.
- 
##Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab
- 
##Dataset
The notebook loads a compressed CSV dataset using Pandas. The dataset is expected to contain columns used in the analysis, including:
price, date, bedrooms, bathrooms, sqft_living, sqft_lot, grade, yr_built, and yr_renovated.

Place the dataset archive in your Google Colab environment and update the file path in the notebook if needed.

##Project Workflow
1. Load libraries and data using Pandas, NumPy, Matplotlib, and Seaborn.
2. Explore the data by listing dataset columns and reviewing descriptive statistics.
3. Visualize property features with histograms and a count plot.
4. Create features such as sale year, property age, and renovation status.
5. Calculate price metrics including price per square foot of living space and lot area.
6. Check data quality by inspecting missing values and zero-bedroom/zero-bathroom records; replace zero values with the median of positive entries for those fields.
7. Analyze renovation history by calculating age at renovation and years since renovation.
8. Detect price outliers using the IQR rule and display a box plot, histogram, and the highest-priced properties.
How to Run
1. Open House_sale.ipynb in Jupyter Notebook or Google Colab.
2. Upload or make the dataset archive available.
3. Update the pd.read_csv(...) path in the notebook to match the dataset location.
4. Run the notebook cells from top to bottom.

##Outputs
- Descriptive statistics for selected property features.
- Plots showing the distributions of bedrooms, living area, grade, and year built.
- Additional columns for sale year, property age, renovation status, and renovation-related age.
- Price-per-square-foot summaries.
- Data-quality checks and IQR-based price-outlier analysis.
- 
##Notes
- The notebook identifies price outliers but does not remove them.
- The notebook checks for missing values; it does not apply a general missing-value imputation step.
- Results depend on the dataset provided and the path configured in the notebook.
