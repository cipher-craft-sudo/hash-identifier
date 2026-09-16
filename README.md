# Hash Identifier

A Python-based cybersecurity tool that identifies the likely algorithm or format of a hash string using its **prefix, length, and character set**.

## Features

* Identifies around **30 common hash formats**, including MD5, SHA-1, SHA-256, SHA-512, bcrypt, Argon2, and MD5-crypt.
* Detects hash formats using **prefix patterns, length, and character sets**.
* Recognizes formats such as **MySQL5, NTLM, NetNTLM, and DES crypt**.
* Detects non-hash inputs such as **JWTs and Base64 strings**.
* Provides **confidence levels** and a reason for each identification.
* Runs locally with **no network access or external services**.

## Example

```bash
python hash_identifier.py 5f4dcc3b5aa765d61d8327deb882cf99
```

### Output

```text
MD5
Confidence: Medium
Reason: 32 hexadecimal characters
```

## Technologies Used

* Python
* Regular Expressions
* Hash Format Analysis
* Cybersecurity Fundamentals


## Purpose

This project was built to understand how different hashing algorithms can be identified based on their **format, prefix, length, and character set**.

> **Note:** This tool identifies hash formats only. It does not crack or recover passwords.
