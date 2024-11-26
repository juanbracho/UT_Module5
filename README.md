# Module 5: Data Visualization with Matplotlib and Pandas

## Overview
This module dives into the visualization of data using Python libraries like **Matplotlib** and **Pandas**. You'll learn how to create and customize visualizations that tell a compelling story about your data. Additionally, the module introduces you to **SciPy**, which is essential for statistical computing in Python. By the end of this module, you will be equipped with the skills to perform exploratory data analysis and present your findings visually.

---

## What We Learn
- Navigate **Matplotlib's PyPlot** interface.
- Create line charts, bar charts, pie charts, and scatter plots using **Matplotlib**.
- Use **Pandas DataFrame.plot()** for quick and efficient visualizations.
- Calculate statistical measures like mean, median, variance, and standard deviation using **NumPy** and **SciPy**.
- Identify and handle outliers using box plots.
- Perform regression analysis and calculate correlation coefficients.

---

### Steps to Complete the Assignment:

### 1. **Prepare the Data**
- Merge the provided `mouse_metadata` and `study_results` datasets into a single DataFrame.
- Display the total number of unique mouse IDs.
- Remove duplicate records and clean the dataset as needed.

### 2. **Generate Summary Statistics**
- Calculate descriptive statistics for each drug regimen:
  - Mean, median, variance, standard deviation, and SEM (Standard Error of the Mean) of tumor volumes.

### 3. **Create Bar Charts and Pie Charts**
- **Bar Charts**:
  - Show the total number of measurements for each drug regimen using both **Pandas** and **Matplotlib** methods.
- **Pie Charts**:
  - Display the distribution of male and female mice in the study using both **Pandas** and **Matplotlib** methods.

### 4. **Quartiles, Outliers, and Box Plots**
- Determine potential outliers in tumor volume data for selected drug regimens.
- Create a **box plot** to visualize the final tumor volume across the four treatment groups: Capomulin, Ramicane, Infubinol, and Ceftamin.

### 5. **Create a Line Plot and Scatter Plot**
- **Line Plot**:
  - Show tumor volume over time for a specific mouse treated with Capomulin.
- **Scatter Plot**:
  - Display mouse weight versus tumor volume for the Capomulin regimen.

### 6. **Perform Correlation and Regression Analysis**
- Calculate the correlation coefficient between mouse weight and tumor volume for the Capomulin treatment.
- Generate a regression line to analyze the relationship between these variables.

---

## Deliverables
1. **Data Visualizations**:
   - Include bar charts, pie charts, box plots, line plots, and scatter plots as per instructions.
2. **Statistical Analysis**:
   - Provide summary statistics and regression analysis results.
3. **Documentation**:
   - Add comments and detailed explanations for each visualization and calculation.
4. **Code Quality**:
   - Ensure your code is clean, well-documented, and free of errors.

---

## Skills Practiced
- Data cleaning and merging using **Pandas**.
- Creating visualizations with **Matplotlib** and **Pandas**.
- Statistical analysis using **SciPy** and **NumPy**.
- Exploratory data analysis to identify trends and outliers.
- Effective communication of findings through visualizations and code.
