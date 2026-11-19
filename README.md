# 🔐 Password Auditing with John the Ripper (JTR)

![Domain](https://img.shields.io/badge/Domain-Cybersecurity-red)
![Tool](https://img.shields.io/badge/Tool-John%20the%20Ripper-blue)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)
![Status](https://img.shields.io/badge/Status-Completed-success)

## Project Overview

This hands-on exercise was completed during **Week 3, Project Module 1** of my cybersecurity internship practice at **NETWORKWALKS**, under the guidance of **Waqas Karim (CCIE)**.

The project explored password security, password-hash analysis, and dictionary-based password auditing using **John the Ripper (JTR)** and its graphical interface, **Johnny**. A practice PDF supplied for the training lab was used.

## Objectives

- Understand how a password-protected PDF can be audited.
- Learn the basic workflow for extracting and preparing a password hash.
- Use John the Ripper/Johnny for an authorized dictionary-based audit.
- Understand why weak or commonly used passwords are vulnerable.
- Reinforce strong, unique password practices.

## Tools and Technologies

| Tool | Purpose |
|---|---|
| John the Ripper (JTR) | Password auditing and recovery |
| Johnny GUI | Graphical interface for John the Ripper |
| Windows | Operating system used |
| PDF hash extraction utility | Extracting the hash from the practice PDF |
| Dictionary-based auditing | Testing candidate passwords against the extracted hash |

## Practical Workflow

1. Visited the official John the Ripper project page and obtained the required software.
2. Installed Johnny on Windows.
3. Configured Johnny to use the John the Ripper executable.
4. Extracted the hash from the authorized practice PDF.
5. Loaded the hash into Johnny.
6. Ran the dictionary-based password audit.
7. Verified the recovered password by opening the practice PDF.

## Screenshots

The screenshots below document the installation, configuration, hash extraction, auditing, and verification stages. Passwords, hash values, and the unique training flag have been redacted from the public copies.

### 1. John the Ripper project page
![John the Ripper project page](screenshots/01-john-the-ripper-official-page.png)

### 2. Johnny setup wizard
![Johnny setup wizard](screenshots/02-johnny-setup-welcome.png)

### 3. Ready to install
![Johnny ready to install](screenshots/03-johnny-ready-to-install.png)

### 4. Installation progress
![Johnny installation progress](screenshots/04-johnny-installation-progress.png)

### 5. Johnny configuration
![Johnny configuration](screenshots/05-johnny-configuration.png)

### 6. PDF hash extraction
![PDF hash extraction with sensitive output redacted](screenshots/06-pdf-hash-extraction-redacted.png)

### 7. Johnny audit result
![Johnny audit result with password and hash redacted](screenshots/07-johnny-audit-result-redacted.png)

### 8. Johnny audit overview
![Johnny audit overview with password and hash redacted](screenshots/08-johnny-audit-overview-redacted.png)

### 9. PDF password verification
![PDF password prompt with password redacted](screenshots/09-pdf-password-prompt-redacted.png)

### 10. Training completion
![Training completion certificate with unique flag redacted](screenshots/10-training-completion-redacted.png)

## Key Learnings

- Password hashes can be extracted from supported protected files for authorized auditing.
- Dictionary-based attacks test candidate words against password hashes.
- Weak and reused passwords can be easier to guess.
- Strong, unique passwords help reduce the risk of unauthorized access.
- Password auditing is useful for identifying weaknesses in a controlled and authorized environment.

## Ethical Use and Safety

All testing documented here was carried out in an authorized cybersecurity training lab using the provided practice file. Do not test files, accounts, or systems unless you own them or have explicit permission.

**Public portfolio note:** The screenshots in this repository are sanitized. Do not publish real passwords, reusable hashes, private documents, or challenge tokens/flags.

## Acknowledgement

Special thanks to **NETWORKWALKS** and **Waqas Karim (CCIE)** for the learning opportunity and practical guidance.

## Author

**Adigun Olamide Precious**  
Cybersecurity Student | Aspiring Cybersecurity Professional

---

⭐ This project is part of my ongoing cybersecurity learning journey.
