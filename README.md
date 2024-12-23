# **Churn Prediction Using Decision Trees**  
> A data-driven approach to predict customer churn using DecisionTreeClassifier and hyperparameter tuning with GridSearchCV.  

![Churn Prediction](https://github.com/abhinishtiwari/Churn-Prediction-Using-Decision-Trees/blob/284c85a3a1634aadccbc0b1ddc9a7e7ef5096e7f/Churn%20Prediction%20Using%20Decision%20Trees.webp)

---

## **📌 Table of Contents**  
1. [Overview](#overview)  
2. [Key Features](#key-features)  
3. [Installation](#installation)  
4. [Usage](#usage)  
5. [Dataset](#dataset)  
6. [Results](#results)  
7. [Visualizations](#visualizations)  
8. [Technologies Used](#technologies-used)  
9. [Contributing](#contributing)  
10. [Contact](#contact)  

---

## **📋 Overview**  
This project focuses on predicting customer churn using a **Decision Tree Classifier**. The model leverages hyperparameter tuning with **GridSearchCV** for optimal performance and delivers insights via a confusion matrix, accuracy metrics, and visualizations.

---

## **✨ Key Features**  
- **Data Preprocessing**: Handles missing values and categorical encoding.  
- **Hyperparameter Tuning**: Uses GridSearchCV for finding the best parameters.  
- **Model Evaluation**: Includes precision, recall, F1-score, and accuracy metrics.  
- **Visualizations**: Confusion matrix, feature importance, and performance charts.  

---

## **🛠️ Installation**  

1. **Clone the repository**:  
   ```bash  
   git clone https://github.com/abhinishtiwari/churn-prediction.git  
   cd churn-prediction  
   ```  

2. **Set up a virtual environment**:  
   ```bash  
   python -m venv env  
   source env/bin/activate # For Linux/Mac  
   env\Scripts\activate    # For Windows  
   ```  

3. **Install dependencies**:  
   ```bash  
   pip install -r requirements.txt  
   ```  

---

## **🚀 Usage**  
1. Add your dataset to the `data` folder (e.g., `data/customer_churn.csv`).  
2. Run the main script:  
   ```bash  
   python churn_prediction.py  
   ```  
3. View the results and metrics in the terminal or as saved visualizations in the `outputs` folder.  

---

## **📂 Dataset**  
- This project uses a sample dataset containing:  
  - **Customer demographics**: Gender, Age, etc.  
  - **Subscription details**: No. of days subscribed, multi-screen usage, etc.  
  - **Target variable**: Churn (1 for churned, 0 for retained).  

Download the dataset or use your custom dataset by following the required format.  

---

## **📊 Results**  
- **Accuracy**: 82.34%  
- **Precision**: 80.12% (Churn = 1), 85.56% (Churn = 0)  
- **Recall**: 78.67% (Churn = 1), 86.29% (Churn = 0)  
- **Confusion Matrix**:  
  |              | Predicted: 0 | Predicted: 1 |  
  |--------------|--------------|--------------|  
  | **Actual: 0** | 1500         | 90           |  
  | **Actual: 1** | 120          | 290          |  

---

## **📈 Visualizations**  
The following visualizations are included in this project:  

### **1. Confusion Matrix**
![Confusion Matrix](https://github.com/abhinishtiwari/Churn-Prediction-Using-Decision-Trees/blob/4b5f9fd94b0f1bf2c427a9f8cba9c2400cf8276e/confusion_matrix.png)

### **2. ROC-AUC**
![ROC-AUC](https://github.com/abhinishtiwari/Churn-Prediction-Using-Decision-Trees/blob/4b5f9fd94b0f1bf2c427a9f8cba9c2400cf8276e/ROC-AUC.png)

---

## **💻 Technologies Used**  
- **Python**: Core language  
- **Libraries**:  
  - **Pandas**: Data manipulation  
  - **NumPy**: Numerical computations  
  - **Matplotlib & Seaborn**: Data visualization  
  - **Scikit-learn**: Machine learning algorithms  

---

## **🤝 Contributing**  
Contributions are welcome! Here's how you can help:  
1. Fork this repository.  
2. Create a new branch (`git checkout -b feature-name`).  
3. Commit your changes (`git commit -m "Add some feature"`).  
4. Push to the branch (`git push origin feature-name`).  
5. Open a Pull Request.  

---

## **📬 Contact**  
Feel free to reach out with any questions or feedback!  

- **Abhinish Tiwari**  
- 🌐 [GitHub Profile](https://github.com/abhinishtiwari)  
- 📧 [Email](mailto:abhinishtiwari02@gmail.com)  
- 💼 [LinkedIn](https://www.linkedin.com/in/abhinish-tiwari-945914260/)  
