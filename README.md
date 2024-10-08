# PRODIGY_CS_01

## Task-01
Create a Python program that can encrypt and decrypt text using the Caesar Cipher algorithm. Allow users to input a message and a shift value to perform encryption and decryption 

# Caesar Cipher Encryption/Decryption

This Python program implements a simple Caesar Cipher for encrypting and decrypting text. The Caesar Cipher shifts the characters in the message by a certain number (called the "shift value"). It can handle both uppercase and lowercase letters, while non-alphabet characters (e.g., spaces, punctuation) remain unchanged.

## Features

- Encrypts messages using the Caesar Cipher.
- Decrypts messages that were encrypted with the Caesar Cipher.
- Handles both uppercase and lowercase letters.
- Non-letter characters (e.g., spaces, punctuation) remain unaffected.

## How It Works

1. **Encryption**: The characters in the input message are shifted forward by a specified number of positions in the alphabet.
2. **Decryption**: The characters are shifted backward by the same number to reveal the original message.

## Usage

To use the program, simply run the script, and follow the prompts to encrypt or decrypt a message.

### Example

```bash
$ python caesar_cipher.py
Caesar Cipher Encryption/Decryption
Would you like to (E)ncrypt or (D)ecrypt? E
Enter the message: Hello World!
Enter the shift value: 3
Encrypted Message: Khoor Zruog!

$ python caesar_cipher.py
Caesar Cipher Encryption/Decryption
Would you like to (E)ncrypt or (D)ecrypt? D
Enter the message: Khoor Zruog!
Enter the shift value: 3
Decrypted Message: Hello World!
