# 🔐 CryptLab

### Breaking Weak Password Security — Building Strong Defences

CryptLab is an interactive cybersecurity research platform that demonstrates how weak passwords and outdated hashing algorithms can be compromised through practical attack simulations, while showcasing modern password protection techniques powered by cryptography and machine learning.

---

## 🚀 What This Project Does

CryptLab allows users to:

* Generate realistic weak password datasets
* Hash passwords using MD5 and SHA-1
* Simulate Dictionary Attacks
* Simulate Brute-Force Attacks
* Analyze password entropy and patterns
* Detect weak passwords using Machine Learning
* Secure passwords with bcrypt and Argon2
* Validate password policies
* Visualize security metrics and attack results

---

## 🛡️ Security Concepts Demonstrated

### Offensive Security

* Password Cracking
* Dictionary Attacks
* Brute Force Attacks
* Hash Analysis
* Password Entropy Evaluation

### Defensive Security

* bcrypt Hashing
* Argon2 Hashing
* Salt Generation
* Password Policy Enforcement
* AI-Based Password Strength Detection

---

## 🧠 Machine Learning Component

A Random Forest classifier analyzes password characteristics and predicts whether a password is weak or secure based on multiple extracted security features.

The model helps users identify risky passwords before deployment in real-world systems.

---

## 📊 Key Findings

The experimental results demonstrate:

✅ 100% success rate against weak MD5-protected passwords

✅ 100% success rate against weak SHA-1-protected passwords

✅ Modern algorithms such as bcrypt and Argon2 significantly increase attack cost

✅ Password complexity remains one of the strongest defenses against offline attacks

---

## ⚙️ Tech Stack

* Python
* Streamlit
* Scikit-Learn
* bcrypt
* Argon2
* Pandas
* NumPy
* Matplotlib
* ReportLab

---

## 🏗️ Project Architecture

```text
User Input
     │
     ▼
Password Analysis
     │
 ┌───┴──────────────┐
 │                  │
 ▼                  ▼
Attack Engine   Defence Engine
 │                  │
 ▼                  ▼
MD5/SHA1      bcrypt/Argon2
 │                  │
 └──────┬───────────┘
        ▼
 Security Analytics
        ▼
 Streamlit Dashboard
```

---

## ▶️ Run Locally

```bash
git clone <repository-url>

cd cryptlab

pip install -r requirements.txt

streamlit run app.py
```

---

## 📚 Educational Purpose

This project was developed as part of an Information Security course to demonstrate both attack and defense mechanisms in password security.

All attacks are executed on synthetic datasets within a controlled environment.

---

## ⭐ Why CryptLab?

Most cybersecurity projects show either attacks or defenses.

CryptLab demonstrates both sides of the security lifecycle:

* How weak systems fail
* Why they fail
* How attackers exploit them
* How modern defenses mitigate those risks

This makes it an excellent learning platform for students, researchers, and cybersecurity enthusiasts.
