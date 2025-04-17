# 🪨 Rock or Mine Prediction using Machine Learning

> Turning sonar signals into smart predictions with Machine Learning.

## 📌 Overview

This project implements a machine learning classification model that predicts whether an object is a **rock** or a **mine** based on sonar signal data. The dataset, sourced from the UCI Machine Learning Repository, includes 60 numerical features representing sonar energy patterns reflected from different surfaces.

By applying supervised learning techniques, this project explores the performance of different classifiers and evaluates them using standard ML metrics. This task has real-world applications in areas such as **underwater object detection**, **military operations**, and **submarine navigation**.

---

## 📁 Files Included

- `sonar data.csv` — Dataset containing sonar signal data and object labels (`R` for Rock, `M` for Mine)
- `Rock Vs Mine.ipynb` — Jupyter Notebook with complete code for:
  - Data loading
  - EDA
  - Preprocessing
  - Model training & evaluation
  - Predictions

---

## 📊 Dataset Description

- **Source**: [UCI Machine Learning Repository – Sonar Dataset](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks))
- **Instances**: 208
- **Features**: 60 numeric attributes
- **Target**: 
  - `R` = Rock  
  - `M` = Mine

Each feature represents the energy of a sonar wave reflected off an object at a specific angle.

---

## 🧠 Machine Learning Workflow

1. **Data Preprocessing**  
   - Label encoding (R → 0, M → 1)  
   - Train-test split  
   - StandardScaler for normalization  

2. **Model Training**  
   - Algorithms used:  
     - Logistic Regression  
     - K-Nearest Neighbors (KNN)  
     - Support Vector Machine (SVM)  
     - Random Forest  

3. **Model Evaluation**  
   - Accuracy Score  
   - Confusion Matrix  
   - Classification Report  

4. **Prediction**  
   - User-defined input for sonar readings to predict class

---

## 🔧 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/Nishant8704/Rock-or-Mine-Prediction-using-Machine-Learning.git
   cd Rock-or-Mine-Prediction-using-Machine-Learning
2. launch Notebook
   jupyter notebook rock_or_mine_prediction.ipynb


📄 License
This project is licensed under the MIT License.
Feel free to use, modify, and distribute this project for educational or commercial purposes.

🙌 Acknowledgements
UCI Machine Learning Repository for the dataset

Scikit-learn documentation for guidance on model building and evaluation


💡 Author
Made with ❤️ by Nishant Raj
🔗 https://github.com/nishant8704
📫 Reach out:  https://www.linkedin.com/in/nishant-raj87/

