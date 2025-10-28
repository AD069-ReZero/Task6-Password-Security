# Password Strength Evaluation Results
**Intern Name:** Aritra Adak  
**Task:** 6 – Create a Strong Password and Evaluate Its Strength  
**Tool Used:** [PasswordMeter](https://www.passwordmeter.com)  

---

## 🧩 Objective
To analyze how password complexity (length, character variety, and unpredictability) affects password strength and resistance against attacks like brute-force and dictionary attacks.

---

## 🧠 Tested Passwords & Results

| No. | Password (for testing only) | Strength (%) | Feedback / Observations |
|:---:|:-----------------------------|:-------------:|:------------------------|
| 1 | **aritraadak** | 8% (Very Weak) | Contains only lowercase letters; short and predictable. |
| 2 | **AritraAdak** | 36% (Weak) | Mixed case but no numbers or special characters. |
| 3 | **Aritra12** | 59% (Good) | Includes numbers, but lacks symbols and longer length. |
| 4 | **@Aritra12** | 75% (Strong) | Excellent mix of upper, lower, digits, and symbols; good length. |
| 5 | **Aritra#!Tiger2025** | 100% (Very Strong) | Long passphrase, includes symbols and numbers; highly secure. |

---

## 📊 Screenshot Evidence
Screenshots for each test are saved in the `screenshots/` folder.
- screenshots/
├── 01_aritraadak.png
├── 02_AritraAdak.png
├── 03_Aritra12.png
├── 04_@Aritra12.png
└── 05_Aritra#!Tiger2025.png

---

## 🔍 Analysis

### 🔸 1. Effect of Length
- Longer passwords dramatically increase the time required for brute-force attacks.
- For example, a 10-character password can be cracked in hours, while a 16-character passphrase may take centuries.

### 🔸 2. Effect of Complexity
- Combining uppercase, lowercase, digits, and symbols increases randomness.
- Simple words or names (e.g., `aritraadak`) are easily found in dictionary attack lists.

### 🔸 3. Common Password Attacks
- **Brute Force Attack:** Systematically guesses every possible combination.
- **Dictionary Attack:** Uses precompiled wordlists of common passwords.
- **Hybrid Attack:** Combines dictionary words with numbers/symbols.

### 🔸 4. Security Best Practices
- Use passwords **at least 12–16 characters long**.
- Include **uppercase, lowercase, numbers, and special characters**.
- Avoid personal information or dictionary words.
- Use **passphrases** (e.g., “Aritra#!Tiger2025.png”) for easier memorization.
- Enable **multi-factor authentication (MFA)** for extra protection.
- Use a **password manager** to store complex passwords securely.

---

## 🏁 Conclusion
This experiment shows that:
- Password **length + complexity = higher security**.
- Short or predictable passwords are vulnerable to brute-force and dictionary attacks.
- Using **unique, random passphrases** and **MFA** provides the best defense against password cracking.

---

✅ **Outcome:** Gained a practical understanding of password creation, strength evaluation, and real-world password security best practices.

