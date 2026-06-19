PRODIGY_CS_03 - Password Complexity Checker

Overview

This project is a Password Complexity Checker developed using Python. It evaluates the strength of a password based on various security criteria such as length, uppercase letters, lowercase letters, numbers, and special characters.

Features

- Checks password length
- Detects uppercase letters
- Detects lowercase letters
- Detects numeric digits
- Detects special characters
- Provides password strength feedback

Technologies Used

- Python 3
- Regular Expressions (re module)

How It Works

The Password Complexity Checker evaluates the strength of a password by analyzing several security factors:

1. Checks whether the password contains at least 8 characters.
2. Verifies the presence of uppercase letters (A-Z).
3. Verifies the presence of lowercase letters (a-z).
4. Checks for numeric digits (0-9).
5. Detects special characters such as !, @, #, $, %, etc.

The program assigns a score based on these criteria and classifies the password as:

- Weak Password
- Medium Password
- Strong Password
- Very Strong Password

This helps users create more secure passwords and improve their account security.

Usage

1. Run the Python script.
2. Enter a password when prompted.
3. View the password strength result.

Examples

Example 1

Input:
hello

Output:
Password Strength: Weak Password

Example 2

Input:
Hello123

Output:
Password Strength: Strong Password

Example 3

Input:
Hello@123

Output:
Password Strength: Very Strong Password

Cyber Security Internship at Prodigy InfoTech
