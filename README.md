# Password Recovery & Hash Analysis Lab

**Narresh Tamilselvan**  
Cybersecurity Student | AI-Powered Creative Designer | Penetration Tester  
[LinkedIn](https://www.linkedin.com/in/narresh-tamilselvan) · [GitHub](https://github.com/narreshtamilselvan)

---

## Project Overview

This repository documents my hands-on learning journey in an authorized password-security lab provided by **NetworkWalks**.

The lab helped me understand the practical workflow behind password auditing: extracting a hash from a password-protected PDF, testing it in a controlled environment, recovering the lab password, and opening the PDF to capture the challenge flag.

I completed the exercise using two approaches:

1. **John the Ripper (JTR)** — a password-auditing tool.
2. **NetworkWalks Hash Calculator and Password Cracker** — beginner-friendly browser tools for learning hash extraction and dictionary attacks.

> **Important:** This project was completed only with lab files provided for authorized educational purposes.

## Learning Objectives

Through this project, I learned:

- What a password hash is and why it is used in security.
- How to identify a password-protected PDF.
- How a compatible PDF hash can be extracted.
- How to store a hash in a `.txt` file for password auditing.
- How dictionary-based password recovery works.
- How to use John the Ripper in an authorized lab.
- Why strong, unique passwords are important for security.

## Tools Used

| Tool | Purpose |
| --- | --- |
| John the Ripper (JTR) | Used to test the extracted password hash in the authorized lab. |
| [NetworkWalks Hash Calculator](https://networkwalks.com/hash-calculator/) | Used to extract a password-auditing hash from the protected PDF. |
| [NetworkWalks Password Cracker](https://networkwalks.com/password-cracker/) | Used to demonstrate dictionary-based password recovery. |
| Protected PDF lab files | Supplied by NetworkWalks for the learning exercise. |
| Wordlist | Used to test password candidates in the controlled lab. |

## Method 1: Learning with John the Ripper

### 1. Start with the locked PDF

I received a password-protected PDF as part of the NetworkWalks lab. The goal was to recover the password only within the authorized learning environment.

### 2. Extract the password hash

I uploaded the locked PDF to a hash-extraction tool. The tool generated a hash in a format suitable for password-auditing tools.

![PDF hash extraction](images/HASHING%20WEB.png)

### 3. Save the hash

After extracting the hash, I copied it into a text file. This file was then used as input for John the Ripper.

### 4. Set up John the Ripper

I installed and configured John the Ripper, then loaded the text file containing the extracted hash.

### 5. Recover the lab password

John the Ripper tested password candidates against the hash using the lab wordlist. After the password was recovered, I used it to open the protected PDF.

![John the Ripper result](images/JTR.png)

### 6. Capture the flags

After accessing the PDFs, I successfully captured the lab flags.

| Flag 1 | Flag 2 | Flag 3 |
| --- | --- | --- |
| ![First captured flag](images/HASH%201%20FLAG.png) | ![Second captured flag](images/HASH%202%20FLAG.png) | ![Third captured flag](images/HASH%203%20FLAG.png) |

## Method 2: Learning with NetworkWalks Tools

NetworkWalks provided browser-based tools that made the password-auditing workflow easier to understand. These tools were especially helpful for visualizing the process before and alongside using John the Ripper.

### NetworkWalks Lab Page

The lab page provided the authorized PDF files and explained the learning activity.

![NetworkWalks password-cracking lab](images/Networkwalks%20page.png)

### Hash Calculator

The [**NetworkWalks Hash Calculator**](https://networkwalks.com/hash-calculator/) allowed me to upload the protected PDF and extract a compatible password hash. This made it easier to understand the relationship between the locked PDF and the hash used for testing.

![NetworkWalks Hash Calculator](images/Hash%20calculator%20NW.png)

### Password Cracker

The [**NetworkWalks Password Cracker**](https://networkwalks.com/password-cracker/) demonstrated how a dictionary attack works. It tested password candidates from a wordlist against the provided hash until the correct lab password was found.

This was a useful visual learning experience because it showed how weak or commonly used passwords can be discovered through wordlist-based testing.

![NetworkWalks Password Cracker](images/Password%20cracker%20NW.png)

### Captured Lab Flag

![NetworkWalks lab flag](images/FLAG%20NW.png)

## Key Takeaways

- Passwords should be long, unique, and difficult to guess.
- Common words and predictable passwords can be vulnerable to dictionary attacks.
- Hashes help protect passwords, but weak passwords can still be recovered if they appear in a known wordlist.
- Password-auditing tools should only be used with explicit authorization.
- Practical labs are an effective way to develop ethical hacking and penetration-testing skills.

## Acknowledgements

A sincere thank you to **Waqas Karim** and **NetworkWalks** for their guidance, hands-on labs, and support throughout my cybersecurity learning journey.

The Hash Calculator and Password Cracker created by NetworkWalks were extremely helpful for understanding password recovery concepts in a safe and beginner-friendly way.

## Disclaimer

This repository is for **educational purposes only**. All activities were performed in an authorized training environment using files provided for the lab. Do not attempt password recovery or security testing on systems, accounts, or files without explicit permission.

## Connect With Me

**Narresh Tamilselvan**  
[LinkedIn](https://www.linkedin.com/in/narresh-tamilselvan) · [GitHub](https://github.com/narreshtamilselvan)
