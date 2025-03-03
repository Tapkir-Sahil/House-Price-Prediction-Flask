# house-price-prediction-flask
A Flask-based web application that predicts house prices using a machine learning model. The app takes input features like the number of bedrooms, bathrooms, square footage, and location, and returns an estimated house price. Built with Flask, Scikit-Learn, Pandas, and NumPy.

---

# 🏡 **House Price Prediction Using Flask**  

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
   git clone https://github.com/Tapkir-Sahil/House-Price-Prediction-Flask.git
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
├📂 Project Root
 ┣ 📂 docs                # Screenshots & documentation
 ┣ 📂 model               # Stores ML model & feature columns
 ┃ ┣ 📄 model.pickle      # Trained ML model
 ┃ ┗ 📄 feature_columns.json # Feature names used in the model
 ┣ 📂 static              # CSS, JS, images
 ┣ 📂 templates           # HTML files
 ┣ 📄 app.py              # Flask backend
 ┣ 📄 dataset.csv         # House Prediction Data
 ┣ 📄 ml_pipeline.ipynb   # ML model training
 ┣ 📄 util.py             # Utility functions
 ┣ 📄 README.md           # Project documentation
 ┣ 📄 .gitignore          # Ignored files
 ┗ 📄 requirements.txt    # Required dependencies

```

---

## 🎯 **How It Works**  

1️⃣ **User enters property details** – Square feet, BHK, bathrooms, and location.  
2️⃣ **Flask API processes the data** – It sends input to the trained ML model.  
3️⃣ **ML Model predicts the price** – The model calculates an estimated price using Linear Regression.  
4️⃣ **Result is displayed on UI** – The predicted price appears on the webpage.  

---

## 🛠 **Technologies Used**  

✅ **Backend** – Flask (Python)  
✅ **Frontend** – HTML, CSS, JavaScript  
✅ **Machine Learning** – Scikit-learn, Pandas, NumPy, Matplotlib  
✅ **Data Processing** – Pandas, NumPy  
✅ **Deployment** – Flask Web Server  

---

## 🏆 **Future Improvements**

🔹 **Enhance UI/UX** – Make the interface more interactive.
🔹 **Deploy Online** – Host the application on Heroku, AWS, or Render.

---