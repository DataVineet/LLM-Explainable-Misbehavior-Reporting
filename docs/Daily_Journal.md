# Daily Journal

## 13 July 2026

### Completed

- Repository structure created
- GitHub repository initialized
- Virtual environment configured
- VeReMi dataset downloaded
- Sample dataset (100k rows) created
- Dataset inspection completed

### Observations

- Total dataset size: 22,165,610 rows
- 21 original features
- Binary attack label available
- 19 attack categories
- No missing values observed

---

## 15–16 July 2026

### Completed

#### Exploratory Data Analysis

- Statistical summary completed
- Class distribution analyzed
- Attack type distribution analyzed
- Correlation heatmap generated
- Histograms created
- Boxplots created
- Outlier inspection completed
- Variance analysis completed
- Random Forest feature importance generated

#### Feature Engineering

Created new physical features

- Position Magnitude
- Speed Magnitude
- Acceleration Magnitude
- Heading Magnitude

#### Preprocessing

- StandardScaler applied
- Dataset normalized
- Stratified Train-Test Split
- Metadata generated
- Feature list exported
- Scaler saved
- Processed datasets saved

### Observations

- Dataset is nearly balanced
- No missing values
- No duplicate records
- Engineered features capture vehicle dynamics effectively
- Correlation among engineered features remains low
- Preprocessing pipeline is fully reproducible

### Next Task

Begin Machine Learning Model Development.

## 25 July 2026

### Completed

- Developed Logistic Regression baseline model.
- Evaluated baseline using Accuracy, Precision, Recall, F1-score and ROC-AUC.
- Developed Decision Tree classifier.
- Tuned tree hyperparameters to avoid overfitting.
- Generated feature importance rankings.
- Visualized the first three levels of the decision tree.
- Saved trained models and evaluation reports.
- Exported confusion matrices and feature importance plots.

### Key Findings

- Logistic Regression performed poorly because the relationship between features and attacks is highly non-linear.
- Decision Tree significantly improved Recall and F1-score while maintaining similar Accuracy.
- `rcvTime` emerged as the most influential feature, followed by positional and motion-based features.
- Decision Tree demonstrates better capability to capture complex decision boundaries in the VeReMi dataset.

### Next Task

- Train Random Forest classifier.
- Compare all baseline models.