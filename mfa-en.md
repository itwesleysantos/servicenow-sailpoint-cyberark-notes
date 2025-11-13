# 🔑 Multi-Factor Authentication (MFA)

Multi-Factor Authentication (MFA) is a cybersecurity discipline that **verifies a user's identity** by requiring **at least two distinct forms of proof (factors)**. MFA adds extra layers of protection beyond passwords alone, which are the most vulnerable factor and the most common cause of data breaches.

MFA is an essential part of Identity and Access Management (IAM) strategies. Even if a hacker steals a password, they will not have the second factor, which is much harder to compromise.

---

## 🛠️ Types of Authentication Factors

To be considered "true" MFA, the authentication must use **at least two different types** of factors, as this requires separate attack methods for each piece of evidence:

| Factor Type | What It Is (Example) | Vulnerability |
| :--- | :--- | :--- |
| **Knowledge** | Something the user *knows* (Password, PIN, Security Question). | Most vulnerable; obtained via phishing, malware, or brute-force attacks. |
| **Possession** | Something the user *has* (Smartphone, Hardware Token, Security Key). Generates One-Time Passwords (OTP) or requires a push notification. | Susceptible to physical theft or scams like SIM swapping and fatigue attacks. |
| **Inherence (Biometrics)** | Something *unique to the user* (Fingerprint, Facial features, Retina scan). | Harder to crack, but once compromised, cannot be easily changed. |
| **Behavioral** | Something the user *does* (Location, IP Range, Typing speed). | Can be copied or spoofed (e.g., using a VPN or a stolen trusted device). |

---

## 🔬 Advanced Concepts and Differentiation

* **Adaptive MFA (Risk-Based):** Uses **Artificial Intelligence (AI) and Machine Learning (ML)** to assess the risk of the login attempt in real-time. The riskier the situation (e.g., logging in from an unusual location), the **more factors** the user must provide. This improves the user experience by requiring multiple factors only in sensitive situations.
* **Passwordless MFA:** Eliminates the "Knowledge" factor because it is the most vulnerable, requiring only Possession, Inherence, and Behavioral factors (e.g., FIDO Passkeys + Biometrics).
* **MFA vs. 2FA:** **Two-Factor Authentication (2FA)** is a **subset of MFA** that uses exactly two factors. MFA can require two, three, or more factors.
* **MFA vs. SSO:** **Single Sign-On (SSO)** focuses on **convenience** (using one login for multiple applications), while MFA focuses on **security**. They are complementary, and modern SSO systems often require MFA.

---

## 🔗 Source

The information contained in this summary was compiled from the article published by **Matthew Kosinski** and **Jim Holdsworth** on **IBM Think**.

* **What is MFA (multifactor authentication)?:** https://www.ibm.com/br-pt/think/topics/multi-factor-authentication
