# Customer Churn Prediction using Artificial Neural Networks  

📌 Overview  
This project predicts whether a customer will churn (leave a service) using an Artificial Neural Network (ANN).  
The dataset contains customer demographics, account details, and usage patterns. The model learns hidden patterns and provides churn probabilities to help businesses reduce customer loss.  

🧠 Model Architecture  
- Input Layer: One neuron per feature after preprocessing  
- Hidden Layers: Dense layers with ReLU activation  
- Output Layer: Sigmoid activation for binary classification  
- Optimizer: Adam  
- Loss Function: Binary Crossentropy  
- Metric: Accuracy  

⚙️ Tech Stack  
- Python  
- TensorFlow / Keras  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib & Seaborn (for visualization)  

📊 Workflow  
1. Data Preprocessing  
   - Handle missing values  
   - Encode categorical variables (OneHotEncoding / LabelEncoding)  
   - Feature scaling (StandardScaler / MinMaxScaler)  

2. Model Training  
   - Build ANN with Keras Sequential API  
   - Compile using Adam optimizer and binary crossentropy  
   - Train on training set, validate on validation set  



🚀 Results  
- Achieved ~80% accuracy on test data  



 


