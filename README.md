# Support Ticket Classification System

## 📖 Overview

Customer support teams receive a large number of tickets every day. Manually categorizing and prioritizing these tickets can be time-consuming and inefficient.

This project uses Natural Language Processing (NLP) and Machine Learning to automatically classify support tickets into predefined categories and assign priority levels.

---

## 🎯 Objective

The objective of this project is to build a machine learning system that can:

- Analyze support ticket text
- Categorize tickets into topic groups
- Predict ticket priorities
- Improve customer support efficiency

---

## 🛠 Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Scikit-Learn | Machine Learning |
| TF-IDF Vectorizer | Text Feature Extraction |
| Logistic Regression | Classification Model |
| Jupyter Notebook | Development Environment |

---

## 📂 Dataset

The dataset contains customer support tickets along with their corresponding topic groups.

### Features

- Ticket Description
- Topic Group
- Priority Label (Generated)

### Target Variables

- Topic Group Classification
- Priority Classification

---

## 🔄 Project Workflow

### 1. Data Loading

- Imported dataset
- Checked dataset structure
- Examined missing values

### 2. Exploratory Data Analysis

- Analyzed topic group distribution
- Visualized category frequencies

### 3. Text Preprocessing

- Converted text to lowercase
- Removed punctuation
- Removed special characters
- Cleaned ticket descriptions

### 4. Feature Extraction

- Applied TF-IDF Vectorization
- Converted textual data into numerical vectors

### 5. Topic Group Classification

- Split dataset into training and testing sets
- Trained Logistic Regression model
- Predicted topic groups

### 6. Priority Generation

Priority labels were created using keyword-based rules:

- High Priority
- Medium Priority
- Low Priority

### 7. Priority Classification

- Trained Logistic Regression model
- Predicted ticket priorities
- Evaluated performance

### 8. Model Evaluation

Evaluation metrics used:

- Accuracy Score
- Classification Report
- Confusion Matrix

---

## 📊 Results

The machine learning models successfully classified support tickets into topic groups and predicted ticket priorities.

The system demonstrates how NLP and Machine Learning can automate ticket routing and prioritization, reducing manual effort and improving operational efficiency.

---

## 🚀 Future Improvements

- Implement advanced NLP models such as BERT
- Improve text preprocessing techniques
- Use larger real-world datasets
- Deploy the model as a web application
- Integrate with customer support platforms

---

## 📌 Conclusion

This project demonstrates how Natural Language Processing and Machine Learning can be applied to automate support ticket classification and prioritization.

The solution helps organizations improve ticket management, reduce response times, and enhance customer support efficiency.

---

## 👩‍💻 Author

Sasi Rekha Tungala

Machine Learning Intern – Future Interns
