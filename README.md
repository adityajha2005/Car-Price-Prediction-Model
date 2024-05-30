
---

# Car Price Prediction Model

## Overview

This project aims to build a machine learning model to predict car prices based on various features such as brand, model, fuel type, mileage, seats, and owner type. The model uses linear regression for the prediction task.

## Installation

Ensure you have the #requirements.txt libraries installed
## Libraries Used

- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations.
- **matplotlib**: For plotting and visualization.
- **seaborn**: For enhanced data visualization.
- **scikit-learn**: For machine learning model building and evaluation.

## Project Structure

- `data/`: Directory to store datasets.
- `notebooks/`: Jupyter notebooks for exploratory data analysis and model building.
- `scripts/`: Python scripts for data processing, model training, and evaluation.
- `README.md`: Project documentation.

## Dataset

The dataset used in this project is https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho

## Data Preprocessing

Before training the model, the dataset needs to be preprocessed. This includes dropping unnecessary columns and encoding categorical variables.

### Dropping Columns

Unnecessary columns such as 'owner' can be dropped:

```python
data = data.drop(columns=['owner'])
```

### Encoding Categorical Variables

Convert categorical variables into numerical format using one-hot encoding:


## Model Training

Split the data into training and testing sets, and then train a linear regression model

## Model Evaluation

Evaluate the model 

## Visualization

Visualize the data and the model's performance using matplotlib and seaborn

## Conclusion

This project demonstrates how to build and evaluate a linear regression model to predict car prices. The evaluation metrics used R-squared score. Visualization techniques help in understanding the relationships between different features and the target variable.

## License

This project is licensed under the MIT License.

---
