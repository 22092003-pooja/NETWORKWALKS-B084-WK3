networkwalks-B082-week1-Week-3-Password-Cracking
📌 Overview
Crack the password of attached PDF file (My Locked PDF1.pdf) using JTR JOHN and JTR JOHNNY tools on my Windows PC.

🖥️ Lab Environment
Component	Configuration
Host OS	Windows
Attack Machine	Windows 11
Project	Week 3 – Module 1 & 2
Focus	Password Cracking
Primary Tool	John the Ripper (JTR) & Network Walks Tools
GUI Tool	Johnny
Program	Network Walks
Files Used
John The Ripper : https://www.openwall.com/john/
Johnny [GUI] : https://openwall.info/wiki/john/johnny
Network Walks Hash Calculator : https://networkwalks.com/hash-calculator/
Network Walks Password Cracker : https://networkwalks.com/password-cracker
📋 General Steps Taken
Download John & Johnny
Add john.exe file to the Johnny GUI
Download the PDF to be cracked
Save has value, upload file and start new attack
Test the cracked password
Step 1 - Download John & Johnny
Screenshot 2026-08-28 113924 Screenshot 2026-08-28 115458 Screenshot 2026-08-28 115734
Step 2 - Add john.exe file to the Johnny GUI
Screenshot 2026-08-28 120106
Step 3 - Download the PDF to be cracked
Screenshot 2026-08-28 120748
Step 4 - Save has value, upload file and start new attack
Screenshot 2026-08-28 121154

Screenshot 2026-08-28 122227

Screenshot 2026-08-28 122337

Screenshot 2026-08-28 123322

Step 5 - Test the cracked password
Screenshot 2026-08-28 123524

Screenshot 2026-08-28 123644
Password Cracking with Networkwalks Tools
📋 General Steps Taken
Uplaod locked PDF file to Networkwalks Hash Calculator
Copy the PDF hash value into Networkwalks Password Cracker
Open the locked PDF file and enter the cracked password
Step 1 - Uplaod locked PDF file to Networkwalks Hash Calculator
Screenshot 2026-08-28 133152
Step 2 - Copy the PDF hash value into Networkwalks Password Cracker
Access Denied
Screenshot 2026-08-28 133755



Access Granted
Screenshot 2026-08-28 134435

Step 3 - Open the locked PDF file and enter the cracked password
Screenshot 2026-08-28 123524

Screenshot 2026-08-28 123644
🧠 What I've learnt
Throughout this lab, I have learnt about different tools that are used together in discovering the passwords for pdf files. There are tools like PDF Hash Extractor that extracts the has value of a pdf. That hash value is then pasted into a tool like John The Ripper GUI version which is connected to the john.exe file from John The Ripper cli version. When the hash file is uploaded to the software it is abble to crack the password of the locked pdf file. There are other tools that can help in getting the hash value of a PDF file like https://networkwalks.com/hash-calculator/ . Networkwalks Password Cracker https://networkwalks.com/password-cracker/ is then used to reveal that password for the pdf file by using either its built in ist or through uploading a custom dictionary. It was observed when using the Networks Password Cracker, that the algorithm seemedto be a brute force methodology.

🔐 Copyright Notice
© 2026 Asher J. Maxwell. All Rights Reserved.

This repository, including its documentation, configurations, lab materials, and original content, is the property of Asher Maxwell. Unauthorized copying, reproduction, modification, redistribution, or commercial use of the original content without prior written permission is prohibited.

The materials are provided for educational and cybersecurity lab purposes only. Any third-party software, trademarks, or resources referenced in this repository remain the property of their respective owners.

Project Status
Completed ✅
