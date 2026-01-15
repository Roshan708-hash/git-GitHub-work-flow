\# Git Installation \& Setup Guide (Android – Termux)



This guide is for \*\*Android users\*\* who want to use Git using \*\*Termux\*\*.

No prior knowledge required.



---



\## What is Termux?

\- Termux is an Android app that gives you a \*\*Linux terminal\*\*

\- We use it to run Git on mobile



---



\## 1. Install Termux (Android)



⚠️ \*\*Do NOT install Termux from random websites\*\*



Download from \*\*Google Play Store\*\*:



👉 https://play.google.com/store/apps/details?id=com.termux



Open Termux after installation.



---



\## 2. Update Termux Packages



In Termux, type:



```bash

pkg update \&\& pkg upgrade

```





\## 1. Install Git in Termux (Android)

```bash

pkg install git

```



```bash

git --version

```



\## 4. Setup Git



```bash

git config --global user.name "Your Name"

git config --global user.email "youremail@gmail.com"


```



\## 5. Create SSH Key (For GitHub)



```bash
ssh-keygen -t ed25519 -C "your-email"
```



\## 6. Read / Copy SSH Key

```bash
cat ~/.ssh/id\_rsa.pub

```

## 7. Add SSH Key to GitHub



Open GitHub in browser



Login



Go to Settings



Open SSH and GPG keys



Click New SSH key



Paste copied key



Save

👉 \[Follow GitHub setup](./github\_setup.md)



