## Day 24 – John the Ripper

### Tool Name

**John the Ripper**

### Category

Password Cracking / Hash Cracking

### Developer

Alexander Peslyak

### Overview

**John the Ripper** is a powerful open-source tool used to **crack passwords by analyzing password hashes**.

Instead of attacking live login systems like Hydra, John works **offline** by taking encrypted password hashes and attempting to recover the original passwords using various techniques.

It supports a wide range of hash types and is widely used in **penetration testing, forensics, and password auditing**.

### Primary Purpose

The primary purpose of John the Ripper is to **crack password hashes to identify weak or easily guessable passwords**.

### Key Features

* Supports many **hash formats** (MD5, SHA, NTLM, bcrypt, etc.)
* Performs **dictionary attacks** using wordlists
* Advanced **brute-force (incremental) mode**
* Custom **rule-based password mutations**
* Detects weak passwords quickly
* Supports GPU acceleration (Jumbo version)
* Cross-platform (Linux, Windows, macOS)

### How It Is Used in Cybersecurity

John the Ripper is widely used in **password auditing and digital forensics**.

Some common uses include:

* Cracking **password hashes from databases**
* Auditing password strength in organizations
* Recovering lost passwords (authorized use)
* Testing effectiveness of password policies
* Supporting forensic investigations
* Identifying weak or reused credentials

It helps answer:
**“How strong are these stored passwords?”**
### Why Beginners Should Know This Tool

John the Ripper is essential because **password security is a major weak point in real systems**.

It helps beginners:

* Understand how **password hashing and cracking works**
* Learn offline attack techniques
* Practice using **wordlists and rules**
* Gain insight into password weaknesses
* Build skills in **pentesting and forensics**

### Official Website

[https://www.openwall.com/john](https://www.openwall.com/john)

### Quick Summary

John the Ripper is a **password hash cracking tool** used to recover passwords from encrypted hashes. It is widely used in cybersecurity for **password auditing, forensic analysis, and testing password strength**.
