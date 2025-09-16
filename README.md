# Titanic-Survival-Prediction
Titanic Survival Prediction is a simple ML classification project to predict whether a particular passenger will survive the Titanic accident or not based on their age, class etc...

# Titanic Survival Prediction

## 🚀 Project Goal  
This project predicts survival of passengers from the Titanic disaster using machine learning.  
It uses a Logistic Regression model trained on Kaggle Titanic dataset.

---

## 🧱 Dataset  
- **Source:** Kaggle Titanic Dataset  
- Two files: `train.csv`, `test.csv`  

---

## 🔧 Data Preprocessing  
- Removed columns with too many nulls (`Cabin`)  
- Filled missing values in `Age` and `Embarked`  
- One-hot encoded categorical variables (`Sex`, `Embarked`)  
- Created new features:  
    - `FamilyMembers` = SibSp + Parch   

---

## ⚡ Model Training  
- Model used: Logistic Regression (`sklearn.linear_model.LogisticRegression`)  
- Train-Test split: 80% training, 20% validation  
- Evaluated with accuracy, confusion matrix, and classification report  

---

## ✅ Results  
- Validation Accuracy: ~[81]%  
- Confusion Matrix:  
    ([90 15]
     [20 54])  

---

## 📊 Final Prediction  
Predicted survival for unseen test dataset (from Kaggle competition).

---

## 📂 Repository Structure  
- `titanic_model.ipynb` → Complete Colab notebook  
- `train.csv`, `test.csv` → Dataset files  
- `submission.csv` → Predicted results  

---

## 📚 Learnings  
- Feature Engineering (FamilyMembers) improved model performance  
- Understanding one-hot encoding & dummy variable pitfalls  
- Practical end-to-end ML project from data to prediction  

---

## 🎯 Conclusion  
This project demonstrates basic but essential supervised learning concepts applied to a real-world dataset.  
