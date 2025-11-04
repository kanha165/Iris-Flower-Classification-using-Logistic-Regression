
#  Iris Flower Classification using Logistic Regression

This project demonstrates the use of **Logistic Regression**, a supervised machine learning algorithm, to classify iris flowers into three species — *Setosa*, *Versicolor*, and *Virginica* — based on their sepal and petal dimensions.

---

##  Overview

The Iris dataset is one of the most popular datasets in machine learning.  
In this project, we:
- Load and explore the Iris dataset from Kaggle (`iris_data.csv`)
- Train a **Logistic Regression** model using Scikit-learn
- Evaluate model performance
- Save the trained model as a `.pkl` file
- Build a test script to make new predictions using the saved model

---

##  Features

* Logistic Regression model trained using Scikit-learn  
* High accuracy (~95%) on test data  
* Reusable model saved as `model.pkl`  
* Separate prediction script (`test_model.py`)  
* Clean, well-structured project for beginners  

---

## 📂 Project Structure
📁 logistic regression/
│
├── .ipynb_checkpoints/       # Auto-saved Jupyter checkpoints
├── .gitignore                # Files to ignore in Git
├── iris.csv                  # Dataset (downloaded from Kaggle)
├── logistic_model.pkl        # Trained Logistic Regression model
├── README.md                 # Project documentation (for GitHub)
├── test_model.ipynb          # Notebook for testing saved model
└── train_model.ipynb         # Notebook for training & saving model

