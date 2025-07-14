# PowerPulse-Household-Energy-Usage-Forecast

📌 PROJECT OVERVIEW:
PowerPulse explores energy consumption behavior of  household over several years. The project  detailed data preprocessing, exploratory data analysis (EDA), feature engineering, model training.

📂 DATASET:
Link: (https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption)

*KEY FEATURES:
Global_active_power
Global_reactive_power
Voltage
Global_intensity
Sub_metering_1, Sub_metering_2, Sub_metering_3
Date, Time

⚙️ TECHNOLOGIES USED:
Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
Models: Linear Regression, Random Forest, Gradient Boosting

🔍 PROJECT OVERFLOW:
* Handled missing values
* Boxplots and histograms to detect outliers
* Sub-metering analysis by zone (kitchen, laundry, heating)
* Correlation heatmap of power metrics
* Extracted features: hour, day, month, weekday, peak hours
* Model training and evalution

  📌 CONCLUSION:
  * The Sub-metering data helps identify appliance-level energy usage and Outliers were detected using boxplots
  * The four models are tried Linear Regression, Random Forest, Gradient Boosting, and Neural Networks
  * The Random Forest Regressor achieved the best overall performance and was selected as the final model for predicting global active power consumption


