# password_generator
This Python script generates a random password based on user input for the number of letters, symbols, and numbers to include. The generated password is then shuffled for added security.

## How to Use
- Run the script in a Python environment.
- You will be prompted to enter the desired number of letters, symbols, and numbers for your password.
- The script will generate a random password based on your input and shuffle the characters for increased security.
- The final password will be displayed on the console.

## Components
- random: Python module for generating random values.
- letters: List of lowercase and uppercase letters.
- numbers: List of numeric digits.
- symbols: List of special characters.
- nr_letters, nr_symbols, nr_numbers: User-input variables for the number of letters, symbols, and numbers in the password.
- password_letters, password_symbols, password_numbers: Substrings containing randomly chosen characters from the respective lists.
- password: Concatenation of the three substrings to form the initial password.
- password_list: Conversion of the password string into a list for shuffling.
- random.shuffle(password_list): Shuffling the characters of the password.
- shuffled_password: Concatenation of the shuffled characters to form the final password.

Example
```bash
Welcome to the PyPassword Generator!
How many letters would you like in your password?
8
How many symbols would you like?
3
How many numbers would you like?
4

Generated password: gP$2oL3NwI7D
```

** Feel free to customize the script according to your preferences or integrate it into your projects. Enjoy secure password generation! **
