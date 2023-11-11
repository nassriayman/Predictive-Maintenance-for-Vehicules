# Predictive-Maintenance-for-Vehicules
# Data-Driven Predictive Maintenance for Automotive Embedded Systems

## Project Overview
The goal of this project is to apply data science and machine learning techniques to the field of automotive maintenance. By analyzing sensor data from embedded systems within vehicles, we aim to predict maintenance needs and identify potential system failures before they occur.

## Contents
- [Data](#data)
- [Methodology](#methodology)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Data
The dataset includes various sensor readings from automotive systems such as engine RPM, lubrication oil pressure, fuel pressure, coolant pressure, and temperature readings. The 'Engine Condition' column is used as a label for predictive modeling.

## Methodology
1. **Data Preprocessing**: Scaling features using RobustScaler to mitigate the influence of outliers.
2. **Dimensionality Reduction**: Applying PCA to transform features into principal components.
3. **Anomaly Detection**: Using Isolation Forest to detect anomalies in sensor readings.
4. **Predictive Modeling**: Employing RandomForestClassifier to predict engine conditions.
5. **Evaluation**: Analyzing the model's performance with precision, recall, and f1-score metrics.

## Usage
To run the project, ensure you have Python 3.8+ installed along with the necessary packages:
- pandas
- numpy
- scikit-learn
- matplotlib (optional for plotting)

Run the Jupyter Notebooks in the following order:
1. `Predict_maint-checkpoint.ipynb`


## Results
The predictive model achieved an accuracy of 64.6% with a higher recall for the positive class (engine fault). Further improvements are planned by refining the anomaly detection process and experimenting with different machine learning algorithms.

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request to propose changes.



