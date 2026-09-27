# NETWORKWALKS-WEEK03-PASSWORD-CRACKING-JTR
Networkwalks Cybersecurity Week 03 Project – Password Cracking with John the Ripper and Network Tools

NETWORKWALKS-SANIKA-B083-WK3-PM1-PM2-PASSWORD-CRACKING-WITH-JTR-NW-TOOLS
NETWORKWALKS Week 03 – Password Cracking with JTR & Network Tools

PASSWORD CRACKING WITH JTR & NETWORK TOOLS

Building an authorized password recovery and security assessment framework combining offline hash extraction via John the Ripper and browser-based dictionary attacks via Networkwalks utilities.

01
⚠️ Liability & Educational Disclaimer

This project is created strictly for educational, cybersecurity training, and authorized laboratory purposes as part of the NETWORKWALKS Week 03 cybersecurity program.

The password recovery and password-cracking techniques demonstrated in this project, including the use of John the Ripper (JTR), Johnny GUI, and Networkwalks tools, must only be used on files, systems, accounts, or data that you own or have explicit permission to test.

The author does not support or encourage unauthorized access, credential theft, privacy violations, or any illegal activity.

All passwords, PDF documents, hashes, and other materials used in this laboratory exercise are intended for controlled educational testing. The techniques demonstrated should not be applied to real-world systems without proper authorization.

The author and project contributors are not responsible for any misuse, damage, data loss, unauthorized access, or legal consequences resulting from the information contained in this repository.

Use these techniques responsibly, ethically, and only within authorized environments.

📝 Project Overview

This project demonstrates the process of password recovery and password cracking using John the Ripper (JTR), Johnny GUI, and Networkwalks tools in a controlled cybersecurity laboratory environment.

The objective of this project is to understand how password-protected PDF documents can be assessed for password strength and how password hashes can be extracted and processed using password-cracking tools.

The project covers different stages of the password recovery process, including:

Identifying password-protected PDF documents.
Extracting password hashes from the authorized test files.
Preparing hash files for password-cracking analysis.
Using John the Ripper (JTR) to perform password recovery.
Using Johnny GUI as a graphical interface for JTR.
Using Networkwalks tools for the assigned password-cracking exercise.
Verifying recovered passwords in the authorized laboratory files.
Documenting the complete process with screenshots and observations.
The practical exercise helps demonstrate important cybersecurity concepts such as password security, hashing, password strength, wordlists, brute-force/dictionary-based attacks, and the importance of strong passwords.

All activities in this project are performed strictly within an authorized educational lab environment for cybersecurity learning and awareness.

🧰 Tools & Technologies

Tool / Technology| Category| Description John the Ripper (JTR)| Password Cracker| Open-source multi-format password recovery tool supporting various hashes. Johnny GUI| Graphical Interface| Graphical point-and-click interface wrapper for John the Ripper. Networkwalks Hash Calculator| Web Utility| Browser-based utility used to extract crackable "$pdf$" format hashes. Networkwalks Password Cracker| Web Cracker| Online dictionary attack tool for evaluating credential strengths.

⚙️ Methodology & Execution

Method 1: Password Cracking with John the Ripper & Johnny GUI (Applied to Multiple Locked PDFs)

JTR & Johnny Download: Downloaded John the Ripper and the Johnny GUI setup package ("johnny-2.2-win.zip") from the official Openwall website, mirror links, or the course Google Drive folder.
02
Application Installation: Located and ran the Johnny installer setup file ("johnny-installer.exe") from the "Downloads" folder to install Johnny on the Windows PC.
03
Binary Path Configuration: Configured Johnny by navigating to "Settings" and mapping the executable path to "john.exe" inside the JTR run folder.
04
PDF Hash Extraction: Uploaded each of the authorized locked PDF files ("My Locked PDF1.pdf", "My Locked PDF2.pdf", and "My Locked PDF3.pdf") sequentially to an authorized PDF hash extractor to obtain their respective hash values.
05
Extracted the individual hash values for "My Locked PDF1.pdf", "My Locked PDF2.pdf", and "My Locked PDF3.pdf".

Hash File Preparation: Pasted each extracted hash into Notepad, ensured no extra leading characters remained, and saved them respectively as "hash1.txt", "hash2.txt", and "hash3.txt".

Attack Initialization: Opened Johnny, selected "Open password file" to load each hash text file sequentially ("hash1.txt", "hash2.txt", and "hash3.txt"), and initiated the process using "Start new attack".

06 Cracking password for my hash for my locked PDF1 07
For My locked PDF2

08 For locked PDF3
Method 2: Password Cracking with Networkwalks Tools (Applied to Multiple Locked PDFs)

Hash Calculator Access: Opened the browser-based Networkwalks Hash Calculator utility.

09
File Upload & Parsing: Uploaded each of the authorized target locked PDF files ("My Locked PDF1.pdf", "My Locked PDF2.pdf", and "My Locked PDF3.pdf") to the Hash Calculator one by one to generate their crackable hash formats.

10
Extracted the individual hash values for each authorized PDF.
Hash String Retrieval: Copied the complete generated hash strings for each respective PDF document.

Dictionary Attack Execution: Navigated to the Networkwalks Password Cracker, entered the extracted hashes for the authorized files sequentially, selected the available dictionary option, and started the password-recovery process.

