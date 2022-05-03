# YBYB-590-capstone
## TeamMenber
Linghao Meng
Erdong Chen
## Brief Introduction
We use kali and Metasploit Framework to attack a Windows7 machine with CVE-MS17-010, get shell permissions then insert our implant into the target machine. Add the implant to the startup folder.
We can send the command message to the implant to encrypt some files and send it via email. Finally, we can send the "delete" command to delete our implant on the target machine, we will delete all logs and clear intrusion records.
### Attack CVE-MS17-010
Some of our attack instructions on kali are in `script`folder.
### Implant
`Sysupdate.py` and `Sysupdate.exe` are our implant script and its executable file.
### Local command sending client
`eternalBlue.py` is a script run on local mahine to send command to implant.
### Aes decrypt
We use aes to encrypt and decrypt the file, `aes_decrypt.py` is a script whick can decrypt the file in email.
