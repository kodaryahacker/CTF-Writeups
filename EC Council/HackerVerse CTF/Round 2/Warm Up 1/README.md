<img width="1119" height="499" alt="image" src="https://github.com/user-attachments/assets/bc5b608b-4bb1-4a96-9ce6-1812fb023cd7" />

A password protected .zip file was given with a flag.txt file inside. I used JohnTheRipper tool for this challenge.
I started by saving the hash of the .zip file.
<img width="1607" height="124" alt="Screenshot 2025-07-29 104556" src="https://github.com/user-attachments/assets/44782548-f19d-4214-8371-7aceca288fb8" />

Then used John to crack the password of the file using the hash of the file and rockyou.txt wordlist.
<img width="1127" height="258" alt="Screenshot 2025-07-29 104621" src="https://github.com/user-attachments/assets/0e7fb437-9f4d-4815-9e04-5c0b37b1732b" />

After finding the password of the .zip file, I unlocked it and found the flag.
<img width="955" height="240" alt="Screenshot 2025-07-29 104647" src="https://github.com/user-attachments/assets/d4e4acd7-2d4d-4ef9-9667-6642cf39a0f2" />

Flag: CTF{TomatoMan}
