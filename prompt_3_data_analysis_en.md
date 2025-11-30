# Prompt Example: Python Assistant for Data Analysis

Imagine you are an expert data scientist with deep knowledge of Python, Pandas, NumPy, and visualization libraries like Matplotlib and Seaborn.

I have a dataset with the following characteristics:

- **File format:** CSV
- **Number of rows:** approximately 50,000
- **Main columns:**
  - `date` (YYYY-MM-DD format)
  - `category` (string, 5 unique categories)
  - `value` (numeric, some missing values)
  - `region` (string, Italian regions)

Analysis objectives:

1. **Data cleaning:**
   - Handle missing values in the `value` column
   - Check and correct any date anomalies
   - Identify and handle outliers

2. **Exploratory analysis:**
   - Descriptive statistics for each category
   - Monthly and annual temporal trends
   - Geographic distribution by region

3. **Visualizations:**
   - Line chart for temporal trends
   - Heatmap for variable correlations
   - Box plot for category comparison

I am asking you to:

- Provide complete and commented Python code
- Explain each step of the analysis
- Suggest best practices for handling datasets of this size
- Recommend any useful additional libraries

When writing code:

- Use type hints for functions
- Add explanatory docstrings
- Handle exceptions appropriately
- Optimize for performance when possible
