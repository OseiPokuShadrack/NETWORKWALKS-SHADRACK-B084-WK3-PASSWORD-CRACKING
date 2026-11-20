# NETWORKWALKS-SHADRACK-B084-WK3-PASSWORD-CRACKING

<div align="center">

# PDF Password Cracking

**Week 3 Project — NetworkWalks B084**

</div>

<p align="center">
  <img src="https://img.shields.io/badge/Cybersecurity-Lab-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/VirtualBox-v7.2.18-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Kali%20Linux-v2025.3-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Tool-Johnny%20%7C%20John%20the%20Ripper-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/NetworkWalks-B084-C00000?style=flat-square" />
</p>

---

## Project Overview

This project documents my Week 3 cybersecurity practical exercise at NetworkWalks, focusing on **Password Cracking and PDF Password Recovery**.

The main objective of this project was to understand how password-protected PDF documents can be assessed using password-cracking tools and techniques in a controlled cybersecurity lab environment.

I completed two practical exercises using different approaches to generate PDF password hashes and recover the passwords.

### Exercise 1 — Online Hash Crack & Johnny (John the Ripper)

For my first exercise, I used the Online Hash Crack website to generate the hash of a password-protected PDF document.

After generating the hash, I copied the hash text into Notepad and saved it as a text file. I then imported the saved hash file into Johnny, the graphical interface for John the Ripper, running on Kali Linux.

Johnny was used to perform the password-cracking process against the generated PDF hash until the password was successfully recovered.

### Exercise 2 — NetworkWalks Hash Generator & Password Cracker

For my second exercise, I used another locked PDF document and followed the password-cracking process provided through the NetworkWalks platform.

I used the NetworkWalks Hash Generator to generate the PDF hash and then submitted the generated hash to the NetworkWalks Password Cracker.

The objective was to recover the PDF password and successfully capture the **Capture The Flag (CTF)** result.

---

## OBJECTIVES & TOOLS

The main objectives of this project were to:

- Understand how password-protected PDF documents work.
- Learn how password hashes are generated from locked PDF documents.
- Use the Online Hash Crack website to generate a PDF hash.
- Understand how to save generated hash text using Notepad.
- Use Johnny (John the Ripper GUI) to perform password cracking.
- Learn how John the Ripper processes password hashes.
- Use the NetworkWalks Hash Generator to generate another PDF hash.
- Use the NetworkWalks Password Cracker to recover the second PDF password.
- Successfully complete the password-cracking exercise and capture the flag.
- Understand the importance of strong passwords and document security.

### Tools and Technologies Used

| Tool | Purpose |
|---|---|
| Kali Linux | Operating system used for the practical exercise. |
| VirtualBox | Virtual environment used to run Kali Linux. |
| Online Hash Crack | Used to generate the hash of the first locked PDF. |
| Notepad | Used to save the generated PDF hash as a text file. |
| Johnny | Graphical interface used to operate John the Ripper. |
| John the Ripper | Password-cracking tool used to recover the first PDF password. |
| NetworkWalks Hash Generator | Used to generate the hash of the second locked PDF. |
| NetworkWalks Password Cracker | Used to crack the second PDF password and complete the CTF exercise. |

---

## PRACTICAL IMPLEMENTATION

# EXERCISE 1: PDF PASSWORD CRACKING USING JOHNNY (JOHN THE RIPPER)

### Step 1 — Generating the PDF Hash

I started by using the Online Hash Crack website to generate the password hash from my first password-protected PDF document.

The generated hash was required because Johnny uses password hash information to perform the password-cracking process.

**Screenshot 1: Online PDF Hash Generation**

<img width="1348" height="655" alt="Screenshot 2026-11-20 133716" src="https://github.com/user-attachments/assets/dbf8990d-7d80-4a84-8e70-7a646067611f" />


*Explanation:* Screenshot showing the first locked PDF being processed by the Online Hash Crack website to generate its password hash.

### Step 2 — Saving the Generated Hash in Notepad

After generating the hash, I copied the generated hash text and pasted it into Notepad.

I saved the hash as a text file so that it could be imported into Johnny for the password-cracking process.

**Screenshot 2: Saving the Hash Using Notepad**

<img width="1004" height="398" alt="Screenshot 2026-11-20 134843" src="https://github.com/user-attachments/assets/1787ba36-b287-4932-b36f-fe116eb7517a" />


*Explanation:* Screenshot showing the generated PDF hash saved as a text file using Notepad.

### Step 3 — Loading the Hash into Johnny

Next, I opened Johnny on Kali Linux.

Johnny provides a graphical interface for John the Ripper, making it easier to load password hashes and monitor the cracking process.

I imported the previously saved hash text file into Johnny to prepare it for password cracking.

**Screenshot 3: Loading the Hash into Johnny**

<img width="680" height="711" alt="image" src="https://github.com/user-attachments/assets/90ca1bff-f7e5-47b4-acad-9e396848beb9" />


*Explanation:* Screenshot showing the generated PDF hash being loaded into Johnny before starting the password-cracking process.

### Step 4 — Performing the Password Cracking

After importing the hash, I initiated the password-cracking process using Johnny.

John the Ripper processed the hash and attempted to identify the password associated with the protected PDF.

**Screenshot 4: Johnny Password Cracking Process**

<img width="690" height="715" alt="Screenshot 2026-11-20 133417" src="https://github.com/user-attachments/assets/a062b081-d952-4ca4-9604-000fa8fe70e3" />


*Explanation:* Screenshot showing Johnny performing the password-cracking process using the imported PDF hash.

### Step 5 — Successful Password Recovery

The password-cracking process successfully recovered the password associated with the first protected PDF.

This demonstrated how password hashes can be assessed using password-cracking tools in an authorized laboratory environment.

**Screenshot 5: Recovered PDF Password**

<img width="1353" height="641" alt="Screenshot 2026-11-20 110733" src="https://github.com/user-attachments/assets/04f79e52-f23f-4d9b-849a-d1e307cb10ec" />


*Explanation:* Screenshot showing the successful password recovery result in Johnny.

---

# EXERCISE 2: PDF PASSWORD CRACKING USING NETWORKWALKS TOOLS

### Step 1 — Generating the Second PDF Hash

For the second exercise, I used another password-protected PDF document.

Instead of using the Online Hash Crack website, I used the NetworkWalks Hash Generator to generate the hash of the second PDF document.

**Screenshot 6: NetworkWalks Hash Generator**

<img width="1334" height="652" alt="Screenshot 2026-11-20 133211" src="https://github.com/user-attachments/assets/ef478b91-b4f2-40ed-b459-b380079cbfd8" />


*Explanation:* Screenshot showing the second locked PDF being processed using the NetworkWalks Hash Generator.

### Step 2 — Using the NetworkWalks Password Cracker

After generating the hash, I proceeded to the NetworkWalks Password Cracker.

I supplied the generated hash to the password-cracking tool, which processed it to identify the password protecting the second PDF document.

**Screenshot 7: NetworkWalks Password Cracker**

<img width="1333" height="671" alt="Screenshot 2026-11-20 133139" src="https://github.com/user-attachments/assets/d311728e-11db-401d-ab36-950a011cc616" />


*Explanation:* Screenshot showing the generated PDF hash being submitted to the NetworkWalks Password Cracker.

### Step 3 — Successful Password Recovery and Capture The Flag

The password-cracking exercise was completed successfully, allowing me to recover the password associated with the second PDF.

I then used the successful result to complete the CTF exercise and capture the flag.

**Screenshot 8: Successful Password Recovery and CTF Flag**

<img width="1349" height="629" alt="Screenshot 2026-11-20 132915" src="https://github.com/user-attachments/assets/e7198a93-a0f5-457b-80a1-adb8b2b67375" />


*Explanation:* Screenshot showing the successful password-cracking result and the captured flag on the NetworkWalks platform.

---

## KEY LEARNING OUTCOMES

Through this practical exercise, I gained experience and understanding in the following areas:

- **Password Hashing:** Understanding how password-protected PDF documents can produce hashes for security assessment.
- **Hash Extraction:** Learning how to generate and obtain PDF password hashes using online tools.
- **John the Ripper:** Understanding how a password-cracking tool can process hashes to recover passwords.
- **Johnny GUI:** Learning how to use a graphical interface to manage and monitor password-cracking activities.
- **Hash File Management:** Understanding how to save generated hash text in Notepad and import it into a password-cracking tool.
- **CTF Practical Experience:** Applying password-cracking knowledge to complete a simulated Capture The Flag challenge.
- **Password Security:** Understanding why strong passwords are important in protecting confidential files and documents.

---

## CONCLUSION

This Week 3 project provided practical experience in password cracking and PDF password recovery using different tools and techniques.

The first exercise helped me understand how to generate a PDF hash using Online Hash Crack, save the hash in Notepad and use Johnny (John the Ripper) on Kali Linux to recover the password.

The second exercise introduced me to the NetworkWalks Hash Generator and Password Cracker, which I used to recover another PDF password and successfully capture the flag.

Overall, the project improved my understanding of password hashes, password-cracking tools and the importance of strong password protection in cybersecurity.

---

## LAB SAFETY & AUTHORIZATION

All activities documented in this project were performed as part of a controlled cybersecurity learning exercise using authorized laboratory materials.

Password-cracking techniques should only be applied to documents and systems that you own or have explicit permission to assess.

---

## AUTHOR

**Shadrack Osei Poku**

Cybersecurity Intern — NetworkWalks

Batch: **B084**

LinkedIn: [Shadrack Osei Poku](https://www.linkedin.com/in/shadrack-hacks-osei/)

---

<div align="center">

**NetworkWalks | Cybersecurity Training | Week 3 Project**

</div>
