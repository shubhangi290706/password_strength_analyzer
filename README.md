🔐 Password Security & Hashing Utility
A secure Python-based password utility that evaluates password strength, generates cryptographically secure password hashes, and verifies passwords using PBKDF2-HMAC-SHA256. This project demonstrates real-world cybersecurity concepts such as password validation, salting, hashing, and secure password comparison. It helps users understand how modern authentication systems securely store and validate passwords while also encouraging strong password practices through detailed strength analysis and improvement suggestions.
🚀 Features
* Password strength checker
* Common password detection
* Secure password hashing using PBKDF2-HMAC-SHA256
* Random salt generation using "os.urandom()"
* Secure password verification with "hmac.compare_digest()"
* Suggestions to improve weak passwords
* Clean and beginner-friendly Python implementation
🛠 Technologies Used
* Python 3
* "hashlib"
* "hmac"
* "os"
* "re"
📌 Password Strength Criteria
The program checks:
* Minimum password length
* Uppercase letters
* Lowercase letters
* Numbers
* Special characters
* Common weak passwords
▶️ How to Run
python password_security.py
📷 Example Output
Enter your password: MySecure@123

========== PASSWORD REPORT ==========
Strength : Strong (6/6)
Salt     : 8c9f3d...
Hash     : e1b7a4...

Verification Test:
Re-enter password: MySecure@123
Password verified successfully.
🔒 Security Concepts Used
* PBKDF2 key derivation
* SHA-256 hashing
* Random salt generation
* Constant-time hash comparison
* Password entropy evaluation
📂 Project Structure
password_security.py
README.md
🎯 Learning Outcomes
This project helps in understanding:
* Secure password storage techniques
* Authentication security fundamentals
* Password hashing best practices
* Basic cybersecurity implementation in Python
📜 License
This project is open-source and available for learning and educational purposes.
