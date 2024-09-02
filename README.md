# Mental Health in the Workplace: Impact Analysis and Predictive Modeling

This project focuses on analyzing the impact of mental health in the workplace, particularly the observed negative consequences for coworkers with mental health conditions. Using a dataset from a mental health survey, we preprocess the data, conduct exploratory data analysis (EDA), and evaluate various classification models to predict the likelihood of negative consequences in the workplace.

## Table of Contents

- [Dataset](#dataset)
- [Pre-processing](#pre-processing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Model Evaluation](#model-evaluation)
  - [K-Nearest Neighbors](#k-nearest-neighbors)
  - [Decision Tree](#decision-tree)
  - [Support Vector Machines](#support-vector-machines)
  - [Ensemble Learners Models (Bagging and Boosting)](#ensemble-learners-models-bagging-and-boosting)
- [Licenses](#licenses)
- [Contributors](#contributors)
- [Contact](#contact)

## Dataset

The dataset used in this project is a mental health survey focused on workplace conditions. Each feature in the dataset is described in detail in the `health_description.txt` file. The dataset file is named `survey.csv`.

### Target Feature
- **obs_consequence**: This feature captures whether the respondent has heard of or observed negative consequences for coworkers with mental health conditions in their workplace.

## Pre-processing

Pre-processing steps include:
- Handling missing data
- Encoding categorical variables
- Normalizing numerical features
- Splitting the dataset into training and test sets

## Exploratory Data Analysis (EDA)

Exploratory Data Analysis (EDA) is conducted to understand the distribution of the data, relationships between features, and the characteristics of the target feature (`obs_consequence`). Key visualizations and statistical summaries are included.

## Model Evaluation

The following classification models were evaluated to predict the target feature:

### K-Nearest Neighbors

- Evaluated using various values for k
- Performance metrics: Accuracy, Precision, Recall, F1-Score

### Decision Tree

- Hyperparameter tuning for tree depth, split criteria, etc.
- Performance metrics: Accuracy, Precision, Recall, F1-Score

### Support Vector Machines

- Experimented with different kernels (linear, RBF, etc.)
- Performance metrics: Accuracy, Precision, Recall, F1-Score

### Ensemble Learners Models (Bagging and Boosting)

- **Bagging**: Random Forest, Bagged Decision Trees
- **Boosting**: Gradient Boosting, AdaBoost
- Performance metrics: Accuracy, Precision, Recall, F1-Score

## Licenses

### Code

The code in this repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### Data and Other Non-Code Assets

The data and other non-code assets in this repository are licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. See the [LICENSE-data](LICENSE-data) file for details.

## Contributors

- [Arian Mohammadi](https://github.com/arianmohammadi)
- [Mina Mohammadi](https://github.com/minamohammadii)

This project was collaboratively developed by [Arian Mohammadi](https://github.com/arianmohammadi) and [Mina Mohammadi](https://github.com/minamohammadii).

## Contact

For questions or support, please reach out to [Mina Mohammadi](mailto:mina.mohamadi1996mm@gmail.com
).
