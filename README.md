> 🎯 **eCPPTv3 (INE Security) Preparation**  
> This repository is part of my study and hands-on practice for the  
> **eCPPTv3 – eLearnSecurity Certified Professional Penetration Tester** certification.  
> All content has been developed and used exclusively in controlled environments  
> such as **TryHackMe** and other offensive security labs.

---

# 🧠 Brainpan – Buffer Overflow (TryHackMe)

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![TryHackMe](https://img.shields.io/badge/TryHackMe-CTF-red)
![Status](https://img.shields.io/badge/Status-Completed-success)

This repository contains the **Python 3 scripts** I used to solve the **Brainpan** machine on **TryHackMe**, which focuses on exploiting a **classic buffer overflow** vulnerability in a Windows **`.exe`** binary.

> ⚠️ **Educational use only**. All material is intended for learning purposes in controlled environments (CTFs / labs).

---

## 📌 Machine Overview

**Brainpan** is a beginner–intermediate level machine that introduces fundamental concepts such as:

- Buffer overflow exploitation in Windows binaries (`.exe`)
- **EIP** control
- Payload creation and testing
- Remote exploitation via TCP sockets
- Exploit automation using **Python 3**

---

## 🛠️ Repository Contents

📂 **Included scripts**:

- Scripts to:
  - Identify the correct offset
  - Verify EIP control
  - Send custom payloads
  - Automate interaction with the vulnerable service
- Clean, commented, and reusable code
- Written entirely in **Python 3** using standard libraries

> All scripts are intended to be executed from Linux-based systems (Kali / Parrot / similar).

---

## 🚀 Usage

Clone the repository, **navigate into the directory, and run the scripts** according to the exploitation stage:

```bash
git clone https://github.com/yourusername/brainpan-buffer-overflow.git
cd brainpan-buffer-overflow
python3 exploit.py
```
Remember to change the IP Address and the port in each file!
