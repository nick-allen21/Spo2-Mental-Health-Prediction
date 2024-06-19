# Spo2-Mental-Health-Prediction
Over the past year, I have been part of Stanford's Snyder Lab aiding in their pursuit to predict mental health states via wearable technology. Using 718 participants, wearable data, and robust survey questionnaires, we have been using machine learning to predict a patients mental health state at a given point. Here is a small portion of my work where I have used machine learning models to deeply analyze the relationship between a mental health signal and a wearable device signal. I have primarily worked with SpO2 and Stress. This code can be generalized to all wearable signals and all mental health signals. 
## Methods
- Machine Learning
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

# Correlation Graphs

![Correlation between High Stress and Low Stress 3 day average pre check](graphs/Correlation%20between%20High%20Stress%20and%20Low%20Stress%203%20day%20average%20pre%20check.png)
![Correlation between High Stress and Low Stress 3 max - min pre check](graphs/Correlation%20between%20High%20Stress%20and%20Low%20Stress%203%20max%20-%20min%20pre%20check.png)
![Correlation between High Stress and Low Stress 30 day average pre check](graphs/Correlation%20between%20High%20Stress%20and%20Low%20Stress%2030%20day%20average%20pre%20check.png)
![Correlation between High Stress and Low Stress 30 max - min pre check](graphs/Correlation%20between%20High%20Stress%20and%20Low%20Stress%2030%20max%20-%20min%20pre%20check.png)
![Correlation between High Stress and Low Stress 7 day average pre check](graphs/Correlation%20between%20High%20Stress%20and%20Low%20Stress%207%20day%20average%20pre%20check.png)
![Correlation between High Stress and Low Stress 7 max - min pre check](graphs/Correlation%20between%20High%20Stress%20and%20Low%20Stress%207%20max%20-%20min%20pre%20check.png)
![Correlation between High Stress and Low Stress 9 day average pre check](graphs/Correlation%20between%20High%20Stress%20and%20Low%20Stress%209%20day%20average%20pre%20check.png)
![Correlation between High Stress and Low Stress Day before check](graphs/Correlation%20between%20High%20Stress%20and%20Low%20Stress%20Day%20before%20check.png)
![Correlation between High Stress and Low Stress PSS Score at check](graphs/Correlation%20between%20High%20Stress%20and%20Low%20Stress%20PSS%20Score%20at%20check.png)
![Correlation between High Stress and Low Stress avg Difference 3 days pre check](graphs/Correlation%20between%20High%20Stress%20and%20Low%20Stress%20avg%20Difference%203%20days%20pre%20check.png)
![Correlation between High Stress and Low Stress avg Difference 7 days pre check](graphs/Correlation%20between%20High%20Stress%20and%20Low%20Stress%20avg%20Difference%207%20days%20pre%20check.png)
![Correlation between High Stress and Low Stress days decreasing pre check](graphs/Correlation%20between%20High%20Stress%20and%20Low%20Stress%20days%20decreasing%20pre%20check.png)
![Correlation between High Stress and Low Stress days increasing pre check](graphs/Correlation%20between%20High%20Stress%20and%20Low%20Stress%20days%20increasing%20pre%20check.png)
![Correlation between High Stress and Low Stress ratio above below 30 check](graphs/Correlation%20between%20High%20Stress%20and%20Low%20Stress%20ratio%20above%20below%2030%20check.png)
![Correlation between High Stress and Low Stress ratio above below 7 check](graphs/Correlation%20between%20High%20Stress%20and%20Low%20Stress%20ratio%20above%20below%207%20check.png)



## Difference Histograms
![Difference_from_30_hist](graphs/Difference_from_30_hist.png)
![Difference_from_30_last_7_hist](graphs/Difference_from_30_last_7_hist.png)
![PSS_hist](graphs/PSS_hist.png)
