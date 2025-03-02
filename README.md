# house-price-prediction-flask
A Flask-based web application that predicts house prices using a machine learning model. The app takes input features like the number of bedrooms, bathrooms, square footage, and location, and returns an estimated house price. Built with Flask, Scikit-Learn, Pandas, and NumPy.

---

# 🏡 **House Price Prediction App**  

## 📌 **Overview**  
This is a **Flask-based web application** that predicts house prices based on user inputs such as square footage, number of bedrooms (BHK), bathrooms, and location.  

### 🔥 **Key Features**  
✅ **User-friendly Interface** – Enter property details and get an estimated price instantly.  
✅ **Machine Learning Model** – Uses a trained model for accurate price predictions.  
✅ **Fast and Lightweight** – Built using Flask for quick API responses.  
✅ **Responsive UI** – Stylish frontend with a cityscape background.  

---

## 📸 **Screenshots**  

### 🟢 **Before Estimation**  
This is the input form where users enter the property details.  
![Before Estimation](docs/C_Before%20Estimation.png)  

### 🔵 **After Estimation**  
After clicking **Estimate Price**, the predicted price is displayed.  
![After Estimation](docs/C_After%20Estimation.PNG)  

---

## ⚙ **Setup & Installation**  

### 📌 **Prerequisites**  
Ensure you have the following installed on your system:  
- 🐍 **Python 3.x**  
- 📦 **pip** (Python package manager)  

### 🔧 **Installation Steps**  

1️⃣ **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/house-price-prediction.git
   cd house-price-prediction
   ```  

2️⃣ **Create a virtual environment (Recommended)**  
   ```bash
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate     # On Windows
   ```  

3️⃣ **Install required dependencies**  
   ```bash
   pip install -r requirements.txt
   ```  

---

## 🚀 **Running the Application**  

### **Step 1: Start the Backend (Flask Server)**  
Run the Flask app:  
```bash
python app.py
```  
🔹 This starts the backend API, usually at **`http://127.0.0.1:5000/`**.  

### **Step 2: Open the Frontend**  
- Open `index.html` manually in your browser.  
- OR use **Live Server** in VS Code for better experience.  

---

## 📂 **Project Structure**  
```
├── app.py               # Flask backend (API)
├── templates/
│   ├── index.html       # Frontend UI
├── static/
│   ├── styles.css       # CSS styles
├── dataset.csv          # Dataset used for training
├── ml_pipeline.ipynb    # Jupyter Notebook for ML model training
├── util.py              # Utility functions
├── requirements.txt     # List of dependencies
└── README.md            # Documentation
```

---

## 🎯 **How It Works**  

1️⃣ **User enters property details** – Square feet, BHK, bathrooms, and location.  
2️⃣ **Flask API processes the data** – It sends input to the trained ML model.  
3️⃣ **ML Model predicts the price** – The model calculates an estimated price.  
4️⃣ **Result is displayed on UI** – The predicted price appears on the webpage.  

---

## 🛠 **Technologies Used**  

✅ **Backend** – Flask (Python)  
✅ **Frontend** – HTML, CSS, JavaScript  
✅ **Machine Learning** – Scikit-learn, Pandas, NumPy  
✅ **Data Processing** – Pandas, NumPy  
✅ **Deployment** – Flask Web Server  

---