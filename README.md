# Hacking
<img src="https://img.shields.io/github/last-commit/evilsquirrelguy/hacking" /> <img src="https://img.shields.io/badge/status-in%20progress-yellowgreen">

**IMPORTANT INFORMATION:** All information in this GitHub repository is strictly for educational purposes, and I will not be held responsible if you use it for any other purpose, if you do decide to put your newly acquired knowledge to good use, you do so at your own risk and expense. Its not my fault if you end up in prison lol.

I made this repository so I have an easy place to find everything to do with hacking/viruses and so i can educate people about what you should watch out for in code (primarily the first one tho).

All the Information can be found on the Wiki

## Things you should do to protect yourself
This is a self-protection checklist, if you do all these things you are slightly safer.

#### Update to the latest version of your OS
This one's a commonly overlooked one, but a lot of people are still running old versions of Windows, slightly over 1% of all PCs around the world are on Windows XP, and Windows 7 still runs on over **25%** of PCs, both these Windows versions are heavily outdated, Windows 7 is from 2009 but Windows XP is from **2001**! These versions will no longer receive security updates so once a vulnerablilty is found, it's there forever (a long time!). Switching to Linux is also a good alternative, Linux runs on 2% of all PCs and is a lot safer than windows, as only 0,5% of viruses are meant for Linux as opposed to the nice big 98% that are for windows. If you have software that only runs on older versions of Windows, consider using a Virtual Machine (I suggest VirtualBox)

#### Have some common sense
Don't download software from dodgy sites, it's likely to have a virus. Don't download "free" or "cracked" versions of otherwise paid software, firstly its illegal, secondly, it's also likely to have a virus. Torrenting software is risky, you don't know where your file is coming from and it could be infected. If you're not sure about software being safe to use, decompile it, or if it's open source, read the source! If your software is from a shady site and it's obfuscated (can't be decompiled) then you should probably delete it. If your friend sends you some software (like a minecraft mod for example) don't assume it's safe just because they're your friend, ask the  for the source code, and if they don't want to disclose it, then don't trust the software.

#### Don't share log and config files (or your passwords!)
One way to hijack an account is by token-logging, this basically means you steal the "key" that the server uses to authenticate you and allow you to log into your account. For example, when you sign into the minecraft launcher, it generates a session token to authenticate you, this token allows you to log in, if someone steals it, they can log in as you until the token expires. Tokens can be found in various different places, but are usually found in the application's AppData folder in config and/or log files. These are usually unencrypted, so be very careful around these, and if someone asks you for these files, they are 100% trying to scam you. I don't even need to say this but just don't give out passwords, you'd have to be pretty stupid to do something like that. Are you?
