# Internship-task2.1
This repository contains a comprehensive analysis of the Heart Disease dataset from the UCI Machine Learning Repository. The primary goal was to explore, visualize, and model the data to understand the factors contributing to heart disease.

Installation
To get started, users should clone the repository and install the data set and work on it.
```sh
pip install ucimlrepo
from ucimlrepo import fetch_ucirepo 
  
# fetch dataset 
heart_disease = fetch_ucirepo(id=45) 
  
# data (as pandas dataframes) 
X = heart_disease.data.features 
y = heart_disease.data.targets 
  
# metadata 
print(heart_disease.metadata) 
  
# variable information 
print(heart_disease.variables) 

```
Usage
The provided Jupyter notebook was designed to facilitate data exploration and analysis.

Requirements
-  pandas
- seaborn
-  matplotlib
- ucimlrepo
- Python 3.x
- Dataset
The dataset was fetched using the ucimlrepo library.

### Understanding the Dataset
The features and targets were concatenated to form a complete dataset. Then statistical data was checked to confirm for the preprocesssing and making the data model ready

 - Exploratory Data Analysis (EDA)
 - EDA involved several key steps:

**Checking Data Types**: This helped in understanding the nature of each column, identifying categorical and numerical data.
**Missing Values**: Detecting any missing values ensured that the dataset was clean and ready for analysis.
**Basic Statistics**: Generating summary statistics provided insights into the distribution and central tendencies of the data, such as mean, median, and standard deviation.
### Data Visualization
Data visualization was performed to gain deeper insights into the dataset:

**Distribution of Target Variable**: Visualizing the distribution of the target variable helped in understanding the balance between different classes.
**Pairplot**: This visualized relationships between features, helping to identify patterns and correlations.
### Correlation Matrix
The correlation matrix was computed and visualized to understand the relationships between different variables. This helped in identifying which features were strongly correlated with each other, which could be useful for feature selection and understanding the dataset's structure.
