### Challenge
https://drive.google.com/drive/folders/1axuBav4DyzfGU6_XPHmen9KRZxKGOhZM?usp=sharing

---

### **Description**
It started as a routine system optimization. A Finance employee executed a tool promising a faster PC, but instead, it delivered a nightmare. Within minutes, the `LabData` folder was encypted, and a ransom demand appeared.

Forensic investigators suspect a Fileless Ransomware attack—a ghost in the machine that leaves no trace on the disk. A memory dump was captured while the threat was still active.

**Your Mission:** Analyze the memory dump, find the attacker's traces, and answer the following questions!

---

### **Questions**

**Q1.** Identify the name and PID of the legitimate Windows process that the attacker compromised to hide the malicious payload? (e.g., `svchost.exe:1234`)

**Q2.** IP and Port of the attacker's C2 server? (e.g., `10.0.0.1:4444`)

**Q3.** The memory address (Start VPN) where the first shellcode was injected? (e.g., `0x12345670000`)

**Q4.** Name of the C2 framework used? `lowercase`

**Q6.** What is the MD5 hash of the original ransomware executable recovered from the memory of the infected process? `lowercase`

**Q5.** Programming language used for the Ransomware payload? `lowercase`

**Q7.** The secret Key used to encrypt the files? `plaintext`

**Q8.** Decrypt file to find the flag: `FLAG{...}`

**Final Flag Format:** `DFIR{Q1_Q2_Q3_Q4_Q5_Q6_Q7_Q8}`
