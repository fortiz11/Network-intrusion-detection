
# Machine Learning-Based Network Intrusion Detection

## Project Overview

The goal is to develop and evaluate supervised machine learning models that can distinguish malicious network traffic from normal network traffic using network-flow characteristics.

We will compare multiple classification algorithms to evaluate their ability to identify potential network intrusions.

## Dataset

This project uses the **UNSW-NB15 dataset**, developed by the University of New South Wales (UNSW Canberra).

The dataset contains network traffic records representing normal activity and various types of cyberattacks.

**Dataset Source:** [UNSW-NB15 Official Dataset](https://research.unsw.edu.au/projects/unsw-nb15-dataset)

We are using the prepared training and testing datasets:

| Dataset | Records | Columns |
|---------|---------|---------|
| Training | 175,341 | 45 |
| Testing | 82,332 | 45 |

### Target Variable

The primary prediction target is `label`:

- `0` = Normal traffic
- `1` = Malicious traffic

## Machine Learning Algorithms

The following supervised learning algorithms will be implemented and compared:

1. **Logistic Regression** – A baseline classification model.
2. **Decision Tree** – A model that learns classification rules from network traffic features.
3. **Random Forest** – An ensemble model combining multiple decision trees.

### Evaluation Metrics

Model performance will be evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Tools and Technologies

- Python
- Jupyter Notebook
- Visual Studio Code
- pandas
- NumPy (planned)
- scikit-learn (planned)
- Matplotlib (planned)
- Git for version control

## Project Progress

### Completed

- [x] Acquired the UNSW-NB15 training and testing datasets.
- [x] Established the Python and Jupyter Notebook development environment.
- [x] Loaded the datasets using pandas.
- [x] Verified the dataset dimensions.
- [x] Initialized the Git repository for collaboration.

### Upcoming

- [ ] Explore the dataset and identify missing values.
- [ ] Clean and preprocess network traffic data.
- [ ] Encode categorical features.
- [ ] Train baseline classification models.
- [ ] Compare model performance.
- [ ] Analyze feature importance and model behavior.

## References

UNSW Canberra. (n.d.). *The UNSW-NB15 dataset*. https://research.unsw.edu.au/projects/unsw-nb15-dataset
