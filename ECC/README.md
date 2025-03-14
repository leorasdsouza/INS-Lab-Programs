# **Elliptic Curve Cryptography (ECC) Key Generation**

This program implements **Elliptic Curve Cryptography (ECC)** to generate private and public keys and compute encryption keys using elliptic curve point multiplication.

## **Open in Google Colab**  

Click the button below to run the program directly in **Google Colab**:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leorasdsouza/INS-Lab-Programs/blob/main/ECC/ecc.ipynb)

## **Features**  

- Uses **Elliptic Curve Cryptography (ECC)** for secure key generation.  
- Implements **elliptic curve point multiplication** to derive encryption keys.  
- Uses the **BrainpoolP256r1** curve for strong security.  
- Demonstrates the generation of **ciphertext public keys** for encryption.  

## **How It Works**  

1. **Generate Private and Public Keys**  
   - A random **private key** is generated for both sender and receiver.  
   - The corresponding **public key** is computed using:  
     ```
     Public Key = Private Key * Generator Point (g)
     ```

2. **Compute Encryption Key**  
   - A new **ciphertext private key** is generated.  
   - A corresponding **ciphertext public key** is derived.  
   - The encryption key is computed using elliptic curve point multiplication:  
     ```
     Encryption Key = Ciphertext Private Key * Ciphertext Public Key
     ```

3. **Key Exchange Simulation**  
   - Both sender and receiver generate their respective encryption keys.  
   - These encryption keys can be used in **secure communication** protocols.  

## **Usage Instructions**  

### **Running the Program**  

#### **Option 1: Run in Google Colab**  
Click the **"Open in Colab"** button above.  

#### **Option 2: Run Locally**  
1. Install the required dependencies:  
   ```bash
   pip install tinyec
2. Download the script ecc.py from this repository.
3. Open a terminal or command prompt.
4. Run the following command:
   ```bash
   python ecc.py
5. The program will output:
    Private and public keys for sender and receiver
    Computed encryption keys

### Sample Output
![image](https://github.com/user-attachments/assets/57b39b2b-859f-4afa-b1e2-703b9e43f8f6)



