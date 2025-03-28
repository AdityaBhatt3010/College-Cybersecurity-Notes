# **Module 2: The Security Environment – Complete Exam Notes**  

## **Introduction**  

In the digital age, cybersecurity is an essential pillar in safeguarding sensitive information, systems, and networks from malicious attacks. With the rise in cyber threats such as hacking, phishing, ransomware, and advanced persistent threats (APT), organizations and individuals must adopt robust security measures. This document provides an in-depth understanding of cybercrime, cybersecurity principles, threats, vulnerabilities, cryptographic techniques, and secure software development practices. By implementing best practices and staying vigilant against cyber risks, we can ensure a safer and more resilient digital environment.
![Image](https://github.com/user-attachments/assets/4854c061-5574-4902-87e6-99360b735ef3) <br/>

## **Index of Topics Covered**
1. **Cyber Crime** – Definition, types, and examples.  
2. **Cyber Security** – Definition, common attacks, and importance.  
3. **Cyber Security Principles (CIAAA Model)** – Confidentiality, Integrity, Availability, Accountability, Auditability.  
4. **Cyber Threats** – Types, sources, and common examples.  
5. **Cyber Threat Index Levels** – Risk levels and their impact.  
6. **Vulnerabilities** – Definition, causes, and types.  
7. **Advanced Persistent Threats (APT)** – Definition, examples, stages, and protection methods.  
8. **Cryptography** – Types (symmetric, asymmetric), hashing, and steganography.  
9. **Access Control** – Types (DAC, MAC, RBAC) and their significance.  
10. **Secure Software Development** – Best practices and security integration.

## **🔷 1. Cyber Crime**

📌 **Definition**:

- Any illegal activity carried out using computers, mobile devices, or the internet.
- Includes financial fraud, identity theft, cyberstalking, and hacking.

📌 **Types of Cyber Crimes**:

1. **Hacking** – Unauthorized access to a system or network.\
   🔹 *Example*: Defacing websites, stealing confidential data.
2. **Illegal Interception of Data** – Capturing data without permission.\
   🔹 *Example*: Packet sniffing.
3. **System Interference** – Disrupting normal system operations.\
   🔹 *Example*: DDoS attacks.
4. **Copyright Infringement** – Unauthorized reproduction of digital content.\
   🔹 *Example*: Torrenting copyrighted content.
5. **Fraud & Phishing** – Deception to obtain sensitive information.\
   🔹 *Example*: Fake banking websites.
6. **Cyberbullying & Harassment** – Online threats, abuse, or blackmail.\
   🔹 *Example*: Online hate speech.

---

## **🔷 2. Cyber Security**

📌 **Definition**:

- Protection of computers, networks, and data from cyber threats.
- Ensures **Confidentiality, Integrity, and Availability (CIA Triad)**.

📌 **Common Cyber Attacks**:

1. **Kill Chain Attack** – Multi-step cyber intrusion.
2. **Zero-Day Attack** – Exploiting unpatched vulnerabilities.
3. **Ransomware** – Encrypting data and demanding a ransom.
4. **MITM Attack** – Intercepting communication.

📌 **Importance of Cyber Security**:

- Prevents **data breaches**, **financial loss**, and **reputational damage**.
- Ensures **compliance** (e.g., GDPR, HIPAA).

---

## **🔷 3. Cyber Security Principles (CIAAA Model)**

📌 **Core Cyber Security Principles**:

1. **Confidentiality** – Prevents unauthorized access.
2. **Integrity** – Ensures data accuracy.
3. **Availability** – Ensures data is accessible when needed.
4. **Accountability** – Users are responsible for their actions.
5. **Auditability** – Enables security assessments.

---

## **🔷 4. Cyber Threats**

📌 **Definition**: Malicious activities aimed at disrupting or gaining unauthorized access.

📌 **Common Cyber Threats**:

1. **Social Engineered Trojans** – Malware disguised as legitimate software.
2. **Unpatched Software** – Outdated applications that can be exploited.
3. **Phishing** – Deceptive emails/messages stealing user credentials.
4. **Network Worms** – Self-replicating malware.

📌 **Sources of Cyber Threats**:

- **Nation-State Hackers** – Cyber espionage (e.g., Stuxnet).
- **Hacktivists** – Politically motivated hackers (e.g., Anonymous).
- **Rogue Employees** – Insider threats.
- **Competitors** – Corporate espionage attacks.

---

## **🔷 5. Cyber Threat Index Levels**

- **Level 0 (Low)** – Minimal risk.
- **Level 1 (Guarded)** – Minor vulnerabilities.
- **Level 2 (Elevated)** – Moderate threats.
- **Level 3 (High)** – Active cyber attacks.
- **Level 4 (Critical)** – Severe active threats.

📌 **Impact of Cyber Attacks**:

- **Financial Loss** – Ransomware, theft.
- **Reputational Damage** – Loss of customer trust.
- **Legal Consequences** – GDPR or HIPAA fines.

---

## **🔷 6. Vulnerabilities**

📌 **Definition**: A flaw that attackers can exploit.

📌 **Causes of Vulnerabilities**:

1. **Unpatched Software** – Missing security updates.
2. **Weak Passwords** – Easily guessed credentials.
3. **Unencrypted Data** – Lack of encryption.

📌 **Types of Vulnerabilities**:

- **Hardware** – Defective chips, supply chain attacks.
- **Software** – Bugs and logic flaws.
- **Network** – Open ports, weak firewall settings.

---

## **🔷 7. Advanced Persistent Threats (APT)**

📌 **Definition**: Long-term, targeted cyberattacks by well-funded hackers.

📌 **Examples**:

- **2015 Deep Panda Attack** – U.S. government data breach.
- **2020 SolarWinds Hack** – Backdoor attack.

📌 **Stages of APT**:

1. **Reconnaissance** – Information gathering.
2. **Intrusion** – Initial network entry.
3. **Persistence** – Maintaining access.
4. **Data Exfiltration** – Stealing data.

📌 **Protection Against APTs**:\
✔ Avoid suspicious emails.\
✔ Regular security audits.\
✔ Use advanced threat detection.

---

## **🔷 8. Cryptography**

📌 **Definition**: Encrypting and securing communication.

### 🔹 **Types of Cryptography**  

### **1. Symmetric Encryption (Secret-Key Cryptography)**  
📌 **Definition**:  
- Uses a **single key** for both encryption and decryption.  
- Faster but requires **secure key exchange**.  

📌 **Common Symmetric Algorithms**:  

| Algorithm  | Key Size  | Block Size | Rounds | Example Usage |
|------------|----------|------------|--------|--------------|
| **DES**  | 56-bit  | 64-bit  | 16  | Outdated but used in legacy systems. |
| **3DES (Triple DES)**  | 112-bit, 168-bit | 64-bit  | 48 | Used in banking & payment systems. |
| **AES (Advanced Encryption Standard)**  | 128, 192, 256-bit  | 128-bit  | 10, 12, 14 | Secure; used in SSL, VPNs, government encryption. |
| **Blowfish**  | 32–448-bit  | 64-bit  | 16 | Fast; used in password hashing. |

📌 **Example**:  
- Encrypting a message using **AES-256**:  
  ```
  Plaintext → Encryption (AES-256) → Ciphertext
  ```

### **2. Asymmetric Encryption (Public-Key Cryptography)**  
📌 **Definition**:  
- Uses **two keys**: a **public key** (for encryption) and a **private key** (for decryption).  
- Slower than symmetric encryption but eliminates **key exchange risks**.  

📌 **Common Asymmetric Algorithms**:  

| Algorithm  | Key Size  | Security Level | Example Usage |
|------------|----------|----------------|--------------|
| **RSA**  | 1024, 2048, 4096-bit | High | Used in digital signatures & SSL certificates. |
| **ECC (Elliptic Curve Cryptography)**  | 160-521-bit | Very High | Used in mobile devices, blockchain. |
| **Diffie-Hellman**  | 1024-bit+  | Medium-High | Used for key exchange. |

📌 **Example**:  
- **Sending an encrypted email using RSA**:  
  ```
  Sender encrypts message with Receiver’s Public Key → Only Receiver can decrypt using their Private Key.
  ```

### **3. Hashing (One-Way Cryptography)**  
📌 **Definition**:  
- Converts input data into a **fixed-length hash value** that cannot be reversed.  

📌 **Common Hashing Algorithms**:  

| Algorithm  | Output Size | Example Usage |
|------------|------------|--------------|
| **MD5**  | 128-bit | Fast but weak (prone to collisions). |
| **SHA-1**  | 160-bit | Weak (deprecated in security-sensitive applications). |
| **SHA-256**  | 256-bit | Secure; used in blockchain (Bitcoin). |
| **SHA-512**  | 512-bit | High security applications. |

📌 **Example**:  
- Hashing a password using SHA-256:  
  ```
  Input: "mypassword" → SHA-256 Hash → e38ad214943daad1d64c102faec29de4afe9da3d
  ```

### **4. Steganography (Hidden Data Technique)**  
📌 **Definition**:  
- Hides secret data **within an image, audio, or video file**.  

📌 **Example**:  
- Hiding text inside an image (LSB method).  

---

### **5. Digital Signatures**  
📌 **Definition**:  
- Ensures **data authenticity and integrity** by signing messages using **private keys**.  

📌 **Example Usage**:  
- Used in **electronic documents**, **software authenticity**, and **blockchain**.  

## **📌 Summary of Cryptography Applications:**  
✔ **Symmetric Encryption** – Used in fast data encryption (AES-256 in VPNs).  
✔ **Asymmetric Encryption** – Used in secure communication (RSA for email encryption).  
✔ **Hashing** – Used in password storage (SHA-256 in blockchain).  
✔ **Steganography** – Used for covert data hiding.  
✔ **Digital Signatures** – Used for document authenticity (e-signatures).  

---

## **🔷 9. Access Control**

📌 **Definition**: Restricting system access.

📌 **Types of Access Control**:

1. **Discretionary Access Control (DAC)** – User-defined permissions.
2. **Mandatory Access Control (MAC)** – Strict security policies.
3. **Role-Based Access Control (RBAC)** – Access based on roles.

---

## **🔷 10. Secure Software Development**

📌 **Best Practices**:\
✔ Secure coding principles.\
✔ Regular penetration testing.\
✔ Integrate security into CI/CD pipelines.

---
