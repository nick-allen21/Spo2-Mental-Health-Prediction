# Spo2-Mental-Health-Prediction
Over the past year, I have been part of Stanford's Snyder Lab aiding in their pursuit to predict mental health states via wearable technology. Using 718 participants, wearable data, and robust survey questionnaires, we have been using machine learning to predict a patients mental health state at a given point. I have primarily worked with SpO2 and Stress. This code can be generalized to all wearable signals and all mental health signals. 
## Methods
- Data preprocessing and cleaning
- Feature engineering 
- Linear Regression Models
- Binary Classification Models
## Setup
1. Clone the repository:
    ```sh
    https://github.com/nick-allen21/Spo2-Mental-Health-Prediction.git
    ```
2. Load the repository into code editor of your choice (recommend VS code)

3. Download the requirements script
    ```sh
    pip3 install -r requirements.txt
    ```
4. Edit the data paths to process your data. Ensure your starting CSVs are in the correct form



# Graphs

## 1 Day Before Survey
![1_before_with_0_total_data_0_pre_survey](graphs/1_before_with_0_total_data_0_pre_survey.png)
![1_before_with_40_total_data_0_pre_survey](graphs/1_before_with_40_total_data_0_pre_survey.png)

## 10 Days Before Survey
![10_before_with_0_total_data_0_pre_survey](graphs/10_before_with_0_total_data_0_pre_survey.png)
![10_before_with_40_total_data_50_pre_survey](graphs/10_before_with_40_total_data_50_pre_survey.png)

## 15 Days Before Survey
![15_before_with_0_total_data_0_pre_survey](graphs/15_before_with_0_total_data_0_pre_survey.png)
![15_before_with_40_total_data_50_pre_survey](graphs/15_before_with_40_total_data_50_pre_survey.png)

## 30 Days Before Survey
![30_before_with_0_total_data_0_pre_survey](graphs/30_before_with_0_total_data_0_pre_survey.png)
![30_before_with_40_total_data_50_pre_survey](graphs/30_before_with_40_total_data_50_pre_survey.png)

## Histogram
![30_day_avg_hist](graphs/30_day_avg_hist.png)
![All_data_his](graphs/All_data_his.png)

## Correlation Graphs
![Correlation between High Stress and Low Stress 3 day average pre check](graphs/Correlation_between_High_Stress_and_Low_Stress_3_day_average_pre_check.png)
![Correlation between High Stress and Low Stress 3 max - min pre check](graphs/Correlation_between_High_Stress_and_Low_Stress_3_max_-_min_pre_check.png)
![Correlation between High Stress and Low Stress 30 day average pre check](graphs/Correlation_between_High_Stress_and_Low_Stress_30_day_average_pre_check.png)
![Correlation between High Stress and Low Stress 30 max - min pre check](graphs/Correlation_between_High_Stress_and_Low_Stress_30_max_-_min_pre_check.png)
![Correlation between High Stress and Low Stress 7 day average pre check](graphs/Correlation_between_High_Stress_and_Low_Stress_7_day_average_pre_check.png)
![Correlation between High Stress and Low Stress 7 max - min pre check](graphs/Correlation_between_High_Stress_and_Low_Stress_7_max_-_min_pre_check.png)
![Correlation between High Stress and Low Stress 9 day average pre check](graphs/Correlation_between_High_Stress_and_Low_Stress_9_day_average_pre_check.png)
![Correlation between High Stress and Low Stress Day before check](graphs/Correlation_between_High_Stress_and_Low_Stress_Day_before_check.png)
![Correlation between High Stress and Low Stress PSS Score at check](graphs/Correlation_between_High_Stress_and_Low_Stress_PSS_Score_at_check.png)
![Correlation between High Stress and Low Stress avg Difference 3 days pre check](graphs/Correlation_between_High_Stress_and_Low_Stress_avg_Difference_3_days_pre_check.png)
![Correlation between High Stress and Low Stress avg Difference 7 days pre check](graphs/Correlation_between_High_Stress_and_Low_Stress_avg_Difference_7_days_pre_check.png)
![Correlation between High Stress and Low Stress days decreasing pre check](graphs/Correlation_between_High_Stress_and_Low_Stress_days_decreasing_pre_check.png)
![Correlation between High Stress and Low Stress days increasing pre check](graphs/Correlation_between_High_Stress_and_Low_Stress_days_increasing_pre_check.png)
![Correlation between High Stress and Low Stress ratio above below 30 check](graphs/Correlation_between_High_Stress_and_Low_Stress_ratio_above_below_30_check.png)
![Correlation between High Stress and Low Stress ratio above below 7 check](graphs/Correlation_between_High_Stress_and_Low_Stress_ratio_above_below_7_check.png)

## Difference Histograms
![Difference_from_30_hist](graphs/Difference_from_30_hist.png)
![Difference_from_30_last_7_hist](graphs/Difference_from_30_last_7_hist.png)
![PSS_hist](graphs/PSS_hist.png)
