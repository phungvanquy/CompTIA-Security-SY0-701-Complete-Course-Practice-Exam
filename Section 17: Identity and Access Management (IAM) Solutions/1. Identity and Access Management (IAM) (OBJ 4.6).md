# Identity and Access Management (IAM) – Exam Summary

## What is IAM?

**Identity and Access Management (IAM)** ensures:

* **Right user**
* **Right resource**
* **Right time**
* **Right reason**

IAM balances **security** and **productivity** by controlling access to systems, data, and resources.

---

## The 4 Core IAM Processes (VERY IMPORTANT)

Memorize this order:

### **I → A → A → A**

**Identification → Authentication → Authorization → Accounting**

---

### 1. Identification

✔ User **claims an identity**

* Username
* Email address
* User ID

📌 Example: Entering a username when logging in
📌 Identification ≠ verification

---

### 2. Authentication

✔ **Verifies** the claimed identity

* Passwords
* PINs
* Biometrics
* MFA

📌 Example: Entering a password after username

---

### 3. Authorization

✔ Determines **what the user is allowed to do**

* Permissions
* Roles
* Access levels

📌 Example:

* HR → personnel files
* Finance → financial records

---

### 4. Accounting (Auditing)

✔ **Tracks and logs user activity**

* Logins/logouts
* Actions performed
* Changes made

📌 Used for:

* Incident detection
* Compliance
* Forensics

---

## Additional IAM Concepts (Exam-Relevant)

---

### 1. Provisioning

✔ **Creating** user accounts and assigning access

📌 Example:

* New employee gets email, network access, apps

---

### 2. Deprovisioning

✔ **Removing** access when no longer needed

📌 Example:

* Employee leaves → accounts disabled

⚠️ Prevents insider threats

---

### 3. Identity Proofing

✔ Verifying identity **before** account creation

* ID checks
* Trusted data sources
* Passport, driver’s license

📌 Confirms the user is who they claim to be

---

### 4. Interoperability

✔ Different systems working together securely

Uses standards such as:

* **SAML**
* **OpenID Connect**

📌 Enables single sign-on (SSO) and cross-platform access

---

### 5. Attestation

✔ **Reviewing and validating access rights**

* Regular audits
* Access reviews

📌 Ensures **least privilege**
📌 Confirms access is still appropriate

---

## Key Exam Takeaways

* IAM protects **data, systems, and networks**
* Identification comes **before** authentication
* Authentication verifies identity
* Authorization controls permissions
* Accounting provides visibility and evidence
* Provisioning = add access
* Deprovisioning = remove access
* Attestation = verify access is still correct

---

## One-Line Memory Aid

**“Identify → Verify → Permit → Track”**
