# 🏦 C-Bank: Bank Account Management System in C
🚀 Effortless Bank Account Management via a Console-Based Application

C-Bank is a Bank Account Management System written in C, designed to efficiently handle essential banking operations via a simple console interface. This application enables users to create and manage bank accounts with ease, featuring functionalities such as account creation, deposits, withdrawals, balance inquiries, and account closure.

## 📌 Key Features
✔ **Account Creation** – Users can create new bank accounts by providing essential details such as account holder name, email, etc.<br>
✔ **Deposit Operation** – Allows users to deposit funds into their accounts while automatically updating the balance.<br>
✔ **Withdrawal Operation** – Enables users to withdraw money, ensuring the requested amount does not exceed the available balance.<br>
✔ **Balance Inquiry** – Users can check their real-time account balance at any time.<br>
✔ **Account Closure** – Accounts can be closed securely, provided there are no outstanding balances.<br>
✔ **Error Handling** – Prevents issues like insufficient funds, invalid inputs, and other errors.<br>
✔ **Data Persistence** – Account information is stored in files, ensuring that data remains intact even after restarting the application.<br>
✔ **Security Measures** – Basic password protection and secure file handling are implemented to safeguard sensitive user data.<br>

## 📂 Project Structure
```r
📦 c-bank
 ├── 📄 main.c           # Core application logic
 ├── 📄 account.h        # Header file for account-related functions
 ├── 📄 functions.c      # Implementation of bank operations
 ├── 📄 database.txt     # Storage file for account data
 ├── 📄 README.md        # Project documentation
 ├── 📄 Makefile         # Build automation (optional)
```
## ⚙️ Requirements
Ensure you have the following installed to run the project:

🔹 GCC Compiler (sudo apt install gcc on Linux/macOS)<br>
🔹 A C Development Environment (VS Code, CodeBlocks, etc.)<br>

## ▶️ How to Run the Project
### 1️⃣ Clone the Repository
``` bash
git clone https://github.com/your-username/c-bank.git
cd c-bank
```
### 2️⃣ Compile the Code
```bash
gcc main.c functions.c -o c-bank
```
### 3️⃣ Run the Application
```bash
./c-bank
```
## 🎯 How It Works
When you run the program, you will be presented with a menu-driven interface:<br>

1️⃣ **Create a New Account** – Enter details like name, email, and initial deposit. <br>
2️⃣ **Deposit Funds** – Add money to your account. <br>
3️⃣ **Withdraw Funds** – Securely withdraw money (ensures no overdrafts). <br>
4️⃣ **Check Balance** – View your current balance instantly.<br>
5️⃣ **Close Account** – Remove an account from the system if the balance is zero. <br>
6️⃣ **Exit Program** – Safely exit the application. <br>

## 🔥 Why Use C-Bank?
✔ Simple & Lightweight – No complex UI, just a fast and functional console app.<br>
✔ Data Persistence – Your account details are saved securely even after closing the program.<br>
✔ Beginner-Friendly – Ideal for learning C programming, file handling, and basic banking logic.<br>

## 💡 Contributors 
👩‍💻 El Hadifi Soukaina <br>
👨‍💻 El Guelta Mohamed-Saber <br>

## 🤝 Contributions & Feedback 
🔹 Found a bug? Have suggestions? Open an issue or submit a pull request!<br>
🔹 Let’s improve C-Bank together! 🚀<br>
📩 Contact us: 
- medsaberelguelta@gmail.com <br>
- soukaina.elhadifi@gmail.com <br>
