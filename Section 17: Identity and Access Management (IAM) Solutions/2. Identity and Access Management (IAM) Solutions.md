# Identity & Access Management (IAM) – Exam Summary

## What is IAM?

**Identity and Access Management (IAM)** ensures:

> **The right person has the right access to the right resource at the right time for the right reason.**

IAM controls:

* User identities
* Authentication methods
* Permissions and access levels
* Monitoring and auditing of access

---

## Core Purpose of IAM

IAM helps organizations:

* Prevent unauthorized access
* Protect sensitive data
* Manage digital identities securely
* Support compliance and auditing

---

## The 4 Core IAM Processes (VERY IMPORTANT)

Use the mnemonic **I-A-A-A**

### 1. Identification

* User **claims** an identity
* Usually a **username or email**
* No verification yet

📌 *Example:* Entering your username

---

### 2. Authentication

* **Verifies** the identity claim
* Uses credentials (passwords, MFA, biometrics)

📌 *Example:* Entering a password or MFA code

---

### 3. Authorization

* Determines **what access** the user gets
* Based on roles, attributes, or policies

📌 *Example:* Can the user read, write, or delete files?

---

### 4. Accounting (Auditing)

* **Tracks and logs** user activity
* Used for:

  * Security monitoring
  * Compliance
  * Incident investigation

📌 *Example:* Log files showing login times and actions

---

## Key IAM Concepts You Must Know

### Provisioning

* Creating user accounts
* Assigning permissions

### Deprovisioning

* Removing access when no longer needed
* Critical for former employees

### Identity Proofing

* Verifying a user’s identity before account creation

### Interoperability

* IAM systems working across platforms and services

### Attestation

* Periodic review to confirm access is still appropriate

---

## Exam Domains Covered

This section supports:

* **Objective 2.4:** Analyze indicators of malicious activity
* **Objective 4.6:** Implement and maintain IAM solutions

---

## Topics Covered in This Section (Study Roadmap)

### 1. IAM Fundamentals

* Identification, Authentication, Authorization, Accounting
* Provisioning & deprovisioning

---

### 2. Multi-Factor Authentication (MFA)

Authentication factors:

* Something you **know**
* Something you **have**
* Something you **are**
* Something you **do**
* Somewhere you **are**

Implementations:

* Biometrics
* Hardware tokens
* Software tokens
* Security keys
* Passkeys

---

### 3. Password Security

* Password policy best practices
* Password managers
* Passwordless authentication (passkeys)

---

### 4. Password Attacks

Know these attack types:

* Password spraying
* Brute force
* Dictionary attacks
* Hybrid attacks

---

### 5. Single Sign-On (SSO)

* One login for multiple systems
* Technologies:

  * LDAP
  * OAuth
  * SAML

📌 *Benefit:* Convenience + centralized control

---

### 6. Federation

* Sharing identities across organizations
* One set of credentials for multiple domains

📌 *Example:* Logging into a partner’s system using your company account

---

### 7. Privileged Access Management (PAM)

Controls administrative access using:

* Just-in-time (JIT) access
* Password vaults
* Temporary (temporal) accounts

📌 *Goal:* Reduce standing admin privileges

---

### 8. Access Control Models (HIGHLY TESTED)

* **MAC** – Mandatory Access Control
* **DAC** – Discretionary Access Control
* **RBAC** – Role-Based Access Control
* **Rule-Based Access Control**
* **ABAC** – Attribute-Based Access Control

Also know:

* Time-of-day restrictions
* Principle of **Least Privilege**

---

### 9. Assigning Permissions

* Proper permission management
* Prevent privilege creep
* Align access with job roles

---

## One-Line Exam Memory Aid

**IAM = Identify → Authenticate → Authorize → Account**

---

## Final Exam Takeaways

* IAM is foundational to cybersecurity
* Authentication ≠ Authorization
* MFA strengthens authentication
* Least privilege reduces risk
* Logging and auditing are part of IAM
* Poor deprovisioning = major security risk
