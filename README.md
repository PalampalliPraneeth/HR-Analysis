# 📊 HR Analysis

## 📂 Introduction

This project focuses on analyzing HR data to gain insights into factors affecting employee promotions. The dataset includes information such as education level, department, gender, recruitment channel, training scores, age, previous year ratings, KPIs met, awards won, and more.

## 🔍 Step 1: Collect Data

### Data
The project utilizes two datasets: `train.csv` and `test.csv`. The `train.csv` dataset contains information about employees, including their attributes and whether they were promoted or not. The `test.csv` dataset is used for making predictions based on the insights gained from the analysis.

## Installation
To run this analysis, you need to have R and the following libraries installed:

- `tidyverse`
- `dplyr`
- `ggplot2`
- `lubridate`
- `janitor`
- `readr`

### Clean Data
Duplicates are removed from the train data to ensure data integrity.

## 📈 Step 2: Analyze and Visualize Data

### Variables vs. Promotion
Visualizations are created to analyze various variables against promotion status, including:
- Education
- Department
- Gender
- Recruitment channel
- Number of trainings
- Average training score
- Age
- Previous year rating
- Length of service
- KPIs met >80%
- Awards won

## 💡 Step 3: Summary & Recommendation

### Summary
- Promotion focus is on employees with Bachelor's degrees or above.
- Top 5 departments with the most promotions are sales & marketing, operations, procurement, technology, and analytics.
- Promotion chances decrease after mid-40s.
- Employees with previous year ratings over 4 have more chances of promotion.
- Achieving over 80% of KPI requirements increases promotion chances.
- Training sessions with scores over 70 are recommended for promotion.

### Recommendations
1. **For Employees:**
   - Aim for Bachelor's degree or higher education.
   - Achieve over 70% in training scores.
   - Focus on departments with high promotion rates.
   - Maintain previous year ratings over 3 and aim for ratings over 4.
   - Meet over 80% of KPI requirements.

2. **For Employers:**
   - Reevaluate the role of awards in the promotion system.
   - Consider introducing a more detailed classification for recruitment channels.
   - Ensure training sessions focus on skill development rather than assessment.

## 🔚 Conclusion

This analysis provides valuable insights into factors influencing employee promotions. By understanding these factors, both employees and employers can make informed decisions to improve promotion rates and career growth opportunities.

## 🤝 Contributing 
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

