A recent cybersecurity incident has led to the discovery of suspicious network traffic. Your task is to perform a detailed analysis of the traffic and uncover the Host name and Windows user account name.

flag-format : AOC_CTF{Host name,Windows user account name}

We can find the Hostname in the following option:

<img width="706" height="438" alt="image" src="https://github.com/user-attachments/assets/7bcd7208-1b1f-4d4e-bcaf-7f32c2c38679" />

To find the Username, use the following command:

kerberos.CNameString

find the CName String and select “Apply as column” and we get the user name.

AOC_CTF{DESKTOP-GXMYNO2,steve.smith}

Network Traffic Analysis part 2:

AOC_CTF{OskiStealer}
