# NETWORKWALKS B084F — WEEK 3 PROJECT
## Password Cracking with John the Ripper and Networkwalks Tools

![Project](https://img.shields.io/badge/Networkwalks-Week%203-blue)
![Platform](https://img.shields.io/badge/Platform-Windows-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Focus](https://img.shields.io/badge/Focus-Password%20Security-red)

## 1. Project Overview

This repository documents the practical exercises completed during Week 3 of the Networkwalks cybersecurity training programme, Batch B084F.

The project focuses on password security assessment through two practical modules:

- **W3-PM1:** Password Cracking with John the Ripper (JTR).
- **W3-PM2:** Password Cracking with Networkwalks Tools.

Both exercises involved working with password-protected PDF documents, extracting their password hashes, performing password-cracking exercises, and verifying successful password recovery.

The practical work was conducted using a Windows environment.

## 2. Project Objectives

The main objectives were to:

1. Understand how password-protected PDF files use password-derived hashes.
2. Extract PDF password hashes using dedicated tools.
3. Understand the operation of John the Ripper and its graphical interface, Johnny.
4. Use Networkwalks Hash Calculator and Password Cracker.
5. Perform password-recovery exercises in an authorized lab environment.
6. Verify recovered passwords by accessing the original PDF documents.
7. Understand the security implications of weak document passwords.

## 3. Tools and Technologies

| Tool | Purpose |
|---|---|
| Windows | Operating system |
| Johnny | Graphical interface for John the Ripper |
| John the Ripper | Password auditing and recovery |
| Online Hash Crack PDF Hash Extractor | PDF hash extraction for PM1 |
| Networkwalks Hash Calculator | PDF hash generation for PM2 |
| Networkwalks Password Cracker | Password-cracking exercise for PM2 |
| Google Chrome | Accessing browser-based tools |
| PDF Reader | Password verification and document access |

## 4. Project Modules

### W3-PM1: Password Cracking with John the Ripper

This module involved extracting a password hash from an encrypted PDF and using John the Ripper through its Johnny graphical interface.

**Methodology:**

1. Selected the password-protected PDF training file.
2. Used the Online Hash Crack PDF Hash Extractor to generate the PDF hash.
3. Copied the extracted hash.
4. Opened Johnny on Windows.
5. Loaded the extracted PDF hash into Johnny.
6. Allowed Johnny/John the Ripper to process the hash.
7. Observed the successful password-recovery result.
8. Used the recovered password to open the original PDF.

**Tools used:**
- Johnny
- John the Ripper
- Online Hash Crack PDF Hash Extractor

**Result:** Successful password recovery and verification through opening the original PDF.

**Evidence:**

<img width="1366" height="720" alt="PDF Hash Extractor for Authorized Testing _ OHC - Google Chrome 20_11_2026 20_04_26" src="https://github.com/user-attachments/assets/0a23bbc2-aa3f-4cba-b986-a053cec51d00" />


*Figure 1: PDF hash extraction.*

<img width="896" height="654" alt="image" src="https://github.com/user-attachments/assets/524b5f7d-259d-4cf6-899a-d303e405503a" />


*Figure 2: Extracted hash loaded into Johnny.*

<img width="1366" height="720" alt="image" src="https://github.com/user-attachments/assets/982a5dbd-248b-4806-b9c6-18c72846460a" />


*Figure 3: Successful password recovery.*

### W3-PM2: Password Cracking with Networkwalks Tools

This module involved using the browser-based Networkwalks Hash Calculator and Password Cracker to recover the password of the supplied training PDF.

**Methodology:**

1. Downloaded the encrypted PDF, `My Locked PDF1.pdf`, from the Networkwalks lab page.
2. Opened the Networkwalks Hash Calculator.
3. Uploaded the encrypted PDF.
4. Generated the PDF hash beginning with `$pdf$`.
5. Copied the complete extracted hash.
6. Opened the Networkwalks Password Cracker.
7. Submitted the hash and initiated the cracking process.
8. Waited for the tool to recover the password.
9. Opened the original PDF using the recovered password.
10. Successfully accessed the document and captured the lab completion flag.

**Tools used:**
- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- Google Chrome
- Windows PDF Reader

**Result:** Successful password recovery, PDF access verification, and flag capture.

**Evidence:**

<img width="1366" height="720" alt="image" src="https://github.com/user-attachments/assets/81278733-971c-433f-b06c-a1484ae3e569" />


*Figure 4: Extracted PDF hash.*

<img width="1366" height="720" alt="image" src="https://github.com/user-attachments/assets/39522634-83b6-4c21-8dd2-a26836aa178b" />


*Figure 5: Password-cracking result.*

<img width="1366" height="720" alt="image" src="https://github.com/user-attachments/assets/a8b6fa55-a553-4f73-a6d8-007e99a4cfbb" />


*Figure 6: Successful lab completion and flag verification.*

## 5. Results and Findings

Both practical modules were completed successfully.

| Assessment | PM1 — JTR | PM2 — NW Tools |
|---|---|---|
| Hash extraction | Successful | Successful |
| Hash submission | Successful | Successful |
| Password recovery | Successful | Successful |
| PDF access verification | Successful | Successful |
| Final outcome | Completed | Completed |

The exercises demonstrated that password-protected PDF files can be vulnerable to password-guessing attacks when attackers obtain the corresponding password hashes.

**Technical limitation:** The exact attack mode and wordlist used during the PM1 Johnny session were not verified. No specific attack mode or wordlist is therefore claimed.

## 6. Security Recommendations

Based on the exercises, the following security practices are recommended:

- Use long and unique passwords for protected documents.
- Avoid common passwords and predictable password patterns.
- Never reuse passwords across different accounts or documents.
- Use password managers to generate and securely store strong passwords.
- Apply appropriate encryption settings when protecting sensitive documents.
- Share document passwords through separate trusted communication channels.
- Perform password-security assessments only with proper authorization.

## 7. Skills Gained

Through these practical exercises, I gained experience in:

- PDF password hash extraction.
- Password hash identification.
- John the Ripper and Johnny GUI.
- Browser-based password auditing tools.
- Password-recovery workflows.
- Verification of recovered passwords.
- Evidence collection and technical documentation.
- Understanding password security weaknesses.

## 8. Conclusion

Week 3 provided practical exposure to password auditing and password recovery using two different approaches.

The first module demonstrated the use of John the Ripper through Johnny, while the second introduced Networkwalks' browser-based Hash Calculator and Password Cracker.

Both exercises were successfully completed, reinforcing the importance of strong password practices and secure document protection.

## 9. Responsible Use

All exercises documented in this repository were conducted as part of an authorized educational cybersecurity lab using the supplied training materials.

The techniques demonstrated should only be used on files and systems for which permission has been granted.

Passwords, raw hashes, and the actual captured flag have intentionally been excluded from this public repository.

---


