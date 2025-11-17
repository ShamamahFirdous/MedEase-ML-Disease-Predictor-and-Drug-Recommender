# 🌿 MedEase — ML-Driven Disease Prediction & Drug Recommendation System  
### 🏥 AI-Powered Symptom Analysis • Doctor Appointment Booking • ML Healthcare App

---

## 🔍 Overview
**MedEase** is an intelligent healthcare system built to predict diseases from user-entered symptoms and recommend appropriate medications—along with alternative drug suggestions.  
It also supports patient–doctor appointment booking and offers dedicated logins for **Admin**, **Doctors**, and **Patients**.

This system combines:
- ML-based Disease Prediction  
- Drug Recommendation  
- Patient & Doctor Login Panels  
- Appointment Booking System  
- Secure database-backed authentication  

---

## 🎯 Project Objectives
- Predict diseases using multiple ML algorithms.
- Suggest medicines based on predicted diseases.
- Provide alternative drug recommendations.
- Allow patients to book appointments with doctors.
- Provide doctors with a dashboard to manage appointments.
- Provide admin-level control for user management.

---

## 🧠 How the System Works

### 1️⃣ Patient Registration & Login  
- User signs up with name, number, username, password.  
- Login validates credentials from MySQL database.  
- After login → Patient Dashboard.
<img width="1280" height="683" alt="image" src="https://github.com/user-attachments/assets/4a19b0fa-f66a-4a21-996f-812d0d072681" />

### 2️⃣ Enter Symptoms  
- Patients enter multiple symptoms separated by commas.  
  Example:  
  ```
  fever, headache, vomiting
  ```
<img width="815" height="741" alt="image" src="https://github.com/user-attachments/assets/2311e228-bfd2-4e79-bbaa-45d62de93221" />

### 3️⃣ ML-Based Disease Prediction  
The system uses **ensemble ML models** to predict diseases:

| Model | Accuracy |
|-------|----------|
| Decision Tree | 82.18% |
| Naive Bayes | 86.17% |
| Random Forest | 88% |
| **Voting Classifier (Final Model)** | **95%** |

Prediction is based on processed symptom vectors from a Kaggle dataset.
<img width="1908" height="1164" alt="image" src="https://github.com/user-attachments/assets/3def4459-7327-4547-ba2a-0a5f1d0071d6" />

### 4️⃣ Drug Recommendation  
For each predicted disease:
- Primary medicine suggestions  
- Alternative drug recommendations  
- Information retrieved from MySQL backend  
<img width="1280" height="677" alt="image" src="https://github.com/user-attachments/assets/316e9282-d4f6-4fbd-92b2-76595ebaafec" />

### 5️⃣ Book an Appointment  
Patients can:
- Select doctor  
- Pick time slot  
- Submit appointment request  

### 6️⃣ Doctor Dashboard  
Doctors can:
- Log in  
- View patient appointments  
- Accept / reject / manage bookings  
<img width="1280" height="617" alt="image" src="https://github.com/user-attachments/assets/12a11309-82b7-417a-b69b-3be310dab1d4" />

### 7️⃣ Admin Panel  
Admin can:
- Manage patient accounts  
- Manage doctor accounts  
- Oversee entire system activities  
<img width="1117" height="575" alt="image" src="https://github.com/user-attachments/assets/8dfdcea8-372d-48ac-bdb5-cf884d61f226" />

---

## 🔐 Login Pages (Screens Summary)

### **Admin Login**
- Username + Password  
- Manages all system data  
- Controls doctors & patients  

### **Patient Login**
- Standard login  
- Can predict disease  
- Receive medications  
- Book appointments  

### **Doctor Login**
- Doctor-specific login  
- Able to view patient appointment requests  

---

## 📸 User Interface Screens  
- Admin Login Page  
- Patient Login Page  
- Doctor Login Page  
- Symptoms Input Page  
- Disease Prediction Output  
- Medicine Recommendation Page  
- Appointment Booking Page  
- Doctor Dashboard  

---

## ⚙️ Tech Stack

### **Frontend**
- HTML  
- CSS  
- JavaScript  

### **Backend**
- Python Flask  

### **Database**
- MySQL  

### **Machine Learning Libraries**
- sklearn  
- pandas  
- numpy  

---

## 📊 Dataset
Dataset Used:  
**Disease Prediction Using Machine Learning**  
Kaggle Link:  
https://www.kaggle.com/datasets/kaushil268/disease-prediction-using-machine-learning

---

## 🚀 Future Enhancements
- Add NLP-based symptom extraction  
- Use deep learning models  
- Integrate live tele-consultation  
- Add medication reminders  
- Expand drug knowledge base  
- Improve security & privacy compliance  

---

## 🙌 Contributors
- **Shamamah Firdous**  
- **Umar Javeed Altaf**  
- **Ayesha Siddiq**  

---

## 📜 License
Project developed for academic & research purposes.

---
