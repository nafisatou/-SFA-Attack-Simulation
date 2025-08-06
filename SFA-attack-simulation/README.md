# 🛡️ SFA Attack Simulation – Flask + Keycloak

This project is part of an **authentication learning path**, simulating **pre-2015 login mechanisms** and evolving toward **modern identity management using Keycloak 26**.

It begins with a traditional username/password login flow in Flask and demonstrates common security pitfalls (e.g., session fixation). Later, it integrates with Keycloak to showcase how **modern Identity Providers (IdPs)** mitigate these issues with standards like **OIDC, MFA, and WebAuthn**.

The goal is to help developers understand **how classic authentication works**, **why it's vulnerable**, and **how to upgrade** securely using real-world tools like Keycloak.

---

## 🎯 What You'll Learn

- How traditional session-based login works
- Common attack surfaces (session fixation, cookie replay)
- Password hashing using bcrypt
- Basic web security flags (`HttpOnly`, `SameSite`)
- How to integrate a Flask app with **Keycloak**
- Basics of **modern SSO / OIDC flows**

---

## 📁 Project Structure

```bash
SFA-attack-simulation/
├── app.py                # Flask app with login & Keycloak integration
├── templates/
│   └── login.html        # Login form
├── static/               # (optional) CSS or images
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
