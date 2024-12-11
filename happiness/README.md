# Automated Analysis Report

## Summary
{'columns': ['Country name', 'year', 'Life Ladder', 'Log GDP per capita', 'Social support', 'Healthy life expectancy at birth', 'Freedom to make life choices', 'Generosity', 'Perceptions of corruption', 'Positive affect', 'Negative affect'], 'data_types': {'Country name': dtype('O'), 'year': dtype('int64'), 'Life Ladder': dtype('float64'), 'Log GDP per capita': dtype('float64'), 'Social support': dtype('float64'), 'Healthy life expectancy at birth': dtype('float64'), 'Freedom to make life choices': dtype('float64'), 'Generosity': dtype('float64'), 'Perceptions of corruption': dtype('float64'), 'Positive affect': dtype('float64'), 'Negative affect': dtype('float64')}, 'missing_values': {'Country name': 0, 'year': 0, 'Life Ladder': 0, 'Log GDP per capita': 28, 'Social support': 13, 'Healthy life expectancy at birth': 63, 'Freedom to make life choices': 36, 'Generosity': 81, 'Perceptions of corruption': 125, 'Positive affect': 24, 'Negative affect': 16}, 'summary_stats': {'Country name': {'count': 2363, 'unique': 165, 'top': 'Argentina', 'freq': 18, 'mean': nan, 'std': nan, 'min': nan, '25%': nan, '50%': nan, '75%': nan, 'max': nan}, 'year': {'count': 2363.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 2014.7638595006347, 'std': 5.059436468192795, 'min': 2005.0, '25%': 2011.0, '50%': 2015.0, '75%': 2019.0, 'max': 2023.0}, 'Life Ladder': {'count': 2363.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 5.483565806178587, 'std': 1.1255215132391925, 'min': 1.281, '25%': 4.647, '50%': 5.449, '75%': 6.3235, 'max': 8.019}, 'Log GDP per capita': {'count': 2335.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 9.399671092077089, 'std': 1.1520694444710216, 'min': 5.527, '25%': 8.506499999999999, '50%': 9.503, '75%': 10.3925, 'max': 11.676}, 'Social support': {'count': 2350.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.8093693617021277, 'std': 0.12121176420299144, 'min': 0.228, '25%': 0.744, '50%': 0.8345, '75%': 0.904, 'max': 0.987}, 'Healthy life expectancy at birth': {'count': 2300.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 63.40182826086957, 'std': 6.842644351828009, 'min': 6.72, '25%': 59.195, '50%': 65.1, '75%': 68.5525, 'max': 74.6}, 'Freedom to make life choices': {'count': 2327.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.750281908036098, 'std': 0.13935703459253465, 'min': 0.228, '25%': 0.661, '50%': 0.771, '75%': 0.862, 'max': 0.985}, 'Generosity': {'count': 2282.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 9.772129710780206e-05, 'std': 0.16138760312630687, 'min': -0.34, '25%': -0.112, '50%': -0.022, '75%': 0.09375, 'max': 0.7}, 'Perceptions of corruption': {'count': 2238.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.7439709562109026, 'std': 0.1848654805936834, 'min': 0.035, '25%': 0.687, '50%': 0.7985, '75%': 0.86775, 'max': 0.983}, 'Positive affect': {'count': 2339.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.6518820008550662, 'std': 0.10623970474397627, 'min': 0.179, '25%': 0.572, '50%': 0.663, '75%': 0.737, 'max': 0.884}, 'Negative affect': {'count': 2347.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.27315083084789094, 'std': 0.08713107245795021, 'min': 0.083, '25%': 0.209, '50%': 0.262, '75%': 0.326, 'max': 0.705}}}

## Story
The analysis of the 'happiness.csv' dataset reveals a broad overview of factors influencing happiness levels across different countries and years. The dataset encompasses a variety of important indicators, including economic, social, and psychological dimensions that contribute to overall life satisfaction as measured by the "Life Ladder."

### Key Insights: 

1. **General Overview**: 
   - The dataset includes a total of 2,363 entries, featuring data from 165 unique countries, with Argentina being the most frequently represented, appearing 18 times across the dataset.

2. **Temporal Range**:
   - The data spans from 2005 to 2023, with a mean year of approximately 2015. This timeframe provides a historical context for assessing shifts in happiness correlating with world events, economic changes, and social dynamics.

3. **Life Ladder**:
   - The average score on the "Life Ladder," which reflects perceived life satisfaction, stands at 5.48 on a scale likely ranging from 1 (lowest satisfaction) to 10 (highest satisfaction). The values range between 1.281 and 8.019, indicating significant variations in happiness levels among different countries and years.

4. **Economic Factors**:
   - The "Log GDP per capita," serving as an economic indicator, has a mean of approximately 9.40. There are missing values for 28 entries, possibly reflecting incomplete economic data for certain countries or years. The minimum GDP per capita logged is around 5.53, while the maximum is 11.68, suggesting disparities in economic development.

5. **Social Support**:
   - Averaging at 0.81, the "Social support" metric indicates a healthy perception of social ties and networks among respondents. This metric, which had 13 missing values, is crucial as social support has significantly positive effects on well-being.

6. **Health and Life Expectancy**:
   - The average "Healthy life expectancy at birth" is reported at about 63.4 years, with a standard deviation indicating notable disparities among countries. The data shows a range from just over 6 years to 74.6 years, highlighting vast differences in health outcomes.

7. **Freedom and Generosity**:
   - The "Freedom to make life choices" averages at approximately 0.75, indicating generally high perceived freedom among respondents. However, the "Generosity" scores are extremely low, averaging nearly zero and reflecting significant variability, with many values near or below zero, hinting at possible socio-economic tensions or a lack of philanthropic behavior in various regions.

8. **Corruption and Affect**:
   - The "Perceptions of corruption" measure shows an average score of around 0.74, with some entries indicating high perceptions of corruption affecting life satisfaction. The balance of "Positive affect" (average around 0.65) versus "Negative affect" (0.273) suggests a generally favorable emotional climate, although variations exist among different countries.

### Conclusion:
Overall, the dataset suggests that happiness is influenced by a complex interplay between economic conditions, social dynamics, health, and subjective well-being measures. Countries with higher GDP per capita tend to exhibit higher life ladder scores, while social support and perceived freedom appear to enhance happiness levels. However, issues like low generosity and high perceptions of corruption may hinder overall life satisfaction in certain regions. As such, this dataset provides valuable insights for policymakers and researchers interested in enhancing the well-being of populations by addressing gaps in economic and social structures. Further analysis could focus on filling in the missing values and exploring the causal relationships between these variables.

## Visualizations
![Visualization](happiness/heatmap.png)
