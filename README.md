# WEEK-3-PDF-PASSWORD-RECOVERY-USING-JOHN-THE-RIPPER

## PDF Password Recovery Using John the Ripper

**Organisation:** Networkwalks  
**Programme:** Cybersecurity Internship  
**Week:** 3  
**Operating System:** Kali Linux  
**Primary Tool:** John the Ripper  
**Technique:** Dictionary Attack  
**Interfaces Used:** Graphical User Interface (GUI) and Command-Line Interface (CLI)

---

## 1. Introduction

During the third week of my cybersecurity internship at Networkwalks, I worked on a practical exercise involving password recovery from a password-protected PDF document.

The task involved using John the Ripper, a password security auditing and recovery tool, to perform a dictionary attack against the protected PDF.

I explored both the graphical user interface (GUI) and command-line interface (CLI) approaches and used a wordlist containing possible password combinations.

This exercise provided practical knowledge of password recovery techniques and demonstrated the importance of using strong passwords to protect sensitive documents.

## 2. Project Objectives

The objectives of this exercise were to:

- Understand how password-protected PDF documents work.
- Become familiar with John the Ripper.
- Understand the concept of dictionary attacks.
- Use a wordlist to test possible passwords.
- Explore password recovery through GUI and CLI.
- Understand the security implications of weak passwords.
- Learn the importance of password strength and complexity.

## 3. Tools and Technologies Used

| Tool | Purpose |
|---|---|
| Kali Linux | Operating system used for the practical exercise. |
| John the Ripper | Password auditing and recovery tool. |
| Wordlist | A collection of candidate passwords used during the dictionary attack. |
| PDF Document | The password-protected file used for the exercise. |
| GUI | Graphical interface used to interact with the password recovery process. |
| CLI | Terminal-based interface used to execute and manage commands. |

## 4. Understanding John the Ripper

John the Ripper is a password security auditing tool used to test password strength and recover passwords from supported password hash formats.

It supports different password-testing techniques, including:

- Dictionary attacks.
- Wordlist-based password testing.
- Brute-force and incremental password testing.
- Password candidate analysis.

For this exercise, I focused on the dictionary attack method.

## 5. Understanding Dictionary Attacks

A dictionary attack is a password-testing technique that uses a predefined list of possible passwords, commonly called a wordlist.

Instead of randomly testing every possible character combination, the tool checks candidate passwords from the supplied list.

The process involves comparing the candidate passwords against the password protection mechanism and determining whether a matching password can be found.

The effectiveness of this method depends on factors such as:

- The quality of the wordlist.
- The complexity of the original password.
- The password's length and unpredictability.
- The document's encryption and password protection configuration.

## 6. Project Methodology

The exercise was completed in the following stages.

### Stage 1: Preparation

I prepared the password-protected PDF document and the required wordlist for the exercise.

I also ensured that John the Ripper was available in my Kali Linux environment.

### Stage 2: Password Recovery Using the GUI

I explored the graphical interface approach to understand how the password recovery process could be managed without relying entirely on terminal commands.

During this stage, I:

- Opened the graphical interface.
- Selected the appropriate PDF password recovery workflow.
- Provided the required document and wordlist.
- Initiated the dictionary attack.
- Monitored the recovery process and observed the results.

### Stage 3: Password Recovery Using the CLI

I also performed the exercise using the command-line interface.

The CLI approach allowed me to interact directly with John the Ripper through the Kali Linux terminal.

During this stage, I:

- Prepared the required input files.
- Used the command-line workflow for the recovery exercise.
- Applied the dictionary attack using the selected wordlist.
- Monitored the process.
- Reviewed the results returned by the tool.

### Stage 4: Result Verification

After the password recovery exercise, I reviewed the result and checked whether the recovered password successfully unlocked the PDF document.

**Actual result:** [Insert whether the password was successfully recovered or not.]

## 7. GUI vs CLI Comparison

| Feature | GUI | CLI |
|---|---|---|
| Interaction | Uses graphical elements. | Uses terminal commands. |
| Ease of use | Generally easier for beginners. | Requires familiarity with commands. |
| Configuration | Managed through graphical options. | Managed through command arguments and files. |
| Feedback | Displays progress through the interface. | Displays output in the terminal. |
| Flexibility | Depends on the available GUI features. | Offers more direct control over operations. |

Both approaches provided an opportunity to understand how password recovery can be performed using John the Ripper.

## 8. Security Relevance

This exercise demonstrated why password security is important when protecting confidential files.

A document protected with a weak or commonly used password may be more susceptible to dictionary-based password guessing.

Organisations and individuals should therefore:

- Use long and unpredictable passwords.
- Avoid common words and easily guessed combinations.
- Avoid reusing passwords across different documents and accounts.
- Store passwords securely.
- Use appropriate encryption and access-control practices.
- Follow organisational policies for protecting sensitive documents.

## 9. Challenges and Observations

During the exercise, I gained experience working with both graphical and command-line interfaces.

I also learned that the effectiveness of a dictionary attack depends heavily on the contents of the wordlist and the strength of the password being tested.

An unsuccessful dictionary attack does not necessarily mean that a document is secure; it may simply mean that the correct password was not included in the selected wordlist.

## 10. Skills and Knowledge Acquired

At the end of this exercise, I gained practical knowledge in:

- PDF password recovery concepts.
- John the Ripper.
- Dictionary-based password attacks.
- Wordlist usage.
- GUI-based security tools.
- Command-line security operations.
- Password strength assessment.
- Document protection and encryption awareness.
- Cybersecurity documentation.

## 11. Conclusion

The Week 3 exercise provided practical experience with password recovery using John the Ripper.

By performing a dictionary attack with a wordlist and exploring both GUI and CLI approaches, I gained a better understanding of how password-testing tools operate and how weak passwords can expose protected documents to security risks.

The exercise reinforced the importance of creating strong, unique passwords and applying appropriate security measures when handling confidential documents.

It also improved my confidence in using cybersecurity tools within a controlled laboratory environment.

## 12. Evidence and Screenshots

The following evidence can be included in this repository:

- Screenshot of the password-protected PDF.
- Screenshot of the John the Ripper GUI.
- Screenshot showing the selected wordlist.
- Screenshot of the dictionary attack process.
- Screenshot of the CLI workflow.
- Screenshot showing the final recovery result, if successful.
- Screenshot showing successful PDF access, if applicable.

### Suggested Repository Structure

```text
Week-3/
│
├── README.md
│
├── reports/
│   └── WEEK-3-PDF-PASSWORD-RECOVERY-USING-JOHN-THE-RIPPER.md
│
├── screenshots/
│   ├── pdf-protected-document.png
│   ├── john-the-ripper-gui.png
│   ├── dictionary-attack-process.png
│   ├── john-the-ripper-cli.png
│   └── recovery-result.png
│
└── evidence/
    └── README.md
```

## 13. Author

**Role:** Cybersecurity Intern  
**Organisation:** Networkwalks  
**Project:** PDF Password Recovery Using John the Ripper  
**Focus Area:** Password Security and Security Auditing

---

**Disclaimer:** This exercise should only be performed on documents you own or have explicit permission to assess. Do not publish recovered passwords, sensitive documents, password hashes, or private wordlists in a public repository.
