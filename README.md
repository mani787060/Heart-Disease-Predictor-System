# Heart Disease Predictor System  
Predicting Heart Disease using Logistic Regression | Machine Learning Project  

This project builds a **Heart Disease Prediction System** using the Logistic Regression algorithm.  
It uses patient medical attributes such as age, sex, chest pain type, blood pressure, cholesterol level, and more to classify whether a person is likely to have heart disease.

---

## Project Overview
- Load and explore the Heart Disease dataset  
- Perform basic data preprocessing  
- Split into training and test sets  
- Train a **Logistic Regression model**  
- Evaluate the performance using accuracy  
- Build a **Predictive System** to classify new inputs  

---

## Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn

## Machine Learning Algorithm Used
- **Logistic Regression** (Binary Classification)

Why Logistic Regression?
- Works well for medical datasets  
- Fast and interpretable  
- Provides probability estimates  

---

## Model Evaluation
- Train accuracy  
- Test accuracy  
- Prediction on custom user inputs  

if prediction[0] == 1:
    print("Person is likely to have Heart Disease.")
else:
    print("Person is healthy (No Heart Disease).")
