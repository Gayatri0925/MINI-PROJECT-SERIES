# Day 3 - Password Strength Checker

## Objective
Check password strength in real-time and provide security suggestions.

## Tech Stack
- Python 3
- Regular Expressions (`re` module)

## Files in this folder
- `password_strength_checker.py` → Python script to check passwords  
- `sample_output.txt` → Example outputs of password checks  

## Features
- Evaluates password as **Strong, Medium, or Weak**  
- Checks length, uppercase & lowercase letters, numbers, and special characters  
- Provides suggestions if password is not strong  
- Displays clear message if password is strong  

## How to Use
1. Run `password_strength_checker.py` in Python 3.  
2. Enter a password when prompted.  
3. View result and suggestions if applicable.  

## Example
Enter a password: Hello123
Result: 🟡 Medium Password

Suggestions:
Include special characters like @, #, $, %, &
Enter a password: StrongPass@2024
Result: ✅ Strong Password
Great! Your password looks strong and secure. 👍

## Learning Outcomes
- Understand password security best practices  
- Apply conditional logic and regex for text validation  
- Build a small, practical Python utility
