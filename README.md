# Titanic Passenger Survival Classification using TensorFlow

This project is a machine learning classification task to predict the survival of Titanic passengers based on various features such as age, gender, passenger class, and fare. The model is built using TensorFlow's Linear Classifier and trained on the Titanic dataset.

## Table of Contents
- [Project Overview](#project-overview)
- [Data](#data)
- [Model](#model)
- [Requirements](#requirements)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
The goal of this project is to build a binary classification model that predicts whether a passenger survived the Titanic disaster. The model is built using TensorFlow, and the dataset is preprocessed using `pandas`. Key steps include data exploration, feature engineering, model training, and evaluation.

## Data
The dataset used in this project is the classic Titanic dataset, which includes information such as:
- Passenger's age, gender, and class
- Fare paid and embarkation town
- Survival status (target variable)

The dataset can be obtained from the [Kaggle Titanic dataset](https://www.kaggle.com/c/titanic/data).

## Model
The model is a TensorFlow `LinearClassifier`, trained using the following features:
- **Categorical Features:** `sex`, `class`, `embark_town`, `alone`
- **Numeric Features:** `age`, `fare`

The dataset is split into training and evaluation sets, and input functions are created to feed data into the model. After training, the model is evaluated for performance on unseen data.

## Requirements
To run this project, you'll need the following Python libraries:
- TensorFlow
- Pandas
- Numpy
- Matplotlib (optional, for visualizations)

You can install the necessary packages using pip:
```bash
pip install tensorflow pandas numpy matplotlib
