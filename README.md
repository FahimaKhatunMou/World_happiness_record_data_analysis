# World_happiness_record_data_analysis
# World Happiness Data Analysis

This repository contains an analysis of the **World Happiness Report** dataset, which ranks countries by their happiness scores based on various socio-economic indicators. The project includes exploratory data analysis (EDA), data cleaning, visualization, and the application of machine learning models for predicting happiness scores.

## Table of Contents
- [Project Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Data Analysis and Visualizations](#data-analysis-and-visualizations)
- [Machine Learning Models](#machine-learning-models)
- [Contributing](#contributing)
- [License](#license)

## Description

The **World Happiness Report** dataset ranks countries based on their happiness levels, determined by factors such as GDP per capita, social support, life expectancy, and perceptions of corruption. This project aims to analyze these relationships using various data analysis techniques and machine learning algorithms.

### Features:
- **Happiness Score**: The dependent variable (target), representing the happiness level of each country.
- **GDP per capita**: Economic output per person.
- **Social Support**: The perceived level of social support from friends and family.
- **Life Expectancy**: The average life expectancy of the population.
- **Freedom**: The perceived freedom to make life choices.
- **Generosity**: The level of charitable giving.
- **Corruption**: Perception of corruption in the government.
- **Dystopia Residual**: A constant used for normalizing scores.

## Installation

To run the analysis locally, follow these instructions:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/world-happiness-analysis.git
import matplotlib.pyplot as plt
import seaborn as sns

# Heatmap
![Heatmap](https://github.com/user-attachments/assets/beaeacec-6f0e-4557-99c6-618072aaeb89)

# Top 10 Happiest and Unhappiest countries
![Happy_country](https://github.com/user-attachments/assets/a2c7b3ef-dd2c-479c-b749-1ff8ed033bc1)

# Average Contribution of Key Factors to Happiness]
![Average Contribution of Key Factors to Happiness](https://github.com/user-attachments/assets/609bcb87-b3e5-4069-a85f-27aa00d417a7)

# Happiness Score by Region
![HappinessScoreByRegion](https://github.com/user-attachments/assets/bca3057c-76c5-43cb-99a7-5ffcd3d778ba)

# Distribution of Happiness Levels
![Distribution_Of_Happiness_levels](https://github.com/user-attachments/assets/7a1dd437-60b9-42d0-a762-92d80c30102f)

# Histograms
![Histograms](https://github.com/user-attachments/assets/8c16cf72-6652-41a1-9ff1-d77e2e0f3ba2)

# Scatter Plots
![ScatterPlot](https://github.com/user-attachments/assets/aab3175f-5d08-47dd-bbdd-d278ef89145e)

# Pie chart
![Pie chart](https://github.com/user-attachments/assets/75fc1176-bf02-4be8-8fcc-caa9dbe5b717)

# Actual vs Predicted Happiness Scores(LInear Regression)
![Linear_regression](https://github.com/user-attachments/assets/97ca3421-8a8e-400e-8315-a721954107c9)

# Actual vs Predicted Happiness Scores(Random Forest)
![RandomForest](https://github.com/user-attachments/assets/ed375876-9543-4e10-9dc4-91ed9cba16b1)

## Final Analysis

### Model Performance Summary

In this project, we analyzed the **World Happiness Report** dataset using both **Linear Regression** and **Random Forest Regression** models to predict the happiness scores of different countries. Here’s a summary of the results:

| Model               | RMSE (Root Mean Squared Error) | R² (R-Squared)  |
|---------------------|---------------------------------|------------------|
| Linear Regression   | 0.5734                          | 0.7599          |
| Random Forest       | 0.2463                          |  0.8201          |

### Interpretation of Results

- **Root Mean Squared Error (RMSE)**: This metric shows the average magnitude of the prediction errors (the lower, the better). 
  - The Random Forest model achieved a significantly lower RMSE (0.2463) compared to the Linear Regression model (0.5734), indicating that it produced more accurate predictions on average.

- **R-Squared (R²)**: This value represents the proportion of variance in the happiness scores explained by the model (the closer to 1, the better).
  - The Random Forest model had a higher R² score (0.8201) than the Linear Regression model (0.7599), suggesting that it captured more of the underlying patterns in the data.

### Final Insights

- **Model Selection**: Based on the evaluation metrics, the Random Forest model is the superior choice for this dataset. It outperforms the Linear Regression model in both RMSE and R², meaning it provides more accurate and reliable predictions for happiness scores.
  


### Conclusion

The **Random Forest model** was found to be more effective than the **Linear Regression model** in predicting happiness scores accurately. For future studies or applications where prediction accuracy is essential, Random Forest provides a better fit for this dataset. Additionally, the feature importance insights from Random Forest can guide policymakers or researchers in identifying key factors influencing happiness at a national level.





