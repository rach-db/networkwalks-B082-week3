# Week 3 – Password Cracking with John the Ripper

## About the Project

This week's tasks focused on understanding password cracking, password hashes, and password security through two practical exercises.

Project Module 1: Password Cracking with John the Ripper (JTR)
Project Module 2: Password Cracking with NetworkWalks Tools

The practicals were performed in a controlled lab environment using a password-protected PDF.

## Project Module 1 – Password Cracking with JTR

# Overview

In the first task, I used John the Ripper (JTR) and Johnny GUI to recover the password of a protected PDF.

The main idea was to extract the password hash from the PDF, load the hash into Johnny, and use John the Ripper to perform password recovery.

## Tools Used

-John the Ripper (JTR)
-Johnny GUI
-Notepad
-PDF hash extraction tool
-Password-protected PDF

## What I Did
### 1. Set Up John the Ripper

I downloaded and set up John the Ripper on my Windows system.

### 2. Configured Johnny

I installed Johnny, the graphical interface for John the Ripper, and configured it to use the john.exe file from the JTR run folder.

### 3. Extracted the PDF Hash

I used a PDF hash extraction tool to extract the hash from the password-protected PDF.

The hash was then saved in a text file:

```text
hash1.txt
```
### 4. Loaded the Hash into Johnny

I opened Johnny and loaded the hash1.txt file using the Open password file option.

### 5. Started the Password Recovery

I started a new attack using John the Ripper and waited for the tool to find the password.

The time required can vary depending on the password complexity and the computer's processing power.

6. Verified the Password

After the password was recovered, I used it to open the protected PDF and confirmed that it worked.
---
## Project Module 2 – Password Cracking with NetworkWalks Tools
# Overview

In the second task, I used the NetworkWalks Hash Calculator and NetworkWalks Password Cracker to perform the same type of password recovery through a web browser.

Unlike the first task, no additional software installation was required.

## Tools Used
-NetworkWalks Hash Calculator
-NetworkWalks Password Cracker
-Web Browser
-Password-protected PDF

## What I Did
### 1. Opened the Hash Calculator

I opened the NetworkWalks Hash Calculator in my browser and uploaded the password-protected PDF.

### 2. Extracted the PDF Hash

The tool generated the PDF hash, which started with:

```text
$pdf$
```

I copied the complete hash for the next step.

### 3. Opened the Password Cracker

I opened the NetworkWalks Password Cracker and pasted the extracted hash.

### 4. Started the Attack

I started the password-cracking process.

The tool used a dictionary-based approach to try different possible passwords until it found a matching password.

### 5. Recovered the Password

The tool successfully recovered the password.

### 6. Tested the Password

I entered the recovered password into the protected PDF and successfully opened the file.

## Workflow
# Module 1
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
# Module 2
```text
Password-Protected PDF
          ↓
  NetworkWalks Hash Calculator
          ↓
    Extract PDF Hash
          ↓
     NetworkWalks Password Cracker
          ↓
  Start Attack
          ↓
   Recover Password
          ↓
      Open PDF
```
## What I Learned

This week's practicals helped me understand password cracking from a more hands-on perspective.

Some of the things I learned were:

-How password-protected files can be targeted for password recovery.
-How a protected PDF can produce a hash that can be used by password-cracking tools.
-How John the Ripper works with password hashes.
-How Johnny provides a graphical interface for JTR.
-How dictionary-based password attacks work.
-How password complexity affects the time required to recover a password.
-Why weak and predictable passwords are easier to compromise.
-The importance of using strong and unique passwords.

Working through both methods also helped me see that password cracking does not always require the same tools. The first task used JTR locally, while the second used browser-based NetworkWalks tools.

## Author 
Rachel Debbarma
