# Password Toolkit 🔐🛠️  

A two-part Python project for generating and evaluating passwords.  

- **`custom_password.py`** provides the core functionality:
  - `generate_password(length)` → creates a secure random password.
  - `check_strength(password)` → evaluates a password as **WEAK**, **MEDIUM**, or **STRONG**.  

- **`password_tool.py`** is a command-line interface (CLI) that lets users interactively:
  - Generate a new password of a chosen length.
  - Check the strength of an existing password.

---

## Usage  

Run the interactive tool with Python 3:  

```bash
python3 password_tool.py

Would you like to 'Generate' a new password, or 'Check' the strength of an existing password? Generate
Please enter the requested password length: 16
Your new password is gH8!@aRzQ1#mNp2W

Would you like to 'Generate' a new password, or 'Check' the strength of an existing password? Check
Please enter the password to be checked: Password123
Your password is WEAK.
