# Python-Password-Generator


Overview
This Python script generates a random password based on user input. You can specify the number of letters, numbers, and punctuation marks that should be included in the password. The script will then shuffle the characters to create a random password.


Features : 
Customizable Password Composition: Allows the user to decide how many letters, numbers, and punctuation marks to include.
Random Generation: Uses random.sample() to select a specified number of characters from each category (letters, numbers, punctuation).
Shuffling: The password characters are shuffled to make the password more secure.

How It Works

Input Parameters:
The user is prompted to enter how many letters, numbers, and punctuation marks they want in their password.
Character Selection:
Letters are chosen from string.ascii_letters, numbers from string.digits, and punctuation from string.punctuation.
Password Construction:
The chosen characters are combined, shuffled, and printed out to form the final password.

License
This project is licensed under the MIT License.
