# Dataset

## Source

The original credit card transaction dataset used for this project was obtained from Kaggle.

## Dataset Description

The project uses a processed and balanced version of the original dataset for binary fraud classification.

### Target Variable

| Value | Description |
|------:|-------------|
| 0 | Legitimate Transaction |
| 1 | Fraudulent Transaction |

## Preprocessing

The dataset was prepared before model development using the following steps:

- Data cleaning
- Missing value handling
- Feature standardization using StandardScaler
- Dataset balancing
- Train-test split
- Data reshaping for Deep Learning models (CNN and LSTM)

## Purpose

The processed dataset enables fair comparison between multiple Machine Learning and Deep Learning algorithms for fraud detection.

> **Note:** The original dataset is publicly available on Kaggle. The version used in this project was preprocessed for research and educational purposes.
