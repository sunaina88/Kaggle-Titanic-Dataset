# **Titanic Survival Prediction**
A machine learning project predicting Titanic passenger survival using the Kaggle dataset.
## **Dataset**
891 passengers with features: Pclass, Sex, Age, SibSp, Parch, Fare, Embarked  
**Target** : Survived (0 = No, 1 = Yes)
 ## **Pipeline**
- Data cleaning & preprocessing (missing values, encoding, scaling)
- Exploratory Data Analysis
- Model training: Logistic Regression, Random Forest, SVM
- Hyperparameter tuning via GridSearchCV
## **Model**
| Model | Accuracy | Precision | Recall | F1-Score |
|:------|:--------:|:---------:|:------:|:--------:|
| Logistic Regression | 44.1% | 37.2% | 65.2% | 47.4% |
| Random Forest | 79.3% | 75.0% | 69.6% | 72.2% |
| SVM | 79.9% | 78.0% | 66.7% | 71.9% |
| **Tuned Random Forest** | **79.9%** | **72.0%** | **78.3%** | **75.0%** |

**Best Model** : Random Forest — chosen for highest recall, minimizing missed survivors.  
**Top features** : Sex (36.8%), Fare (18.1%), Age (12.8%), Pclass (11.1%), SibSp (3.7%)
## **Setup**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```
