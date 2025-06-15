# Insecure Feedback App (For Research Purposes Only)

This is the **insecure version** of the Secure Feedback App, built intentionally to demonstrate unsafe web development practices for academic comparison. It is used as part of a Master's research project on the role of security protocols and testing tools in web applications.

## ❗ Warning
> This application contains intentionally hardcoded secrets and insecure code. It must **never be deployed in a production environment**.

---

## 🔍 Purpose

This version is designed to:
- Lack environment-based secret management (secrets are hardcoded).
- Allow potential SQL injection vulnerabilities.
- Use outdated or insecure coding practices.
- Provide a baseline for analysis using **Bandit** and **Docker Scout**.

---

## ⚙️ Features

- Google OAuth login with hardcoded client ID and secret.
- Feedback form that stores user input in an insecure PostgreSQL setup.
- No input sanitization or password hashing.
- Secrets exposed in the source code.
- No `.env` file used.

---

## 🐍 Bandit & 🐳 Docker Scout

This version will be scanned using:
- **Bandit** for Python security issues.
- **Docker Scout** for container-level vulnerabilities.

The goal is to compare its results against the secure version of the app.

---

## 📂 Repository

GitHub: [https://github.com/20110145/insecure-feedback-app](https://github.com/20110145/insecure-feedback-app)

---

## 🔬 Research Context

This application contributes to the following research questions:
1. How do security protocols impact the development process of web applications?
2. What are the primary challenges developers face when integrating security protocols like OAuth and JWT?
3. How do security testing and audits contribute to the secure design and maintenance of web applications?

---

## 📚 Author

Muhammad Faizaan  
MSc Computing (Information Systems Processes)  
Southeast Technological University  
