# Hill-Cipher

## Overview

This program implements the **Hill Cipher**, a polygraphic substitution cipher that encrypts and decrypts messages using linear algebra. It supports both encryption and decryption functionalities using matrix operations.

## Open in Google Colab

Click the button below to run the program directly in **Google Colab**:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leorasdsouza/INS-Lab-Programs/blob/main/Hill%20Cipher/Hill_Cipher.ipynb)

## Features

- Encrypts and decrypts plaintext using a **predefined key matrix**.
- Automatically **pads the plaintext** if necessary.
- Works with **uppercase English letters**.
- Implements **modular arithmetic** for encryption and decryption.

## How It Works
### Encyption Process:
1. The plaintext is **converted into numerical form** (A = 0, B = 1, ..., Z = 25).
2. The text is split into blocks matching the size of the key matrix.
3. The blocks are multiplied by the **key matrix** and taken modulo 26.
4. The resulting numbers are converted back to letters to form the **ciphertext**.

### Decrption Process:
1. The ciphertext is converted into numerical form.
2. The inverse of the key matrix (mod 26) is calculated.
3. The ciphertext blocks are multiplied by the inverse key matrix and taken modulo 26.
4. The resulting numbers are converted back to letters to retrieve the original plaintext.

## Usage Instructions

### Running the Program

#### **Option 1: Run in Google Colab**

Click the **"Open in Colab"** button above.

#### **Option 2: Run Locally**

1. Download the script `Hill_Cipher.py` from this repository.
2. Open a terminal or command prompt.
3. Run the following command:
   ```bash
   python Hill_Cipher.py
   ```
4. The program will output:
   - The **encrypted message**.
   - The **decrypted message**.

### Sample Output

![image](https://github.com/user-attachments/assets/f13607c5-de12-49fd-8e92-e3fda4f6c7d4)

![image](https://github.com/user-attachments/assets/24667f8b-5c2d-4e7a-a662-47f2aa02d99a)





