# Task 6: Create a Strong Password and Evaluate Its Strength

## 🎯 Objective
To understand what makes a password strong by creating multiple passwords with varying complexity, testing them using an online password strength checker, and summarizing best practices for secure password creation.

---

## 🧰 Tools Used
- [Password Meter](https://passwordmeter.com/)
- Web browser for testing
- Markdown for documentation

---

## 🔐 Passwords Tested

| Password           | Score (%) | Strength       | Time to Crack     | Tool Feedback |
|--------------------|-----------|----------------|-------------------|--------------|
| butterfly          | 9%       | Weak           | Instant           | Too short, lacks numbers, symbols, and uppercase |
| butterfly123       | 45%       | Weak-Medium    | Few seconds       | Lacks symbols & uppercase |
| ButterFly123       | 79%       | Medium         | Hours             | Could be longer |
| ButterFly@123      | 100%       | Strong         | Years             | Strong but could be longer |
| !SkyHorse92^Wave   | 100%      | Very Strong    | Centuries         | Excellent length & complexity |
| G7!pL0#r2WqT&8uB@  | 100%      | Very Strong    | Centuries         | Extremely strong random password |

*(Note: Replace scores & feedback with your real results from Password Meter.)*

---

## 📷 Screenshots
All test results are available in the [`/screenshots`](./screenshots) folder.

---

## 📚 What I Learned

### 1. What Makes a Password Strong?
- Length: At least 12–16 characters is recommended.
- Complexity: Use a mix of uppercase, lowercase, numbers, and special symbols.
- Unpredictability: Avoid dictionary words or personal information.
- Uniqueness: Never reuse passwords across accounts.

### 2. Common Password Attacks
- **Brute Force Attack**: Tries every possible combination.
- **Dictionary Attack**: Uses a list of common words & phrases.
- **Phishing**: Tricks users into revealing passwords.

### 3. Why Length Matters
The longer the password, the more combinations an attacker has to try, making brute force attacks exponentially harder.

### 4. Multi-Factor Authentication (MFA)
Adding MFA means even if a password is compromised, the attacker still needs another verification method (e.g., OTP, fingerprint).

### 5. Password Managers
They securely store and generate strong, unique passwords for all accounts.

### 6. Passphrases
Using a string of random words (e.g., `BlueTigerRuns@Midnight!`) can be both secure and easier to remember.

---

## ✅ Best Practices for Password Security
1. Use 12+ characters.
2. Combine uppercase, lowercase, numbers, and symbols.
3. Avoid personal information.
4. Use unique passwords for each account.
5. Enable MFA wherever possible.
6. Use a password manager to store credentials.

---

## 📂 Repository Structure

task-6-password-security/

│── README.md          # Documentation

│── screenshots/       # Screenshots from password strength tools

---

## 📌 Conclusion
This task demonstrated how password length, complexity, and unpredictability significantly increase security against common attacks.


