# Hill-Cipher

## Overview

This program implements the **Hill Cipher**, a polygraphic substitution cipher that encrypts messages using linear algebra. It supports **encryption** functionalities using matrix operations.

## Open in Google Colab

Click the button below to run the program directly in **Google Colab**:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leorasdsouza/INS-Lab-Programs/blob/main/Hill%20Cipher/Hill_Cipher.ipynb)

## Features

- Encrypts plaintext using a **predefined key matrix**.
- Automatically **pads the plaintext** if necessary.
- Works with **uppercase English letters**.

## How It Works

1. The plaintext is **converted into numerical form** (A = 0, B = 1, ..., Z = 25).
2. The text is split into blocks matching the size of the key matrix.
3. The blocks are multiplied by the **key matrix** and taken modulo 26.
4. The resulting numbers are converted back to letters to form the **ciphertext**.

## Usage Instructions

### Running the Program

#### **Option 1: Run in Google Colab**

Click the **"Open in Colab"** button above.

#### **Option 2: Run Locally**

1. Download the script `HillCipher.py` from this repository.
2. Open a terminal or command prompt.
3. Run the following command:
   ```bash
   python HillCipher.py
   ```
4. The program will output:
   - The **encrypted message**.

### Sample Output

![image](https://github.com/user-attachments/assets/acb9bb98-ad64-4781-8d66-1735cdd108e9)
![image](https://github.com/user-attachments/assets/3c045e40-0f15-472e-a66d-eb73fd81b6d9)




