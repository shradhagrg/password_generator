# PyPassword Generator
The PyPassword Generator is a Python program that generates strong and random passwords based on user-defined criteria. Users can specify the number of letters, symbols, and numbers they want in their password and the program will create a password accordingly.

## How to Use
1. Run the Python script `password_generator.py`.
2. Enter the desired number of letters, symbols, and numbers for your password.
3. The program will generate a random password that meets your criteria.

## Features
- Generates strong and random passwords for enhanced security.
- Allows users to customize the password length and composition.
- The code uses for loops to iterate through the desired number of characters for letters, symbols, and numbers from corresponding lists.
- Shuffles the generated characters using the random.shuffle() function, to enhance randomness.
- Provides an easy way to create complex passwords by concatenating characters (lowercase/uppercase letters, symbols, and numbers) from the shuffled password list.
