 OTP-Verification-System

  🔐 OTP Verification System

A simple Python project that simulates an OTP (One-Time Password) verification process through the console. This project demonstrates user input handling, basic authentication logic, and modular programming in Python.

---

## 🚀 Features

- ✅ Generates a secure 6-digit OTP
- 📧 Simulates sending the OTP to a user’s email address
- 🔁 Allows up to 3 attempts for OTP verification
- 🔒 Provides access only on correct OTP input
- 🧩 Clean, modular, and reusable code using Python functions

---

## 🛠️ Tech Stack

- **Language:** Python 3
- **IDE:** PyCharm / VS Code / Jupyter Notebook
- **Libraries Used:** 
  - `random` (for OTP generation)
  - `input()` (for user interaction)

---

## 📁 Project Structure

otp_verification_system/ │ ├── otp_verification.py # Main Python script with full functionality ├── README.md # Project documentation

yaml
Copy
Edit

---

## 💡 How It Works

1. The system generates a random 6-digit OTP.
2. It simulates sending the OTP to a predefined email address.
3. The user is prompted to enter the OTP.
4. If the entered OTP matches the generated OTP, access is granted.
5. If not, the user has 2 more attempts before access is denied.

---

## 📸 Sample Output

Welcome to the OTP Verification System! Sending OTP to email: yamunagannina@gmail.com Generated OTP (for testing): 559105 Enter the OTP you received in your email: 559105 Access granted!

yaml
Copy
Edit

---

## 🔒 Security Note

- The OTP is printed on the console for demonstration/testing.
- In a real-world project, use an email API like SMTP, SendGrid, or Mailgun to send OTPs securely.

---

## 🧠 Concepts Covered

- Random number generation
- Function-based modular design
- Conditional logic
- Retry mechanism with user feedback
- Input validation

---

## 🔮 Future Improvements

- Integrate real email functionality using `smtplib`
- Add logging for security tracking
- Develop a GUI with Tkinter or a web-based version using Flask
- Implement time-limited OTP expiry

---

## 📧 Contact

**Created by:** Yamuna Gannina  
📩 Email: yamunagannina@gmail.com  
🔗 LinkedIn: [linkedin.com/in/yamuna-gannina-374945269](https://www.linkedin.com/in/yamuna-gannina-374945269)

