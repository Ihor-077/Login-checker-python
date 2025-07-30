
# 🔐 Login Checker

A simple Python program that simulates a login system by checking if the username and password match preset values.

## 💡 What You'll Learn
- How to use `input()` for user data
- `if`/`else` conditions
- Variable comparison and logic
- How login logic works behind the scenes

## ▶️ How to Run
1. Run the script in a Python environment
2. Enter a username and password
3. See if access is granted or denied!

-------------------------------------------------------------

correct_username = "Thor"
correct_password = "GitHub"

username = input("Enter your username: ")
password = input("Enter your password: ")

if username == correct_username and password == correct_password:
print("Access granted")

else:
print("Incorrect username or password"')
