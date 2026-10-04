# 🎓 Student Performance Prediction & Analytics System

A full-stack Machine Learning web application that predicts student academic performance based on study hours, attendance, and previous scores.

Built using Flask, Scikit-learn, SQLite, and Bootstrap with an admin-style dashboard.

---

## 🚀 Features

- 📊 Machine Learning model (Random Forest)
- 🔢 Probability prediction (PASS / FAIL confidence %)
- 📈 Accuracy visualization graph
- 🗄️ SQLite database integration
- 🧾 Prediction history dashboard
- 🎨 Professional admin-style sidebar layout
- 🌐 Flask web application deployment ready

---

## 🧠 Machine Learning Workflow

1. Data preprocessing  
2. Feature scaling using StandardScaler  
3. Model training using RandomForestClassifier  
4. Model evaluation (accuracy score)  
5. Model persistence using Pickle  
6. Real-time prediction using Flask backend  

---

## 🛠️ Technologies Used

- Python
- Flask
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- SQLite
- Bootstrap 5
- HTML / CSS

---

## 📂 Project Structure

```
student_prediction/
│
├── app.py
├── train.py
├── requirements.txt
├── README.md
│
├── data/
│     └── student_data.csv
│
├── templates/
│     ├── layout.html
│     ├── index.html
│     ├── result.html
│     └── dashboard.html
│
└── static/
      └── accuracy.png
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/student-performance-prediction.git
cd student-performance-prediction
```

### 2️⃣ Create Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Train Model

```bash
python train.py
```

### 5️⃣ Run Application

```bash
python app.py
```

Open browser:

```
http://127.0.0.1:5000
```

---

## 📊 Model Performance

The model uses Random Forest classifier and displays:

- Prediction result  
- Confidence probability  
- Accuracy visualization graph  

---

## 🎯 Future Improvements

- User authentication system  
- Model comparison (Logistic Regression vs Random Forest)  
- Feature importance visualization  
- Deployment on cloud platform (Render / Heroku)  
- REST API version  

---

## 👨‍💻 Author

**Marpu Karthik**  

Final Year Computer Science Student  
Machine Learning & Full Stack Development Enthusiast  

---

⭐ If you like this project, give it a star!
