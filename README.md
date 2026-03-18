# Microsoft Entra ID IAM Lab

## 📌 Overview

Designed and implemented an IAM lab in Microsoft Entra ID to simulate real-world identity and authentication workflows.

The goal was to simulate a real-world environment by creating users, assigning roles, enforcing security controls, and analyzing authentication activity.

---

## 🧠 Skills Demonstrated

* Identity & Access Management (IAM)
* Role-Based Access Control (RBAC)
* Multi-Factor Authentication (MFA)
* Sign-in log analysis
* Authentication troubleshooting

---

## ⚙️ Lab Setup

* Created two user accounts:

  * Intern (standard user)
  * Manager (privileged user)

* Assigned roles:

  * Manager → Global Reader role

* Configured security:

  * Enabled MFA for privileged account

---

## 🔍 Authentication Analysis

The following login scenarios were tested and analyzed:

### ❌ Failed Login Attempt

Repeated occurrences of error 50126 could indicate password-guessing or user credential issues, which would require further investigation in a real SOC environment.

* Error Code: 50126
* Cause: Invalid username or password
* Insight: Demonstrates detection of incorrect credential usage

---

### ✅ Successful Login

* Normal authentication flow
* Insight: Confirms proper access configuration

---

## 📸 Screenshots

The screenshots below provide evidence of IAM configuration, RBAC role assignment, MFA enforcement, and authentication log analysis performed during the lab.

* IAM user creation
* RBAC role assignment
* MFA configuration
* Sign-in logs (failure, success, MFA)

---

## 🧠 Key Takeaways

* Learned how identity systems control access in cloud environments
* Gained experience analyzing authentication behavior
* Understood how MFA protects privileged accounts
* Practiced interpreting real login failure codes and patterns

---

## 🚀 Future Improvements

* Add Conditional Access Policies
* Simulate brute-force login attempts
* Expand to a hybrid environment (on-prem AD + Entra ID)
