# Feistel-Cipher

## Overview

This program implements a **Feistel cipher** for encrypting and decrypting binary representations of text using bitwise operations and a key.

## Open in Google Colab

Click the button below to run the program directly in **Google Colab**:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leorasdsouza/INS-Lab-Programs/blob/main/Feistel%20Cipher/Feistel_Cipher.ipynb)

## Features

- Converts plaintext into binary representation.
- Uses a Feistel-like structure for encryption.
- Applies bitwise operations (XOR) and binary addition for transformation.
- Decrypts the ciphertext back to plaintext.

## How It Works
### Encyption Process:
1. The plaintext is converted into an 8-bit binary representation.
2. The binary string is split into two halves.
3. A key is provided and converted into binary.
4. The right half is modified using binary addition with the key, followed by an XOR operation with the left half.
5. The halves are swapped, and another round of transformation is performed.
6. The final binary string is the ciphertext.

### Decrption Process:
1. The ciphertext undergoes the same process in reverse.
2. The original plaintext is reconstructed from the binary form.

## Usage Instructions

### Running the Program

#### **Option 1: Run in Google Colab**

Click the **"Open in Colab"** button above.

#### **Option 2: Run Locally**

1. Download the script `Feistel_Cipher.py` from this repository.
2. Open a terminal or command prompt.
3. Run the following command:
   ```bash
   python Feistel_Cipher.py
   ```
4. The program will output:
   - The **encrypted message**.
   - The **decrypted message**.

### Sample Output

![image](https://github.com/user-attachments/assets/9d5fa21a-aa7d-442a-ad8e-879c97a7ad5d)


![image](https://github.com/user-attachments/assets/e13dc418-50c3-4919-87a9-fddbc9005555)







