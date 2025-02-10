#  Prediction of Titanic Survivors using Random Forest

##  Project Overview
This project applies Machine Learning techniques to predict the survival of passengers on the Titanic. Using the **Random Forest Classifier**, we analyze key passenger features to determine their likelihood of survival. The dataset used is from **Kaggle's Titanic dataset**.

## Dataset Information
- **Source**: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)
- **Features Used**:
  - `Pclass` (Passenger Class)
  - `Sex` (Gender)
  - `Age`
  - `SibSp` (Number of siblings/spouses aboard)
  - `Parch` (Number of parents/children aboard)
  - `Fare`
  - `Embarked` (Port of Embarkation)
- **Target Variable**: `Survived` (1 = Survived, 0 = Did not survive)

##  Installation & Setup
To run this project, follow these steps:

### 1. Clone the Repository
```bash
git clone  https://github.com/vany-gr34/pediction-of-survivors-.git
cd pediction-of-survivors
```


### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run Jupyter Notebook
```bash
jupyter notebook
```

## Machine Learning Model
- **Algorithm Used**: Random Forest Classifier
- **Performance Metrics**:
  - Accuracy
  - Precision, Recall, and F1-score
  - Confusion Matrix


## Results & Insights
- Higher survival rates observed for **females and passengers in first class**.
- **Children** had a better chance of survival than adults.
- **Ticket price (Fare) and Embarkation point** had an impact on survival probability.

## Exploratory Data Analysis (EDA)
EDA was conducted to visualize:
- Correlation between features and survival.
- Distribution of age groups and survival.
- Impact of ticket fare on survival probability.

## Acknowledgments
- Kaggle for providing the Titanic dataset.
- Scikit-learn for machine learning tools.
- Matplotlib & Seaborn for data visualization.

##  Contributions
Feel free to fork the repository and submit pull requests! 


