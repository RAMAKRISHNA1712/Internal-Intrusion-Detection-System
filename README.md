# Internal Intrusion Detection and Protection System (IIDPS)

A hybrid cybersecurity framework for detecting insider threats and malware attacks using **System Call Analysis**, **Machine Learning**, and **Malware API Monitoring**.

---

# 📌 Project Overview

Modern organizations face increasing risks from insider threats, credential misuse, and malware attacks. Traditional intrusion detection systems primarily focus on external threats and often fail to detect malicious activities performed by authenticated users.

This project introduces an **Internal Intrusion Detection and Protection System (IIDPS)** that combines:

- 🔍 System Call (SC) Analysis
- 🧠 Machine Learning based Behavioral Profiling
- 🦠 Malware API Call Monitoring
- ⚡ Real-Time Intrusion Detection

The system continuously monitors user behavior patterns and uploaded files to identify suspicious activities and malware attacks in real time.

---

# 🚀 Features

- 🔐 Insider threat detection using system call patterns
- 🧠 Machine learning based anomaly detection
- 🦠 Malware API call classification
- ⚡ Real-time intrusion alerts
- 📊 Behavioral profiling of users
- 🌐 Django-based web interface
- 📁 Secure logging and forensic analysis
- 📈 Accuracy comparison of ML models
- 🔔 Admin monitoring dashboard
- 🛡️ Real-time malware upload scanning

---

# 🏗️ System Architecture

The system consists of the following modules:

1. User Authentication & Session Monitoring
2. System Call Logging
3. Session-Based SC Mining
4. Behavioral Analysis
5. Malware API Call Analysis
6. Machine Learning Classification
7. Real-Time Alert Generation
8. Admin Dashboard & Monitoring

---

# 🛠️ Technologies Used

## Programming Languages
- Python

## Frameworks & Libraries
- Django
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Joblib

## Machine Learning Models
- Random Forest
- Support Vector Machine (SVM)
- Gaussian Naive Bayes

## Database
- MySQL

## Frontend
- HTML
- CSS
- JavaScript

---

# 📂 Project Workflow

```text
User Login
      ↓
Session Creation
      ↓
System Call Logging
      ↓
SC Pattern Mining
      ↓
Behavior Analysis
      ↓
Intrusion Detection
      ↓
Real-Time Alerts
```

### Malware Detection Workflow

```text
File Upload
      ↓
API Call Extraction
      ↓
TF-IDF Feature Extraction
      ↓
ML Classification
      ↓
Malware / Benign Prediction
      ↓
Alert Generation
```

---

# 🧠 Machine Learning Models

## Random Forest
- High accuracy malware classification
- Handles large datasets effectively
- Used as primary prediction model

## Support Vector Machine (SVM)
- Detects complex intrusion patterns
- Effective for high-dimensional data

## Gaussian Naive Bayes
- Fast probabilistic classification
- Lightweight and efficient

---

# 📊 Evaluation Metrics

The system evaluates model performance using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

# 💻 Hardware Requirements

- Windows 10 or above
- Intel i5 Processor or higher
- Minimum 8GB RAM
- 25GB Free Storage

---

# ⚙️ Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/IIDPS.git

cd IIDPS
```

## 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

## 3️⃣ Activate Virtual Environment

### Windows
```bash
venv\Scripts\activate
```

### Linux / Mac
```bash
source venv/bin/activate
```

## 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

## 5️⃣ Configure Database

Update MySQL credentials inside Django settings.

---

## 6️⃣ Run Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

---

## 7️⃣ Start the Server

```bash
python manage.py runserver
```

---

# 📁 Dataset

The project uses:
- Malware API Call Dataset
- System Call Logs
- User Session Data
- Intrusion Detection Datasets

Example datasets:
- NSL-KDD
- CIC-IDS2017
- UNSW-NB15

---

# 🧪 Testing

The project includes:

- Unit Testing
- Integration Testing
- Model Validation
- Performance Evaluation
- Real-Time Detection Testing

---

# 📷 Sample Outputs

- User Login Monitoring
- Intrusion Detection Dashboard
- Malware Prediction Results
- Accuracy Comparison Graphs
- Session Call Logs
- Admin Monitoring Panel

---

# 🔮 Future Enhancements

- Deep Learning based intrusion detection
- Cloud deployment support
- Real-time network packet analysis
- Multi-factor authentication integration
- AI-powered adaptive threat intelligence
- Zero-day attack detection

---

# 👨‍💻 Author

**Pathuri Rama Krishna**  
B.Tech – Computer Science & Engineering (Cyber Security)  
Institute of Aeronautical Engineering, Hyderabad

---

# 📜 License

This project is intended for academic and research purposes only.

---

# ⭐ Acknowledgement

Special thanks to the Department of CSE (Cyber Security), Institute of Aeronautical Engineering, Hyderabad, for their guidance and support throughout the project development.
