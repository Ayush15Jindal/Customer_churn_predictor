# 📉 Customer Churn Prediction App

This interactive web app predicts whether a customer is likely to churn using a trained **Artificial Neural Network (ANN)** model. Built using **Streamlit**, the app provides a simple interface for telecom/customer service data-based predictions.

🔗 **Live App**:  
[👉 Try it here](https://ayush15jindal-customer-churn-predictor-main-hjuy0e.streamlit.app/)

---

## 🚀 Overview

Customer churn refers to when a customer stops doing business with a company. Predicting churn helps businesses take proactive steps to retain customers and reduce loss.

This app allows users to:
- Input customer demographic and service details
- Get real-time predictions on churn likelihood
- Understand how ANN-based models can help with customer retention strategies

---

## 📦 Project Structure

```
customer-churn-prediction/
│
├── main.py               # Streamlit app logic and UI
├── model.sav             # Pre-trained ANN model for churn prediction
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

---

## 🛠️ How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/customer-churn-prediction.git
   cd customer-churn-prediction
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the Streamlit app**
   ```bash
   streamlit run main.py
   ```

4. **Open your browser**
   - Visit: [http://localhost:8501](http://localhost:8501)

---

## 📚 Tech Stack

- **Streamlit** – for the interactive frontend
- **NumPy & Pandas** – data manipulation
- **Scikit-learn** – model training and preprocessing
- **Keras (TensorFlow backend)** – to build and save the ANN model

---

## 📄 Sample Use Case

A telecom company wants to identify customers at risk of leaving. Input fields such as contract type, internet service, tenure, and payment method are provided. The ANN model then predicts churn likelihood, helping decision-makers act early.

---

## 🙋‍♂️ Author

Developed by [Ayush Jindal](https://github.com/ayush15jindal)  
🔗 Streamlit: [Customer Churn App](https://ayush15jindal-customer-churn-predictor-main-hjuy0e.streamlit.app/)

---

## ✅ License

This project is open source and free to use under the [MIT License](LICENSE).
