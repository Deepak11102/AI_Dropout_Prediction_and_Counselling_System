The AI-Based Student Dropout Prediction & Counseling System is a full-stack solution designed to help educational institutions:

Identify at-risk students early

Understand why a student is at risk using explainable AI (LIME)

Enable counselors to take timely corrective action

Automate communication with students via email + notifications

Support low-risk students with an AI-powered academic assistant

This system does NOT replace human counseling — it empowers counselors by providing:

✔️ Accurate dropout risk prediction (0–100)
✔️ Transparent LIME-based explanations
✔️ A centralized counselor dashboard
✔️ Automated meeting scheduling via email
✔️ Student profiles, attendance, GPA, fees & forum activity
✔️ A chatbot for low-risk students only, providing:

Academic help

Basic emotional support

Initial stress-level guidance

High-risk students always get routed to a human counselor.

🚀 Key Features
🧠 1. AI-Powered Dropout Prediction

Trained using XGBoost

Considers 5 major inputs:

Attendance %

GPA

Past failures

Fees dues

Sentiment score from forum posts

Produces a 0–100 dropout risk score

🔍 2. Explainable AI (LIME)

Counselors get clear reasons behind the predicted risk:

Attendance impact

Academic impact

Financial issues

Behavioral patterns

Forum sentiment

LIME provides:

Factor name

Condition

Weight

Impact (+Risk / Safe)

🧑‍🏫 3. Counselor Dashboard (NOT Faculty Dashboard)

View all registered students

Risk-based priority queue

Deep dive: full academic + personal profile

LIME risk explanation

Send alerts & schedule meetings

Email system via SMTP

Add new student pre-registrations

Counselor provides real human counseling.

🧑‍🎓 4. Student Dashboard

Each student can view:

Academic profile

GPA

Fee status

Attendance

Forum

AI assistant (low risk only)

🤖 5. AI Chat Assistant (Low-Risk Only)
✔ Offers:

General academic guidance

Study planning help

Motivation & basic emotional support

Initial guidance for stress or confusion

❌ Does NOT replace human counseling

High-risk students cannot access the chatbot.
They are routed directly to the counselor.

📧 6. Email Scheduling (SMTP-Based — Free)

Counselors can send:

Risk alert emails

Meeting invitations

Uses secure SMTP + App Password, no paid service needed.

🔐 7. Authentication & Authorization

Firebase Authentication

Student registration allowed only if pre-registered

Counselor signup also secured via pre-reg

Role-based routing

🔥 8. Realtime Database

Firebase Realtime Database

Auto-sync of:

Students

Forum posts

Updates

Profiles

Attendance

☁️ 9. Cloud Deployment
Backend

Python Flask deployed on Render Web Service

Frontend

HTML/CSS/JS deployed on Render Static Site

💻 Tech Stack
Frontend

HTML

CSS

JavaScript

html5-qrcode

Custom UI (no framework)

Backend

Python

Flask

XGBoost

Numpy / Pandas

LIME

Groq API (LLAMA 3.3)

Firebase Admin SDK

SMTP (Email)

Database

Firebase Realtime Database

Auth

Firebase Authentication

Deployment

Render Web Service (Backend)

Render Static Site (Frontend)

🧠 Model Details
Inputs

| Feature         | Description          |
| --------------- | -------------------- |
| Attendance %    | Commitment           |
| GPA             | Academic performance |
| Past failures   | Backlogs             |
| Fees Due        | Financial issue      |
| Sentiment Score | Emotional state      |

Risk Output

Range: 0 to 100

Categories:

Low Risk: 0–30

Medium Risk: 31–69

High Risk: 70–100

Interpretability

Uses LIME Regression Explainer

📧 SMTP Email System
Uses:

Gmail SMTP

App Password (not your actual password)

Features:

Sends:

Warning alerts

Counseling meeting invitations

No payment required.
🤖 Groq Chat Assistant

Model: LLAMA-3.3-70B

Context-aware

Provides:

Academic support

Basic emotional support

Motivation

Guidance

Disabled for high-risk students

🏗️ System Architecture

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/f5f54635-16d6-4312-9289-f5d682dd2c74" />

🏁 Conclusion

This system provides:

✔ Accurate dropout prediction
✔ Transparent explanations
✔ Real counselor intervention
✔ Smart AI support for low-risk cases
✔ Fully cloud-based scalable architecture

Perfect for colleges, universities & academic institutions.
