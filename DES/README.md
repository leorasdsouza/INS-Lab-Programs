# Data Encryption Standard (DES) - Key Generation Program

## Overview

This program implements a custom key generation process as part of the **Data Encryption Standard (DES)**. It takes a user-input string, processes it through a series of binary transformations, bit shifts, and random bit removal techniques, and generates 8 unique keys.

## Open in Google Colab

Click the button below to run the program directly in **Google Colab**:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leorasdsouza/INS-Lab-Programs/blob/main/DES/des.ipynb)

## Features

- Converts plaintext into binary representation.
- Removes specific bits to modify the binary sequence.
- Splits the modified binary into two halves.
- Applies bitwise shifts to create variations of the key.
- Generates 8 unique DES keys using a predefined transformation.

## How It Works
### Key Generation Process:
1. Convert Input to Binary
  - Each character in the input string is converted to 8-bit binary.
2. Modify Binary Sequence
  - Removes specific bits from each 8-bit block.
3. Split the Binary Data
  -The processed binary string is divided into two halves: Left and Right.
4. Apply Bitwise Shifts
  -Each half undergoes left shifts using predefined values.
5. Generate 8 DES Keys
  -Using a selection process, 8 unique keys are generated.
## Usage Instructions

### Running the Program

#### **Option 1: Run in Google Colab**

Click the **"Open in Colab"** button above.

#### **Option 2: Run Locally**

1. Download the script `des.py` from this repository.
2. Open a terminal or command prompt.
3. Run the following command:
   ```bash
   python des.py
   ```
4. Enter a plaintext string when prompted.
5. The program will generate and display 8 unique DES keys.
6. 
### Sample Output

![image](https://github.com/user-attachments/assets/2d8128f0-f849-45d1-ac2a-0e7d51e870e0)


![image](https://github.com/user-attachments/assets/4774f887-cb4f-455b-9eaa-f56281192369)







