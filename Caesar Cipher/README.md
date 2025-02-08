# Caesar-Cipher

## Overview
This program implements the **Caesar Cipher**, a simple encryption technique that shifts each letter in the plaintext by a fixed number of positions in the alphabet. It provides both **encryption** and **decryption** functionalities.

## Open in Google Colab
Click the button below to run the program directly in **Google Colab**:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leorasdsouza/INS-Lab-Programs/blob/main/Caesar%20Cipher/CaesarCipher.ipynb)

## Features
- Encrypts text using a user-specified shift key.
- Decrypts the encrypted text to retrieve the original message.
- Supports both **uppercase and lowercase** letters.
- Preserves **non-alphabetic characters** (e.g., spaces, punctuation).

## How It Works
1. Each letter in the input text is **shifted forward** by `k` positions for encryption.
2. For decryption, each letter is **shifted backward** by `k` positions to restore the original text.
3. The shift wraps around the alphabet (e.g., shifting 'Z' by 1 results in 'A').

## Usage Instructions

### Running the Program
#### **Option 1: Run in Google Colab**
Click the **"Open in Colab"** button above.
#### **Option 2: Run Locally**
1. Download the script `CaesarCipher.py` from this repository.
2. Open a terminal or command prompt.
3. Run the following command:
   ```bash
   python CaesarCipher.py
3. Enter the required inputs when prompted:
   - A **text message** to encrypt.
   - A **numeric shift key** (e.g., `3`).
4. The program will output:
   - The **encrypted message**.
   - The **decrypted message** for verification.

### Sample Output
![image](https://github.com/user-attachments/assets/50c12e28-4422-4940-afc6-8552e2c93982)
![image](https://github.com/user-attachments/assets/38e578b1-c061-4fac-b48c-1f31fbd2e1d5)



