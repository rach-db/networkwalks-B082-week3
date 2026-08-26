# Week 3 – Password Cracking with John the Ripper

## About the Project

This is my **Week 3 project** from the **NetworkWalks Cybersecurity & Ethical Hacking Internship**.

For this task, I worked with **John the Ripper (JTR)** and **Johnny GUI** to understand how password recovery works. The practical involved a password-protected PDF, extracting its hash, and then using JTR to recover the password.

I did this in a controlled lab environment for learning and cybersecurity practice.
---

## Tools Used

* John the Ripper (JTR)
* Johnny GUI
* Windows
* Notepad
* PDF hash extraction tool
---

## What I Did

### 1. Set up John the Ripper and Johnny

I downloaded John the Ripper and installed the Johnny GUI on my Windows system.

After installing Johnny, I configured it to use the `john.exe` file from the John the Ripper `run` folder.

### 2. Extracted the PDF hash

I used the provided password-protected PDF and extracted its hash using a PDF hash extraction tool.

The extracted hash was then copied into a text file called `hash1.txt`.

### 3. Loaded the hash into Johnny

I opened Johnny and used the **Open password file** option to load the `hash1.txt` file.

### 4. Started the password recovery

After loading the hash, I started a new attack using John the Ripper.

The time taken for password recovery can depend on things like the password complexity and the computer's processing power.

### 5. Recovered the password

Once the process finished, Johnny displayed the recovered password.

I then used that password to open the protected PDF and verify that it worked.
---

## Workflow

```text
Password-Protected PDF
          ↓
   Extract PDF Hash
          ↓
  Save as hash1.txt
          ↓
Load Hash into Johnny
          ↓
Start John the Ripper
          ↓
   Recover Password
          ↓
Open the Protected PDF
```
---
