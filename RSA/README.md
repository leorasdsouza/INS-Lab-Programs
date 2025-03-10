# RSA Algorithm

## Overview

This program implements the RSA Algorithm, a public-key cryptographic system used for secure data transmission. It supports both encryption and decryption of numerical messages using modular arithmetic.

## Open in Google Colab

Click the button below to run the program directly in **Google Colab**:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leorasdsouza/INS-Lab-Programs/blob/main/RSA/rsa.ipynb)

## Features

- Generates public and private keys dynamically.
- Encrypts and decrypts messages using the RSA algorithm.
- Implements modular exponentiation for encryption and decryption.
- Uses greatest common divisor (GCD) to find the public key exponent.

## How It Works
### Key Generation:
1. Choose two prime numbers, p and q.
2. Compute n = p × q.
3. Compute φ(n) = (p-1) × (q-1).
4. Find an integer e such that 1 < e < φ(n) and GCD(e, φ(n)) = 1.
5. Compute d, the modular inverse of e mod φ(n).

### Encryption Process:
1. Convert the plaintext message into numerical form.
2. Compute the ciphertext using the formula:
  $ C = (M^e) mod n $
### Decryption Process:
1. Compute the original message using:
   $ M = (C^d) mod n $

## Usage Instructions

### Running the Program

#### **Option 1: Run in Google Colab**

Click the **"Open in Colab"** button above.

#### **Option 2: Run Locally**

1. Download the script `rsa.py` from this repository.
2. Open a terminal or command prompt.
3. Run the following command:
   ```bash
   python rsa.py
   ```
4. The program will output:
   - The **encrypted message**.
   - The **decrypted message**.

### Sample Output

![image](https://github.com/user-attachments/assets/3b9d860b-c418-4868-92d4-d99b027a5989)


![image](https://github.com/user-attachments/assets/e4c0f205-1e75-40eb-bc50-9e77af4703ca)






