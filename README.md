# Easy Peasy - TryHackMe Writeup

This repository contains my writeup for the TryHackMe room Easy Peasy.

The room focuses on basic enumeration, web discovery, hash cracking, steganography, SSH access, and Linux privilege escalation through a misconfigured cron job.

## Room Summary

Easy Peasy starts with service enumeration using Nmap, followed by web directory brute-forcing with GoBuster. Hidden web directories reveal encoded values, hashes, and clues that are used to progress through the machine.

After discovering credentials through hash cracking and steganography, SSH access is gained as a low-privileged user. The final privilege escalation is achieved by abusing a writable script executed by a root cron job.

## Topics Covered

* Nmap service enumeration
* GoBuster directory enumeration
* Source code inspection
* Base64 and Base62 decoding
* Hash identification and cracking
* Steganography with steghide
* SSH login on a non-standard port
* ROT13 decoding
* Linux privilege escalation through cron job abuse
* SUID bash privilege escalation

## Files

## Writeup

./easy-peasy-tryhackme-writeup.pdf

## Note

This writeup is for learning and documentation purposes only.
