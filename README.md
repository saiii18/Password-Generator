# Password Generator

This Java Console Tool generates random passwords and checks their strength.

## Overview

I developed this project during the winter break of my third year, inspired by the Object-Oriented Effective Java Programming course. The idea for the project came when I was explaining the importance of strong passwords to my father. That’s when I decided to create a random password generator to apply my Java skills in a practical way. A week later, the project was complete!

In addition to generating passwords, I added a password strength checker to evaluate how secure the entered password is. Though the project was functional, I realized it wasn’t very user-friendly for beginners. In the future, I plan to improve the project by building a graphical user interface (GUI), which will be part of my Password-Services repository.

## Features

### 1. Password Generation

- Users can choose whether to include uppercase letters, lowercase letters, numbers, and symbols in the generated password.
- The length of the password is specified by the user.
- Based on these choices, a password alphabet is created.
- Random characters are selected from this alphabet to generate the password.
- The password is displayed in the console.

### 2. Password Strength Checker

The strength of the password is evaluated based on several factors:
- Use of uppercase letters.
- Use of lowercase letters.
- Use of numbers.
- Use of symbols.
- Password length of at least 8 characters (a common security minimum).
- Password length of at least 16 characters (often considered strong).

The tool then provides feedback on whether the password is weak, medium, strong, or very strong.

### 3. Password Security Tips

The tool also provides recommendations on how to create secure passwords, such as:
- Avoiding repeated characters and patterns.
- Avoiding dictionary words or common sequences.
- Not reusing passwords across multiple accounts.

## How to Use

 **Menu Options**:
   - Select `1` to generate a new password based on your preferred character types and desired length.
   - Select `2` to check the strength of an existing password.
   - Select `3` for useful tips on creating strong passwords.
   - Select `4` to exit the tool.

## Key Classes:

- **Alphabet Class**: Manages the pool of available characters for password generation (uppercase, lowercase, numbers, symbols).
- **Generator Class**: Handles user interaction for password generation, strength checking, and displaying security tips.
- **Password Class**: Evaluates the strength of a password based on the character types used and the length of the password.
