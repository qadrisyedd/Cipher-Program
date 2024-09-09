# README

## Security Pin Cipher

The **Security Pin Cipher** is a Python-based program that allows users to encrypt and decrypt messages using a 4-digit PIN. The program operates on lowercase alphabetical characters and uses a simple shift cipher mechanism for encryption and decryption.

## Features

- **Encrypt a Message**: Users can input a message and a 4-digit PIN to generate an encrypted cipher.
- **Decrypt a Message**: Users can decrypt a previously encrypted message by providing the correct 4-digit PIN.
- **Input Validation**: The program ensures that only lowercase letters are accepted and that the PIN is a valid 4-digit number.
- **User-friendly Interface**: The program provides easy-to-follow instructions and error handling.

## Program Flow

1. The user is presented with a menu to choose between encrypting a message, decrypting a message, or exiting the program.
2. The user selects an option:
   - **Option 1**: Encrypt a message by entering a lowercase message and a 4-digit PIN.
   - **Option 2**: Decrypt a message by entering the encrypted message and the correct 4-digit PIN.
3. After completing the chosen operation, the user can continue or exit.

## How to Run

1. **Install Python**: Ensure you have Python 3 installed on your system.
2. **Download the Script**: Clone or download this repository to your local machine.
3. **Run the Program**: Execute the Python script using the command:
   ```bash
   python security_pin_cipher.py
