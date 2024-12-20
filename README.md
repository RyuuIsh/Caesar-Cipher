# Caesar-Cipher
A Python implementation of the Caesar Cipher, a simple encryption technique used in ancient Rome. Encode or decode messages by shifting letters in the alphabet. This program is interactive, user-friendly, and handles edge cases like non-alphabetic characters and large shift values.

## Features
- Encode and Decode: Encrypt or decrypt messages with a user-defined shift.
- Handles Non-Alphabetic Characters: Numbers, spaces, and symbols remain unchanged during encryption/decryption.
- Shift Normalization: Handles shift values greater than 26 using modulus arithmetic.
- User-Friendly Interface: Allows users to restart the program for multiple encryptions or decryptions.

## How it works
1. User Input:
- Choose to encode or decode a message.
- Enter the text and shift number.
2. Encryption/Decryption:
- Each letter in the text is shifted by the given amount.
- Non-alphabetic characters remain unchanged.
3. Restart Option:
- After processing, users can choose to restart the program or exit.

## Future Improvements
- Add support for uppercase letters.
- Implement a graphical user interface (GUI).
- Include other encryption algorithms for comparison.
