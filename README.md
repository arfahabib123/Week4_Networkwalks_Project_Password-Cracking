# 🔐 Week 3 – PDF Password Cracking | Networkwalks Academy

## 📌 Project Overview

This project was completed as part of my Week 3 Cybersecurity Practical Lab at **Networkwalks Academy**.

The objective was to understand how password-protected PDF files can be tested for weak passwords using hash extraction and dictionary-based password attacks.

Through this hands-on exercise, I explored password hash extraction and used dictionary attacks to identify the password of a protected PDF file in a controlled lab environment.

## 🎯 Objectives

- Understand how password-protected PDF files work.
- Extract a crackable password hash from an encrypted PDF.
- Learn how dictionary attacks are performed.
- Use John the Ripper for password-cracking practice.
- Understand the importance of strong passwords.

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Networkwalks Hash Calculator | Extracting a crackable hash from a password-protected PDF |
| Networkwalks Password Cracker | Performing a dictionary attack through a wordlist |
| John the Ripper | Testing password hashes against wordlist entries |

## ⚙️ Practical Workflow

### 1. Hash Extraction

I used the Networkwalks Hash Calculator to extract a crackable hash from a password-protected PDF file.

The tool generated a hash in a format compatible with PDF password-cracking tools such as pdf2john and Hashcat.

### 2. Dictionary Attack

I explored dictionary-based password cracking by testing words from a wordlist against the extracted password hash.

I also used **John the Ripper** to understand and practice the dictionary attack process.

### 3. Password Verification

After identifying a matching password, I tested it by opening the protected PDF file.

The successful verification demonstrated how weak passwords can be vulnerable to dictionary attacks.

## 📚 Key Learning Outcomes

- Understood the relationship between password protection and password hashes.
- Learned how password hashes can be extracted from protected PDF files.
- Gained practical experience with dictionary attacks.
- Explored the use of John the Ripper for password auditing.
- Understood why commonly used and predictable passwords are risky.
- Improved my understanding of practical password security testing.

## 🔑 Key Takeaway

This lab helped me understand that password protection alone does not guarantee security. Weak and predictable passwords can be vulnerable to dictionary attacks, which makes choosing strong and unique passwords essential.

## 📸 Project Screenshots

The repository includes screenshots documenting the practical workflow:

1. PDF hash extraction using the Networkwalks Hash Calculator.
2. Dictionary attack using the Networkwalks Password Cracker.
3. Password verification by opening the protected PDF.

## ⚖️ Disclaimer

This practical exercise was performed in a controlled learning environment using a lab-provided PDF file. The techniques demonstrated are intended for educational purposes and authorized security testing only.

##  Acknowledgment

Thanks to **Networkwalks Academy** for providing this hands-on cybersecurity learning opportunity.

## 👩‍💻 Author

**Arfa Habib**

NetworkWalks B084H | Cybersecurity Learner
---

**#Cybersecurity #Networkwalks #EthicalHacking #JohnTheRipper #PasswordSecurity #DictionaryAttack #HandsOnLearning**
