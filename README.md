# Insurance Cost Prediction using PyTorch

## Overview

This project predicts individual medical insurance costs using a deep neural network built with PyTorch. The model is trained on demographic and health-related features such as age, BMI, smoking status, and region.

## Dataset

The project uses the Medical Cost Personal Dataset.

### Features

* Age
* Sex
* BMI
* Number of Children
* Smoker Status
* Region

### Target

* Insurance Charges

## Data Preprocessing

The following preprocessing steps were applied:

* Missing value inspection
* Categorical feature encoding
* Train / Validation / Test split
* Feature scaling using StandardScaler
* Log transformation applied to the target variable
* Outlier and distribution analysis

## Model Architecture

Neural Network implemented with PyTorch:

* Linear Layers
* ReLU Activation
* Batch Normalization
* Dropout Regularization
* He (Kaiming) Weight Initialization

## Training Configuration

* Optimizer: AdamW
* Loss Function: MSELoss
* Learning Rate Scheduling
* Early Stopping
* Batch Size: 32

## Results

Best Test Performance:

* MAE: 2676.22
* RMSE: 4962.93
* R2 Score: 0.8628

## Technologies Used

* Python
* PyTorch
* NumPy
* Pandas
* Scikit-Learn
* Matplotlib


## Future Improvements

* Feature Engineering
* Hyperparameter Tuning
* Learning Rate Scheduling Experiments
* Ensemble Models
* Advanced Regression Architectures

```
```
