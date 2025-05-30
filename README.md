Logistic Regression on Breast Cancer Dataset with Threshold Tuning and ROC Analysis
This project demonstrates how to apply logistic regression to a classic binary classification problem — detecting malignant vs benign breast cancer tumors using the Breast Cancer Wisconsin dataset.

It includes:

Model training and evaluation

ROC curve plotting

Threshold tuning

Probability distribution visualization

📁 Dataset
We use the built-in Breast Cancer Wisconsin dataset from sklearn.datasets, which includes 30 features computed from digitized images of breast mass samples, labeled as:

0: Malignant (cancerous)

1: Benign (non-cancerous)

✅ Steps Covered
Load & Split Dataset

Splitting into train/test sets using train_test_split()

Feature Scaling

Standardizing the features using StandardScaler

Logistic Regression Model

Fitting the model using LogisticRegression

Probability Predictions

Getting prediction probabilities (predict_proba) for ROC and threshold tuning

Threshold Tuning

Changing the classification threshold to observe how precision and recall change

Manual control over decision threshold instead of default 0.5

ROC Curve

Visualizing the trade-off between True Positive Rate and False Positive Rate

Probability Histogram

Plotting the distribution of predicted probabilities to choose meaningful thresholds

📊 Visualizations Included
ROC Curve: To evaluate model performance over different thresholds.

Predicted Probability Histogram: Helps understand how confident the model is in its predictions.

Confusion Matrix at Tuned Thresholds: To show the effect of different thresholds on predictions.

⚙ Libraries Used
scikit-learn

matplotlib

numpy
