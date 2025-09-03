# 🔐 User Registration and Login System (Python)

This is a simple command-line Python application that allows users to register and log in securely. It uses file handling to store credentials and hashes passwords using SHA-256 for security. The system checks for strong passwords and prevents duplicate usernames.

---

## 💡 Features

- ✅ Register a new user
- 🔑 Login with existing credentials
- 🔒 Passwords are hashed using SHA-256
- ⚠️ Password strength validation (min 8 characters, uppercase, lowercase, digit, special character)
- 📁 User credentials are saved to `users.txt`
- 🛡️ Input validation and error handling
- 📌 Menu-based interaction (Register / Login / Exit)

---

## 📂 How It Works

1. **User Registration**
   - Prompts for a new username and password.
   - Checks that the password is strong using regex.
   - Checks that the username does not already exist.
   - Hashes the password and saves it in `users.txt`.

2. **User Login**
   - Prompts for username and password.
   - Hashes the input password and matches it against stored data.
   - Displays success or error message accordingly.

---

## 🚀 How to Run

1. Make sure you have Python 3 installed.
2. Save the code in a file called `user_system.py`.
3. Open a terminal or command prompt and run:

```bash
python user_system.py
