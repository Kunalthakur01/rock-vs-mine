# 🚢 Rock vs Mine Prediction using Machine Learning

A Machine Learning classification project that predicts whether an underwater object detected by SONAR is a **Rock (R)** or a **Mine (M)** using Logistic Regression.

## 📖 Project Overview

SONAR (Sound Navigation and Ranging) technology is widely used in submarines and underwater navigation systems.
When sound waves hit an underwater object, they bounce back and create reflected signals. By analyzing these reflected sonar signals, we can determine whether the object is:

- 🪨 Rock
- 💣 Mine

This project trains a Machine Learning model to classify underwater objects based on SONAR signal measurements.

---

## 🎯 Objective

Build a binary classification model that can accurately identify whether an underwater object is a rock or a mine.

---

## 📊 Dataset Information

The dataset contains:

- 208 observations
- 60 numerical sonar signal attributes
- 1 target column

Target Labels:

| Label | Meaning |
|---------|---------|
| R | Rock |
| M | Mine |

Each feature represents the energy of sonar signals reflected at different frequencies.

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-Learn
- Jupyter Notebook(google colab)

---

## 🤖 Machine Learning Model

### Logistic Regression

The Logistic Regression algorithm was used because:

- Binary classification problem
- Fast training
- Easy implementation
- Good performance on structured datasets

---

## 🔄 Project Workflow

### 1. Import Libraries
### 2. Load Dataset
### 3. Data Analysis
- Dataset inspection
- Shape analysis
- Statistical summary
### 4. Data Preprocessing
- Separate Features (X)
- Separate Target (Y)
### 5. Train-Test Split
Dataset split into:
- Training Data
- Testing Data



### 6. Model Training
```python
model = LogisticRegression()
```
### 7. Model Evaluation
Accuracy is calculated for:
- Training Data
- Testing Data
## Model Accuracy

![Accuracy](Screenshot_2026-06-07_154726.png)

### 8. Prediction System
The trained model accepts new SONAR readings and predicts:
```text
Rock
```
or
```text
Mine
```
---
## Prediction Output

![Prediction](Screenshot_2026-06-07_155348.png")
## 📂 Project Structure

```text
rock-vs-mine/
│
├── sonar_data.csv 
├──README.md
├── Rock_vs_mine_prediction.ipynb
```

---
## 🚀 How to Run on you system 

### Clone Repository

```bash
git clone https://github.com/Kunalthakur01/rock-vs-mine.git
```

### Install Dependencies

```bash
pip install numpy pandas scikit-learn
```

### Launch Notebook

```bash
jupyter notebook
```

Open:

```text
Rock_vs_mine_prediction.ipynb
```

---

## 🧪 Sample Prediction

Input:

```python
input_data = (...)
```

Output:

```text
The object is a Mine
```

or

```text
The object is a Rock
```

---

## 📚 Skills Demonstrated

- Data Analysis
- Data Preprocessing
- Feature Engineering
- Train-Test Split
- Logistic Regression
- Model Evaluation
- Machine Learning Prediction Systems

---

## 🔮 Future Improvements

- Random Forest Classifier
- Support Vector Machine (SVM)
- XGBoost
- Hyperparameter Tuning
- Streamlit Web Application
- Model Deployment

---

## 👨‍💻 Author

**Kunal Singh**

GitHub: https://github.com/Kunalthakur01

⭐ If you found this project useful, consider starring the repository.
