# Life Expectancy Project
 EDA, Observations, Statistical Analysis, Inferences of life expectancy data
 
# Objective: 
The purpose of our analysis on life expectancy is to uncover potential patterns that affect the life expectancy in different communities. We aim to do this by analyzing the correlations between factors such as; country development status, disease management, immunization coverage, and expenditure per citizen.

# Dataset Overview: 
The life expectancy dataset used was sourced through Kaggle and uses data collected from the World Health Organization and United Nations data repository websites. It consists of 22 columns and 2938 rows with 20 key variables.

# Data Cleaning:  
The accuracy and reliability of the dataset was improved by removing incomplete entries.  Entries with no data present (missing values) were removed from the analysis. 

# Analysis Techniques:  
Data visualizations:
- Correlation heatmap
- linear regression trendlines
- box and whisker plot
- histogram
- violin graph
- scatterplot

# Industry Focus:  
Healthcare

# Research Questions:  
1A.  How does the life expectancy of individuals in developed countries compare to those in developing countries?

1B.  What is the life expectancy trend by country?

2.  What is the standalone most impactful factor to life expectancy?
  
3.  Is there a correlation between immunization coverage for Hepatitis B, Polio, Diphtheria and life expectancy?
   
4.  Is there a correlation between a country's healthcare expenditure per capita and its life expectancy?

# Conclusions
Developed countries are correlated with a longer life expectancy but developing countries does not always correlate with a lower life expectancy.

Healthcare Expenditure: There is a significant correlation between healthcare expenditure per capita and life expectancy (0.38). Countries that invest more in healthcare tend to have a higher life expectancy.

Immunization Coverage (Ranked order): Diphtheria (0.48), Polio (0.47), Hepatitis B (0.26) and life expectancy. Countries with higher immunization rates tend to have higher life expectancy, highlighting the importance of vaccination programs in public health.

Most Impactful Factor: School identified as the most impactful standalone factor on life expectancy, with a strong positive correlation. Higher levels of education are associated with longer life expectancy, underscoring the role of education in promoting health.

## Data Sources: 
Kaggle Life Expectancy Dataset

https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who?resource=download

## Tools and Libraries: 
- pandas
- numpy
- matplotlib.pyplot
- Seaborn

