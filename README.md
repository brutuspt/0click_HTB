# 0click_HTB

This repository contains exploit scripts which require zero additional interaction by the attacker or victim, that's why they are  0-click exploit scripts.
I've solved these 16 HackTheBox machines with the objective to help me study for the OSWE certification.

Most of these scripts either allow you to obtain a reverse shell on the target machine or it displays a SSH private key of a user inside the box.

Disclaimer:
Personally I like to proxy every request with Burp, in order to make it easier to debug the requests being sent but in this case I decided to comment out that part of the code.

#### Sorted by specific Vulnerability

##### XSS

- Schooled (Medium)

##### SSTI

- RedPanda (Easy)
- Doctor (Easy)

##### Serialization

- Arkham (Medium)
- Celestial (Medium)
- JSON (Medium)

##### SSRF

- Forge (Medium)
  

##### File Upload

- Popcorn (Medium)
- Vault (Medium)
- Falafel (Hard)

##### Type Juggling

- Falafel (Hard)

##### SQLi

- Popcorn (Medium)
- Shared (Medium)
  

##### LFI

- Unattended (Medium)
- Monitors (Hard)

##### HTTP Smuggling

- Sink (Insane)


---

### Example Proofs:


##### Falafel machine:

![image](https://github.com/brutuspt/0click_HTB/assets/98529536/e251f042-e3d3-417b-a288-26858c5eac13)



##### Help machine:
![image](https://github.com/brutuspt/0click_HTB/assets/98529536/99fc48da-877c-48df-9f8c-569a1de5a352)


##### Schooled machine:
![image](https://github.com/brutuspt/0click_HTB/assets/98529536/46519356-e99d-4540-a239-b6d204ea6042)

