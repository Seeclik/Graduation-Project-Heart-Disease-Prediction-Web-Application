# Heart Disease Prediction Web Application

## 📌 Project Overview
This project is a **Heart Disease Prediction Web Application** developed as a **Graduation Project**.  
The system leverages **Machine Learning models** to predict the likelihood of heart disease and provides two different usage modes tailored for distinct user groups:

- **PRO MODE**: Designed for healthcare professionals.
- **BASIC MODE**: Designed for the general public.

The application includes a secure **login system** and displays the **prediction probability instantly** after data submission.

---

## 🎯 Objectives
- Assist in early detection of heart disease risk.
- Provide an intuitive interface for both medical professionals and non-expert users.
- Demonstrate the practical use of machine learning in healthcare applications.
- Compare simplified input-based prediction versus professional-level detailed prediction.

---

## 🧠 Machine Learning Models
The project contains **two independent ML models**, each optimized for its target audience:

### 🔹 PRO MODE
- Intended for **doctors and healthcare professionals**.
- Uses **detailed clinical features**.
- Provides **higher accuracy and deeper analysis**.
- Implemented in:  
  [ProMode.ipynb](https://github.com/Seeclik/Graduation-Project-Heart-Disease-Prediction-Web-Application/blob/main/ProMode.ipynb)


### 🔹 BASIC MODE
- Intended for **non-medical users**.
- Requires **simplified and minimal input data**.
- Focuses on **ease of use and accessibility**.
- Implemented in:  
  [BasicMode.ipynb](https://github.com/Seeclik/Graduation-Project-Heart-Disease-Prediction-Web-Application/blob/main/BasicMode.ipynb)

---

## 📊 Model Performance and Accuracy

### 🔹 PRO MODE
- **Best Performing Model:** XGBoost (XGBClassifier)
- **Best Accuracy Achieved:** 87%
- The PRO MODE model achieved the highest accuracy by utilizing detailed clinical features.
  XGBoost outperformed other tested models due to its ability to capture complex, non-linear relationships within clinical data, making it suitable for healthcare professionals and medical decision support.

### 🔹 BASIC MODE
- **Best Performing Model:** Random Forest Classifier
- **Best Accuracy Achieved:** 92%
- The BASIC MODE model achieved its highest accuracy using a Random Forest classifier despite relying on a simplified set of input features.
  The model provided strong predictive performance while maintaining ease of use and accessibility for general users.


---

## 🌐 Web Application Features
- User authentication (Login system).
- Separate interfaces for:
  - BASIC users
  - PRO users
- Real-time prediction results.
- Clean and user-friendly UI.
- Probability-based output instead of binary results.

---

## 🛠️ Technologies Used

### 🔧 Backend & Machine Learning
- Python
- Scikit-learn
- Pandas
- NumPy

### 🎨 Frontend
- HTML
- CSS
- JavaScript
---
### 📧 Contact
Created by

* **[Khalid Alammari]**
* **[Turki Lughbi]**
* **[Mohammed Hantool]**
* **[Hulayyil Faqiri]**




Connect with me on [Linkedin](https://www.linkedin.com/in/khalid-alammari-/)
 or Email [Khalid.A.Alammari@gmail.com]
