# Hill-Cipher

## Overview

This program implements the **Vigenère Cipher**, a method of encrypting alphabetic text using a series of Caesar ciphers based on letters of a keyword. It supports both encryption and decryption functionalities.

## Open in Google Colab

Click the button below to run the program directly in **Google Colab**:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leorasdsouza/INS-Lab-Programs/blob/main/Vigenère%20Cipher/Vigenere_Cipher.ipynb)

## Features

- Encrypts and decrypts plaintext using a **repeating key**.
- Ignores spaces in plaintext while preserving non-alphabetic characters.
- Works with **uppercase English letters**.

## How It Works
### Encyption Process:
1. The plaintext is converted to uppercase and spaces are removed.
2. A key is repeatedly cycled through for each letter in the plaintext.
3. Each letter is shifted forward based on the corresponding key letter.
4. The resulting letters form the **ciphertext**.

### Decrption Process:
1. The ciphertext is processed similarly, but letters are shifted backward using the key.
2. The original plaintext is reconstructed.

## Usage Instructions

### Running the Program

#### **Option 1: Run in Google Colab**

Click the **"Open in Colab"** button above.

#### **Option 2: Run Locally**

1. Download the script `Vigenere_Cipher.py` from this repository.
2. Open a terminal or command prompt.
3. Run the following command:
   ```bash
   python Vigenere_Cipher.py
   ```
4. The program will output:
   - The **encrypted message**.
   - The **decrypted message**.

### Sample Output

![image](https://github.com/user-attachments/assets/36242b72-81f5-473a-8e20-bc2b7d9e195c)

![image](https://github.com/user-attachments/assets/c6774e19-9114-4c96-bb09-d022a9f00d29)







