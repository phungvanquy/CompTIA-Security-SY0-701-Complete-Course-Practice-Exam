# Password Attacks – Exam Summary

## What Are Password Attacks?

Password attacks are techniques used by attackers to **guess, crack, or recover passwords** in order to gain unauthorized access.

---

## Main Types of Password Attacks (VERY IMPORTANT)

Use the mnemonic **B-D-S-H**
**Brute force – Dictionary – Spraying – Hybrid**

---

## 1. Brute Force Attack

**Tries every possible combination** of characters until the password is found.

* Example: A → B → C → … → Z → AA → AB → AC
* Very **thorough**
* Very **time-consuming and resource-intensive**
* Short passwords and PINs are extremely vulnerable

📌 Example:

* 4-digit PIN = **10,000 combinations**
* Easily cracked in minutes or seconds offline

### Mitigations

* Long passwords
* Complex passwords
* Account lockout policies
* MFA
* CAPTCHAs (for online attacks)

---

## 2. Dictionary Attack

**Uses a predefined list of common passwords**

* Originally real dictionary words
* Modern attacks use **hacker dictionaries**
* Includes variations using **Leet Speak**

  * Example: `P@$$w0rd`

📌 Effective against:

* Common passwords (password, admin, root)

📌 Less effective against:

* Long, unique, random passwords

### Mitigations

* Same as brute force:

  * Long & complex passwords
  * MFA
  * Account lockouts
  * CAPTCHAs

---

## 3. Password Spraying

**Tries a few common passwords across many accounts**

* Example: Try `Password1` on all users
* Avoids account lockouts
* Very effective in large organizations

📌 Relies on the assumption that **some users reuse weak passwords**

### Mitigations

* Unique passwords for each user
* MFA
* Strong password policies

---

## 4. Hybrid Attack

**Combines dictionary + brute force**

* Starts with a dictionary word
* Adds numbers or symbols
* Variations generated dynamically

📌 Example:

* Policy requires: *word + 6 numbers*
* Password: `fabulous617238`
* Attack: `fabulous000001 → fabulous999999`

📌 Faster than pure brute force for structured passwords

---

## Password Cracking Tools (Conceptual Knowledge)

### John the Ripper

* Popular password cracking tool
* Supports many hash types
* Uses:

  * Dictionary attacks
  * Brute force
  * Hybrid attacks

📌 Weak hashes (like MD5) are **easily cracked**
📌 Strong hashes + salt significantly reduce effectiveness

---

## Hashing & Salting (High-Level Exam Concept)

* **Hashing**: Converts passwords into fixed-length values
* **Salting**: Adds random data before hashing
* Prevents:

  * Rainbow table attacks
  * Simple dictionary lookups

📌 Never store plaintext passwords
📌 Use strong hashing algorithms (e.g., SHA-256 + salt)

---

## Key Defenses Against Password Attacks

✔ Long, complex, unique passwords
✔ Password managers
✔ Account lockout policies
✔ CAPTCHAs
✔ **Multifactor Authentication (MOST EFFECTIVE)**

📌 MFA protects even if the password is cracked

---

## Quick Comparison Table (Mental Model)

| Attack Type | Key Idea                  | Best Defense            |
| ----------- | ------------------------- | ----------------------- |
| Brute Force | Try all combos            | Long, complex passwords |
| Dictionary  | Common passwords          | Unique passwords        |
| Spraying    | Few passwords, many users | MFA, unique passwords   |
| Hybrid      | Word + variations         | Random passwords        |

---

## One-Line Exam Takeaway

**Password attacks exploit weak or reused passwords—long, unique passwords and MFA are the strongest defenses.**
