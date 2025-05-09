# 🏧 Java ATM Interface (Console-Based)

A simple console-based **ATM interface** application built using core Java. This project is designed for Java freshers to practice:

- Loops and Conditional Statements
- Switch-case control flow
- File Handling for balance persistence
- Basic authentication with a PIN

---

## 📋 Features

- ✅ PIN-based user authentication  
- 💰 Check balance  
- ➕ Deposit amount  
- ➖ Withdraw amount (with insufficient balance check)  
- 💾 Balance is saved to a file (`balance.txt`)  
- 🔁 Repeats until user exits

---

## 📂 File Structure

ATMInterface/
│
├── ATM.java # Main Java file with program logic
├── balance.txt # Stores the current balance
└── README.md # This file

yaml
Copy
Edit

---

## 🚀 How to Run

### 1. Compile the Java file

```bash
javac ATM.java
2. Run the application
bash
Copy
Edit
java ATM
🔐 Default PIN
The default PIN is: 1234

You can change it in the code if needed.

💡 Notes
If balance.txt does not exist, it will be created automatically with a default balance of 0.0.

All data is saved locally, no database is used.

🛠 Technologies Used
Java SE (Standard Edition)

File I/O (BufferedReader, FileWriter)

Console I/O (Scanner)

Control Structures






🚀 Made with ❤️ by [Venkatesh Inamanamelluru]

