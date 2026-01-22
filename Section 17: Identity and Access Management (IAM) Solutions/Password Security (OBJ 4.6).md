# Password Security – Exam Summary

## What Is Password Security?

Password security measures how well a password resists:

* **Guessing attacks**
* **Brute-force attacks**

Stronger passwords = **more attempts required** = **more time to crack**

---

## Where Password Policies Are Configured (Windows)

* **Local machine**: Local Group Policy Editor (`gpedit.msc`)
* Path:

  ```
  Computer Configuration
  → Windows Settings
  → Security Settings
  → Account Policies
  → Password Policy
  ```

---

## The 5 Password Policy Characteristics (VERY IMPORTANT)

Use the mnemonic **L-C-R-E-A**

**Length – Complexity – Reuse – Expiration – Age**

---

### 1. Password Length

* **Most important factor**
* Longer passwords increase security **exponentially**
* Recommended: **12–16+ characters**

📌 Example:

* 4-digit PIN = 10,000 combinations
* 8-digit PIN = 100,000,000 combinations

📌 Windows default max is **14**, higher requires enabling:

* *Relaxed minimum password length limits*

---

### 2. Password Complexity

Uses multiple character types:

* Uppercase letters
* Lowercase letters
* Numbers
* Special characters

📌 More character types = more combinations
📌 Example:

* `1234` → very weak
* `aW3+` → much stronger

📌 Windows has **built-in complexity rules**

---

### 3. Password Reuse

Avoid using:

* The same password on multiple sites
* Old passwords again on the same site

📌 Controlled by **Password History**

* Example: history set to **24**
* User must change password 24 times before reuse

📌 Reusing old passwords is risky because:

* They may already be cracked

---

### 4. Password Expiration

Requires password change after a set time (e.g., 90 days)

⚠️ Modern guidance (NIST):

* **Not recommended** unless password managers are enforced
* Leads to:

  * Weak incremental passwords
  * Password reuse

📌 Still commonly seen on exams → know how it works

---

### 5. Password Age

* **Minimum Password Age**: prevents rapid cycling
* Stops users from bypassing password history

📌 Example:

* Minimum age = 3 days
* User must wait 3 days before changing again

---

## Password Managers (Highly Recommended)

Password managers securely store and manage passwords.

### Key Features

1. **Password generation** – strong & unique
2. **Autofill** – fewer errors
3. **Secure sharing** – no password exposure
4. **Cross-platform access**

📌 Examples:

* Bitwarden
* 1Password
* Dashlane

---

## Passwordless Authentication (Modern Trend)

More secure + better user experience

### Common Passwordless Methods

* **Biometrics** (fingerprint, face)
* **Hardware tokens**
* **One-Time Passwords (OTP)**
* **Magic links**
* **Passkeys**

---

### Passkeys (Exam-Relevant)

* Passwordless authentication using **public-key cryptography**
* Private key stored on device
* Public key stored on server
* Protected by device unlock (PIN, face, fingerprint)

📌 Benefits:

* Phishing resistant
* No shared secrets
* No password reuse
* Strong security

---

## Final Exam Takeaways

* **Length > Complexity**
* Longer passwords = exponentially stronger
* Never reuse passwords
* Password history + minimum age work together
* Password managers greatly improve security
* Passwordless methods (especially passkeys) are the future

---

## One-Line Memory Aid

**“Long, complex, unique passwords—managed or replaced.”**

If you want, I can also:

* Turn this into **flashcards**
* Create **exam practice questions**
* Make a **one-page password policy cheat sheet**
* Compare **passwords vs MFA vs passkeys** in a table
