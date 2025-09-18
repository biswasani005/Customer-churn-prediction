# 📊 Customer Churn Prediction & Analysis  

## 📌 Project Overview  
Customer churn is one of the biggest challenges for subscription-based and service-oriented businesses.  
This project focuses on predicting customer churn using **Deep Learning models** and analyzing the key factors that drive churn.  

The project demonstrates how businesses can proactively identify at-risk customers and take data-driven retention measures.  

##  Key Steps in the Project  
Exploratory Data Analysis (EDA)
  Identified important patterns, visualized churn distribution, and explored feature relationships.  
Modeling with Deep Learning (Keras Sequential Model)
  Built binary classification models with ReLU activation and Sigmoid output.  
Regularization:
  Added Dropout layers to prevent overfitting and improve generalization.  
Evaluation Metrics:
  Used Confusion Matrix and Accuracy Graphs to validate performance.  


## 🏗️ Model Building  

### Model 1 – Simple Sequential Model  
- Input: 12 nodes (ReLU) → Hidden: 8 nodes (ReLU) → Output: Sigmoid  
- Optimizer: Adam | Epochs: 150  
- Evaluated with Confusion Matrix & Accuracy plot.  

### Model 2 – With Dropout Layers  
- Same as Model 1 + Dropout (0.3 & 0.2).  
- Reduced overfitting, improved generalization.  

### Model 3 – Multi-feature Model  
- Features: Tenure, MonthlyCharges, TotalCharges.  
- Achieved higher accuracy compared to single-feature models.  


## 🛠️ Tech Stack  
- **Python
- **Pandas, NumPy, Matplotlib, Seaborn**  
- **TensorFlow / Keras 
- **Scikit-learn 


## 📈 Results  
- Best-performing model achieved strong accuracy in predicting churn.  
- Demonstrated the impact of contract type, payment method, and monthly charges on churn likelihood.  
- Provided actionable insights for customer retention strategie.



