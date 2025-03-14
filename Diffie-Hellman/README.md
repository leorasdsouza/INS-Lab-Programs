# **Diffie-Hellman Key Exchange**

This program implements the **Diffie-Hellman Key Exchange**, a cryptographic protocol that allows two parties to securely generate a shared secret key over an insecure channel.

## **Open in Google Colab**  

Click the button below to run the program directly in **Google Colab**:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leorasdsouza/INS-Lab-Programs/blob/main/Diffie-Hellman/Diffie_Hellman.ipynb)

## **Features**  

- Securely generates a **shared secret key** between two users.  
- Uses a **prime number (q)** and a **primitive root (a)** for key generation.  
- Computes **public keys** and derives a **shared key** using modular exponentiation.  

## **How It Works**  

1. **User Input**  
   - A prime number `q` and a primitive root `a` are chosen.  
   - Two private keys (`Xa` for User A and `Xb` for User B) are provided.  

2. **Public Key Generation**  
   - The public keys `Ya` and `Yb` are computed as:  
     ```
     Ya = (a^Xa) % q
     Yb = (a^Xb) % q
     ```

3. **Shared Key Computation**  
   - Both users compute the shared secret key using:  
     ```
     Ka = (Yb^Xa) % q
     Kb = (Ya^Xb) % q
     ```
   - Since both computations result in the same value, `Ka = Kb`, this shared key can be used for secure communication.  

## **Usage Instructions**  

### **Running the Program**  

#### **Option 1: Run in Google Colab**  
Click the **"Open in Colab"** button above.  

#### **Option 2: Run Locally**  
1. Download the script `diffie_hellman.py` from this repository.  
2. Open a terminal or command prompt.  
3. Run the following command:  
   ```bash
   python diffie_hellman.py
4. Enter the required values when prompted.
5. The program will output:
    Public keys for both users
    Computed shared key

### Sample Output
![image](https://github.com/user-attachments/assets/ca0f66fc-a644-4b9b-8f9e-11ccdc7740c3)

![image](https://github.com/user-attachments/assets/ac0c3009-18e4-4311-bfa7-e34733c5a45c)


