# Week3 - Password-Cracking-Techniques
Cracking PDF Files with Consent

## Overview

In week 3 of my cybersec internship I did two practical exercises around password cracking. These were exercises in which we looked at how you can attempt to crack the password on a password protected PDF file using various password cracking tools. I used John the Ripper (JTR), Johnny GUI and Networkwalks as my online tools to pull the password hashes and do the cracking. These exercises gave me some very hands on experience with password security, password hashing and the importance of using good passwords to protect your data.

## Objectives

- Understand the basic concept of password cracking and password hashing.
- Learn how to extract password hashes from password protected PDFS.
- Practise using a variety of password cracking tools.
- Understand the importance of password complexity and security.

## Module 1: Password Cracking with John the Ripper (JTR)

### Tools Used
- John the Ripper (JTR)
- Johnny GUI
- Online PDF Hash Extractor
- Notepad
- Windows PC / Kali Linux

### Methodology

1. Downloaded and installed John the Ripper and Johnny GUI.
2. Configured the Johnny GUI by finding the john.exe executable.
3. Uploaded the encrypted PDF to an online PDF hash extractor.
4. Pulled the PDF hash and copied it.
5. Saved the extracted hash to a text file called hash1.txt.
6. Opened Johnny GUI and loaded the password file.
7. Commenced a new password cracking attack.
8. Retrieved the recovered password.
9. Used the recovered password to successfully gain access to the protected PDF.

### Learning Outcomes

This exercise has got me to grips with John the Ripper and its GUI (Johnny). I've learned how you can extract password hashes from protected files and use those as input to a cracking tool. I also got a better feel for how password complexity impacts the time it takes to recover a password.


## Module 2: Password Cracking with Networkwalks Tools

### Tools Used
- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- Web Browser
- Windows PC / Kali Linux

### Methodology

1. Downloaded the encrypted PDF file that had been provided for the exercise.
2. Opened the Networkwalks Hash Calculator via a web browser.
3. Uploaded the protected PDF to extract the password hash from it.
4. Copied the full hash value (starting with $pdf$).
5. Opened the Networkwalks Password Cracker.
6. Pasted the extracted hash into the password cracking tool.
7. Commenced the cracking process and waited for the tool to find the password.
8. Used the password we'd recovered to open the protected PDF.

### Learning Outcomes

Through that exercise I've learned how easy it is to do a password crack via browser tools without having to install any additional software. I also understood the link between extracting a password hash and then taking that hash as input to a password cracking tool.

## Key Takeaways

Throughout both exercises, I gained practical knowledge of:

- Password hashing and its use in password protection.
- Extracting the hashes from the encrypted PDFS.
- Using John the Ripper and Johnny GUI for the cracking exercises.
- Doing some password cracking exercises using the browser based tools.
- The importance of password length and complexity.
- The security risks inherent in the use of weak and commonly used passwords.

## Conclusion

Overall these two exercises have given me a much better understanding of how password cracking works in the world of cyber security. Having used both John the Ripper and Networkwalks has given me a real insight into the various techniques that are available for cracking passwords from PDFS. The experience really helped to ground my practical understanding of password security, password hashing and security testing. Most importantly it drove home the fact that having strong, unique passwords is absolutely critical to the protection of both personal and organisational data.

*Note: These exercises were carried out in an authorised learning environment using the supplied lab files.*
