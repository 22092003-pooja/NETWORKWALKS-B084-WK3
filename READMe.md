networkwalks-B082-week1-Week-3-Password-Cracking
📌 Overview
Crack the password of attached PDF file (My Locked PDF1.pdf) using JTR JOHN and JTR JOHNNY tools on my Windows PC.

🖥️ Lab Environment
<img width="617" height="372" alt="image" src="https://github.com/user-attachments/assets/f24b2cf9-0bb6-4e0a-b73c-95742b9130a4" />


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
<img width="830" height="557" alt="image" src="https://github.com/user-attachments/assets/f614dcc2-7246-466d-8cf0-664b204e7b86" />

<img width="820" height="520" alt="image" src="https://github.com/user-attachments/assets/d18df6e8-aadd-4bbc-8748-3c3210eb0b31" />

Step 2 - Add john.exe file to the Johnny GUI
<img width="822" height="516" alt="image" src="https://github.com/user-attachments/assets/86c858a4-8a6b-4e18-b4c3-ed3aa923b54e" />


Step 3 - Download the PDF to be cracked
<img width="332" height="150" alt="image" src="https://github.com/user-attachments/assets/b9740b1d-bcc7-41ac-8a16-b47596a6d6a2" />


Step 4 - Save has value, upload file and start new attack
<img width="816" height="266" alt="image" src="https://github.com/user-attachments/assets/48a35e22-c559-47c9-a1b5-3a4d8c30430b" />
<img width="806" height="481" alt="image" src="https://github.com/user-attachments/assets/6531abd0-7c46-4418-934a-45ee8f6b4659" />
<img width="387" height="205" alt="image" src="https://github.com/user-attachments/assets/17860060-02e2-4ec0-abe5-1e74b1253439" />
<img width="812" height="508" alt="image" src="https://github.com/user-attachments/assets/ee9d5c01-2712-4844-88fe-a03ef9aba5e8" />


Step 5 - Test the cracked password
<img width="818" height="435" alt="image" src="https://github.com/user-attachments/assets/044707d5-a5a3-4675-84df-c134ad8b8e00" />
<img width="651" height="718" alt="image" src="https://github.com/user-attachments/assets/a99ae95b-cc44-438c-a95e-2ddd11f52e32" />

Password Cracking with Networkwalks Tools

📋 General Steps Taken

Uplaod locked PDF file to Networkwalks Hash Calculator
Copy the PDF hash value into Networkwalks Password Cracker
Open the locked PDF file and enter the cracked password


Step 1 - Uplaod locked PDF file to Networkwalks Hash Calculator
<img width="815" height="692" alt="image" src="https://github.com/user-attachments/assets/e97bc65e-bc69-4a7d-a833-22d9cf866cbb" />

Step 2 - Copy the PDF hash value into Networkwalks Password Cracker
Access Denied
<img width="820" height="707" alt="image" src="https://github.com/user-attachments/assets/559ad749-75d8-469b-a99c-46baec6a30ec" />




Access Granted
<img width="808" height="727" alt="image" src="https://github.com/user-attachments/assets/b56e49fd-1160-4514-a30a-877b2cf79b59" />


Step 3 - Open the locked PDF file and enter the cracked password

<img width="651" height="797" alt="image" src="https://github.com/user-attachments/assets/ab3e5db8-ad03-4b34-9627-72498f46ee8b" />

🧠 What I've learnt
Throughout this lab, I have learnt about different tools that are used together in discovering the passwords for pdf files. There are tools like PDF Hash Extractor that extracts the has value of a pdf. That hash value is then pasted into a tool like John The Ripper GUI version which is connected to the john.exe file from John The Ripper cli version. When the hash file is uploaded to the software it is abble to crack the password of the locked pdf file. There are other tools that can help in getting the hash value of a PDF file like https://networkwalks.com/hash-calculator/ . Networkwalks Password Cracker https://networkwalks.com/password-cracker/ is then used to reveal that password for the pdf file by using either its built in ist or through uploading a custom dictionary. It was observed when using the Networks Password Cracker, that the algorithm seemedto be a brute force methodology.

🔐 Copyright Notice
© 2026 Asher J. Maxwell. All Rights Reserved.

This repository, including its documentation, configurations, lab materials, and original content, is the property of Asher Maxwell. Unauthorized copying, reproduction, modification, redistribution, or commercial use of the original content without prior written permission is prohibited.

The materials are provided for educational and cybersecurity lab purposes only. Any third-party software, trademarks, or resources referenced in this repository remain the property of their respective owners.



