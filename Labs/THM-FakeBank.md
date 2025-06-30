# Lab: TryHackMe – Fake Bank Recon

## 🧠 Objective
Use directory brute forcing to find hidden endpoints and exploit a vulnerable transfer page.

## 🛠️ Tools Used
- `gobuster`: for directory brute force
- Kali terminal commands

## 🔍 Key Commands
```bash
gobuster -u http://fakebank.thm -w wordlist.txt dir
