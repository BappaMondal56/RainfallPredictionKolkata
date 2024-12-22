# Rainfall Prediction in Kolkata (2022-2023)

This project aims to predict the daily rainfall categories in Kolkata for the year 2022-2023 based on historical weather data. The model utilizes machine learning techniques, specifically the Random Forest algorithm, to classify the weather into four categories: **Clear**, **Rain (Partly Cloudy)**, **Rain (Overcast)**, and **Overcast**.

## Dataset

The dataset consists of daily weather data from Kolkata for the year 2022-2023, with the following categories:

- **Clear**
- **Rain (Partly Cloudy)**
- **Rain (Overcast)**
- **Overcast**

The dataset includes various weather parameters such as temperature, humidity, wind speed, and pressure.

**Note**: The "Rain (Overcast)" category had only 5 instances, leading to an imbalance in the dataset. To address this issue, we applied **oversampling** techniques to balance the data for training.

## Model

The primary machine learning model used in this project is the **Random Forest** classifier. This model was chosen due to its ability to handle large datasets and capture complex relationships in the data.

- **Test Accuracy**: The model achieved an accuracy of **0.88** on the test dataset.

## Data Visualization

Several visualizations were created to explore the dataset and gain insights into the distribution of different weather conditions:

- **Histograms**: Show the distribution of different weather parameters (e.g., temperature, humidity).
- **Heatmaps**: Display correlations between various features.
- **Charts**: Visual representations of weather patterns over time.
- **Outlier Detection**: Identified and visualized outliers in the data to improve model accuracy.

## Key Steps in the Project

1. **Data Collection**: Acquired daily weather data for Kolkata (2022-2023).
2. **Data Preprocessing**: Cleaned and formatted the dataset, handling missing values and categorical variables.
3. **Handling Class Imbalance**: Oversampled the "Rain (Overcast)" category due to its small representation.
4. **Model Training**: Trained a Random Forest classifier on the preprocessed data.
5. **Evaluation**: Achieved a test accuracy of 0.88.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/BappaMondal56/RainfallPreditionKolkata.git
2. Install the required Python libraries:
  ```bash
  pip install -r requirements.txt
```
### Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn
### Conclusion
The project demonstrates the potential of machine learning for predicting weather categories based on historical data. The Random Forest model performed well, achieving a high accuracy despite the challenges posed by the imbalanced dataset.
   
