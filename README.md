# **AI-Based Student Dropout Prediction & Counseling System**

The **AI-Based Student Dropout Prediction & Counseling System** is a full‑stack platform designed to help educational institutions:

- **Identify at‑risk students early**
- **Understand why** a student is at risk using **Explainable AI (LIME)**
- **Enable counselors** to take timely corrective action
- **Automate communication** with students via **SMTP email**
- **Assist low‑risk students** using an AI‑powered academic & emotional‑support assistant

> ⚠️ **This system does NOT replace human counseling — it empowers counselors.**
>
> High‑risk students are ALWAYS routed to a human counselor.

---

# 🚀 **Key Features**

## 🧠 **1. AI‑Powered Dropout Prediction**
- Trained using **XGBoost**
- Uses **5 major input features:** Attendance %, GPA, Past failures, Fees due, Sentiment score
- Outputs a **0–100 dropout risk score**

---

## 🔍 **2. Explainable AI (LIME)**
LIME provides counselors with transparent explanations:

| Attribute | Description |
|----------|-------------|
| **Factor Name** | Influencing factor |
| **Condition** | Actual student value |
| **Weight** | Contribution strength |
| **Impact** | +Risk / Safe |

---

## 🧑‍🏫 **3. Counselor Dashboard**
Counselors can:

- View all students  
- Monitor **Risk‑Priority Queue**  
- Analyze detailed profiles  
- See **LIME explanations**  
- Send alerts & schedule meetings via SMTP  
- Add pre‑registered students  

---

## 🧑‍🎓 **4. Student Dashboard**

Students can access:

- Academic profile  
- GPA  
- Fee status  
- Attendance  
- Forum sentiment  
- **AI assistant (low‑risk only)**  

---

## 🤖 **5. AI Chat Assistant (Low‑Risk Only)**

Assistant provides:

- Academic guidance  
- Study help  
- Motivation  
- Basic emotional support  
- Initial stress‑level guidance  

❌ **High‑risk students cannot use the chatbot.**

---

## 📧 **6. Email Scheduling (SMTP – Free)**

Counselors send:

- Risk alerts  
- Meeting invitations  

Uses **Gmail SMTP** with **App Password**.

---

## 🔐 **7. Firebase Authentication**
- Pre‑registration required  
- Secure login  
- Role‑based routing  

---

## 🔥 **8. Firebase Realtime Database**
Auto-syncs:

- Students  
- Forum posts  
- Profiles  
- Attendance  
- GPA  

---

## ☁️ **9. Cloud Deployment**
- **Backend:** Flask on Render Web Service  
- **Frontend:** HTML/CSS/JS on Render Static Site  

---

# 💻 **Tech Stack**

### **Frontend**
HTML, CSS, JS, html5-qrcode

### **Backend**
Python, Flask, XGBoost, Pandas, NumPy, LIME, Groq API, Firebase Admin SDK, SMTP

### **Database**
Firebase Realtime Database

### **Auth**
Firebase Authentication

---

# 🧠 **Model Details**

### **Inputs**
| Feature | Meaning |
|---------|---------|
| Attendance % | Learning commitment |
| GPA | Academic performance |
| Past Failures | Backlogs |
| Fees Due | Financial issue |
| Sentiment Score | Behavior/emotion |

### **Risk Levels**
- **Low:** 0–30  
- **Medium:** 31–69  
- **High:** 70–100  

---

# 🏗️ **System Architecture**
*(Insert your diagrams here)*

---

# 🏁 **Conclusion**
This system provides:

- ✔ Accurate dropout prediction  
- ✔ Transparent explanations  
- ✔ Real human counseling  
- ✔ Smart AI support for low‑risk students  
- ✔ Cloud‑based scalable deployment  

Suitable for **colleges, universities, and academic institutions**.

