# Heart Disease Prediction

This project performs an analysis and prediction of heart disease using a dataset containing various health indicators. The goal is to predict the likelihood of heart disease based on patient data and visualize the key features.

## Dataset
The dataset used in this project contains health-related information such as age, cholesterol levels, blood pressure, and other features that can help predict heart disease.

### Columns:
- `Age`: The age of the patient.
- `Cholesterol`: The cholesterol level of the patient.
- `Heart Disease`: A binary column representing whether the patient has heart disease (1) or not (0).
- Various other features related to the health of the patient.

## Steps Involved
1. **Data Loading and Cleaning:**
   - Load the dataset and check for missing values.
   - Perform basic data cleaning if necessary.

2. **Exploratory Data Analysis (EDA):**
   - Perform data visualization using Seaborn and Matplotlib to identify patterns and correlations between features.
   - Plot heatmaps, histograms, and pair plots to better understand the data.

3. **Preprocessing:**
   - Use `StandardScaler` to scale the features.
   - Split the dataset into training and testing sets using `train_test_split`.

4. **Model Building:**
   - Implement a Logistic Regression model and Decision Tree Classifier to predict heart disease.
   - Evaluate the models using metrics such as accuracy and ROC-AUC score.
   - Visualize the confusion matrix for each model.

## Libraries Used
- `numpy`
- `pandas`
- `seaborn`
- `matplotlib`
- `scikit-learn`

## Visualizations
Several plots are used to better understand the dataset and the models:
- Correlation Heatmap
- Histograms
- Count Plots
- Confusion Matrix

## Model Performance
- Logistic Regression:
  - Train Score: *To be evaluated*
  - Test Score: *To be evaluated*

- Decision Tree Classifier:
  - Train Score: *To be evaluated*
  - Test Score: *To be evaluated*
  - ROC-AUC score is calculated for both train and test sets.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/SankarKarthi/Heart-disease-analysis.git
