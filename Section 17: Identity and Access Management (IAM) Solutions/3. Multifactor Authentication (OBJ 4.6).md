# Multifactor Authentication (MFA) – Exam Summary

## What is MFA?

**Multifactor Authentication (MFA)** requires **two or more authentication factors from different categories** to verify a user’s identity.

**Purpose of MFA:**

* Create **layered security**
* Reduce unauthorized access
* Protect systems, networks, devices, and data

---

## The 5 Authentication Factors (VERY IMPORTANT)

Memorize with: **Know – Have – Are – Do – Location**

---

### 1. Something You Know (Knowledge Factor)

Information only the user should know:

* Password
* PIN
* Security questions

📌 Examples:

* Phone PIN
* Website password

⚠️ Multiple passwords or questions = **still single-factor**

---

### 2. Something You Have (Possession Factor)

A physical or digital item the user possesses:

* Smart card
* Hardware token (key fob, USB key)
* Software token (authenticator app)
* SMS or email one-time code

📌 Codes are usually **time-based (30–60 seconds)**
📌 Proves the user has the device

---

### 3. Something You Are (Inherence Factor)

Biometric identifiers unique to the user:

* Fingerprint
* Facial recognition
* Iris/retina scan
* Voice recognition

📌 Strong security
📌 Difficult to replicate or steal

---

### 4. Something You Do (Behavior Factor)

User behavior patterns:

* Keystroke dynamics
* Mouse movement
* Walking pattern
* Swipe/scroll behavior

📌 Newer factor
📌 Usually used as a **secondary factor**

---

### 5. Somewhere You Are (Location Factor)

User’s physical or network location:

* IP address
* GPS location
* Trusted network connection

📌 Example: Access allowed only from certain countries

---

## Types of Authentication

### Single-Factor Authentication (SFA)

* Uses **only one factor**
* Example: Username + password

📌 Username ≠ authentication factor
📌 Password + security questions = still **single-factor**

---

### Two-Factor Authentication (2FA)

* Uses **two different factor types**
* Example:

  * Password (know) + SMS code (have)
  * Smart card (have) + PIN (know)

📌 2FA **is a subset of MFA**

---

### Multifactor Authentication (MFA)

* Uses **two or more different factor categories**
* Can use 2, 3, 4, or all 5 factors

📌 More factors = more security
📌 More factors = less convenience

---

## Tokens (Common Exam Topic)

### Hardware Tokens

* Physical devices (key fobs, smart cards, USB keys)
* Generate codes or store certificates
* More secure, higher cost

### Software Tokens

* Authenticator apps
* SMS/email one-time codes
* Easier and cheaper to deploy

---

## Passwords & Password Managers

### Password Issues

* Hard to remember many passwords
* Reuse across websites
* Vulnerable to phishing

### Password Managers

* Generate unique, strong passwords
* Store them in an encrypted vault
* Improve security but **still rely on passwords**

---

## Passkeys (Passwordless Authentication)

### What Are Passkeys?

A **passwordless authentication method** using:

* Biometrics or device unlock
* Public-key cryptography

### How Passkeys Work

* **Private key** stored securely on the user’s device
* **Public key** stored on the server
* No shared secrets on the server

### Benefits

✔ Resistant to phishing
✔ Secure against data breaches
✔ Easier for users
✔ No password reuse

📌 Each passkey is **unique per service**

---

## Key Exam Takeaways

* MFA = **two or more different authentication factors**
* Username is **not** a factor
* Multiple passwords ≠ MFA
* 2FA ⊂ MFA
* Biometrics = *something you are*
* SMS codes = *something you have*
* Passkeys = **passwordless + cryptographic**

---

## One-Line Memory Aid

**“Know, Have, Are, Do, Location — use two or more for MFA.”**
