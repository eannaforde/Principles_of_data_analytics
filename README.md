# Principles of Data Analytics

## Author: Eanna Forde

## Overview
This repository contains a Jupyter notebook (tasks.ipynb) that explores the Wine dataset from sklearn.datasets. 

## 1. Introduction
The notebook covers the following steps:

- Loading and exploring the dataset
- Computing summary statistics (mean, median, range, standard deviation, IQR)
- Visualizing feature distributions with histograms
- Exploring relationships between features using scatter plots
- Fitting a linear regression model and calculating the R² value

## Repository contents
- 'tasks.ipynb' - The main jupyter notebook with analysis and visualisations.
- '.gitignore' - Standard file to ignore unnecessary files.
- 'README.md' - This file providing context and instructions.

[Eanna.Forde/myproject](https://github.com/eannaforde/Principles_of_data_analytics)

## 2. Import Libraries
The following Python libraries were used:

- `pandas` – for data manipulation  
- `numpy` – for numerical computations  
- `matplotlib` – for data visualization  
- `sklearn` – for machine learning and linear regression

## 3. Load Data
The dataset is available in `sklearn.datasets`. The data was loaded into a pandas DataFrame for analysis.  

**References:**  
[1] [Scikit-learn Wine Dataset Documentation](https://scikit-learn.org/stable/datasets/toy_dataset.html#wine-recognition-dataset)  
[2] [Pandas DataFrame Documentation](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.html)

## 4. Data Exploration
The dataset was explored using:

- `.shape` – check dataset dimensions  
- `.head()` – display the first few rows  
- `.tail()` – display the last few rows  
- `.columns` – list feature names  
- `.target_names` – list wine class labels  

**References:**  
[3] [Pandas DataFrame `.head()` Documentation](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.head.html)  
[4] [Pandas DataFrame `.tail()` Documentation](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.tail.html)

## 5. Summary Statistics
Summary statistics were computed for each feature to understand distributions and variability:

- Mean – average value  
- Range – max minus min  
- Standard deviation – variability around the mean  
- Median – middle value  
- Interquartile range (IQR) – spread of the middle 50% of values  

**References:**  
[5] [Pandas `.mean()`](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.mean.html)  
[6] [Pandas `.std()`](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.std.html)  
[7] [Pandas `.median()`](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.median.html)  
[8] [Pandas `.quantile()`](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.quantile.html)

## 6. Data Visualization
### Histograms
Histograms were plotted for selected features (alcohol, malic_acid, color_intensity, proline) to understand the distribution of values.  

**References:**  
[9] [Matplotlib Histograms Tutorial - Real Python](https://realpython.com/python-histograms/)  
[10] [DataCamp: Histograms in Matplotlib](https://www.datacamp.com/tutorial/histograms-matplotlib)

### Scatter Plots
Scatter plots were used to explore relationships between pairs of features:

- alcohol vs malic_acid  
- color_intensity vs hue  
- flavanoids vs total_phenols  

**References:**  
[11] [Matplotlib Scatter Plot Documentation](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.scatter.html)

## 7. Correlation and Regression
A linear regression line was fitted between alcohol and color_intensity to examine the correlation. The R² value indicates how well the line fits the data:

**References:**  
[12] [Scikit-learn Linear Regression Example](https://scikit-learn.org/stable/auto_examples/linear_model/plot_ols_ridge.html)  
[13] [Matplotlib Pyplot Tutorial](https://matplotlib.org/stable/tutorials/pyplot.html)

## Conclusion
This notebook provides an exploration of the Wine dataset, including summary statistics, visualizations, and a linear regression analysis to identify relationships between chemical features and wine classes.