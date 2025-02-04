# COVID-19 Diagnosis Prediction Using Machine Learning

![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Python-blue) ![Status](https://img.shields.io/badge/Project%20Status-Completed-brightgreen)

## 📌 Overview
This project leverages **Machine Learning** to predict **COVID-19 infection outcomes** based on patient symptoms and demographic data. The goal is to enhance **early detection**, optimize **resource allocation**, and improve **healthcare efficiency**.

## 🚀 Features
- Predicts COVID-19 infection using **Logistic Regression, Decision Trees, Random Forest, and XGBoost**
- Data preprocessing includes **EDA, feature selection, and hyperparameter tuning**
- Implements **train-test splitting** for robust model evaluation
- Provides insights into **key symptoms** affecting diagnosis
- Scalable approach for future disease prediction models

## 📂 Project Structure
```
├── data/                # Dataset used for training/testing
├── models/              # Trained machine learning models
├── notebooks/           # Jupyter notebooks with analysis & visualization
├── scripts/             # Python scripts for data processing & training
├── README.md            # Project documentation (this file)
├── requirements.txt     # Dependencies and libraries
```

## 🛠️ Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, XGBoost
- **Data Storage**: MySQL (for structured patient records)
- **Model Evaluation**: Accuracy, Precision, Recall

## 📊 Model Performance
| Model                 | Accuracy |
|-----------------------|---------|
| Logistic Regression   | 93.14%  |
| Decision Tree        | 94.46%  |
| Random Forest       | 94.46%  |
| XGBoost Classifier  | 94.46%  |

## 🔬 Methodology
1. **Data Collection**: Patient symptom and demographic data
2. **EDA & Feature Engineering**: Data cleaning, correlation analysis, feature selection
3. **Model Training**: Multiple ML models trained & tuned for performance
4. **Evaluation**: Comparison of models using various performance metrics
5. **Deployment Considerations**: Scalability for predicting other diseases

## 📌 Key Insights
- **Cough, Fever, and Shortness of Breath** are strong indicators of COVID-19.
- **Decision Tree, Random Forest, and XGBoost** showed similar accuracy (94.46%).
- **Feature scaling & encoding techniques** improved model performance.
- **Potential for future applications** in detecting other infectious diseases.

## 🔗 References
- [Johns Hopkins University COVID-19 Dataset](https://github.com/CSSEGISandData/COVID-19)
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php)
- Research Papers on ML-based COVID-19 Diagnosis

## 📥 Installation & Usage
```bash
# Clone the repository
git clone https://github.com/your-username/covid19-ml-prediction.git
cd covid19-ml-prediction

# Install dependencies
pip install -r requirements.txt

# Run model training
python scripts/train_model.py
```

## 📢 Contributing
Contributions are welcome! Feel free to fork the repo, create a feature branch, and submit a PR. 

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

---
💡 **Like this project? Give it a ⭐ on GitHub!**
