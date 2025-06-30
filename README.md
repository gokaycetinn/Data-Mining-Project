
# 🌾  Comparing the Performance of Classification Algorithms for Predicting Grain Yield

## 📘 Objective
- To compare the performance of different algorithms.
- By comparing the performance of different machine learning algorithms, the model that provides
the highest accuracy was determined.


## 🧪 Algorithms Used

The following classification algorithms were applied and evaluated:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Naive Bayes
- Artificial Neural Networks (ANN)
- Random Forest 🌟 (best performer)
- Gradient Boosting
- AdaBoost
- Support Vector Machines (SVM)
- XGBoost

- ## 📊 Results

### 🏆 Top Performing Algorithms (Full Features):
| Algorithm         | Accuracy | AUC  |
|------------------|----------|------|
| Random Forest     | 78.45%   | 86%  |
| XGBoost           | 76.71%   | 86%  |
| Gradient Boosting | 75.77%   | 84%  |
| SVM               | 74.02%   | 85%  |

### ⚠️ With Selected Features:
- Gradient Boosting achieved the highest accuracy: **59.44%**
- Overall, performance dropped with fewer features, suggesting the value of full feature sets.

## 📈 Visualizations

- ROC curves for all models
- Confusion matrix for Random Forest
- Accuracy comparison bar chart

## 📁 Dataset

The project uses a dataset named `Data_processed.xlsx`, which contains various attributes related to soil properties and grain yield categories (A, B, C). All preprocessing was done using Python (pandas, sklearn).

##  👨‍💻  Team Members
- **Gökay Çetinakdoğan** (202111050)  
- **Hasan Emre Usta** (202111301)  

## Conclusions
- In this study, various machine learning classification algorithms were evaluated for their effectiveness in predicting grain yield. The dataset underwent preprocessing, including imputation of missing values, encoding of categorical variables, and standardization. Feature selection using SelectKBest identified 'VarietyClass_SDV' and 'DaysFromZerotoSowing' as the two most significant predictors.
