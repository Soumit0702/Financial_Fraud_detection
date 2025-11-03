
Each file provides information about **customers, merchants, transactions, and anomalies**, forming a complete financial ecosystem for fraud analysis.

---

## Features

### Data Processing & Cleaning
- Merges multiple data sources by `CustomerID` and `TransactionID`
- Handles missing and timestamp data
- Outlier detection and statistical validation

### Feature Engineering
- **Temporal features:** hour, weekday, month, rush hours, weekends  
- **Account behavior:** login gaps, frequency indicators, session activity  
- **Amount features:** log/square transforms, z-scores, binning  
- **Anomaly-based features:** anomaly scores, ratios, and products  
- **Customer-level aggregations** and rolling statistics  

### Model Training & Evaluation
- Random Forest  
- Gradient Boosting  
- Decision Tree  
- Ensemble Voting Classifier  

### Performance Metrics
- Accuracy, Precision, Recall, and F1-score  
- Confusion Matrix & Feature Importance plots  
- Cross-Validation and Threshold Optimization  

---

## Technologies Used

| Category | Tools / Libraries |
|-----------|------------------|
| **Language** | Python 3.x |
| **Data Handling** | pandas, numpy |
| **Visualization** | matplotlib, seaborn |
| **Machine Learning** | scikit-learn, imbalanced-learn |
| **Statistical Analysis** | scipy |
| **Modeling** | RandomForestClassifier, GradientBoostingClassifier, DecisionTreeClassifier, VotingClassifier |

---

## How to Run

### Clone the Repository
```bash
git clone https://github.com/yourusername/financial-fraud-detection-system.git
cd financial-fraud-detection-system
