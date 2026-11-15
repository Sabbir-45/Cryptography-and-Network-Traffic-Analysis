
# Cyber Network Intelligence & Cryptography

## Assignment Overview

This assignment focuses on the fundamentals of cryptography, encryption techniques, hashing algorithms, password security, practical hash identification and cracking, and network traffic analysis using Wireshark.

## Objectives

- Understand the fundamentals and types of cryptography.
- Learn Symmetric and Asymmetric Encryption techniques.
- Identify common hashing algorithms and understand password security.
- Perform practical hash identification and cracking.
- Capture and analyze basic network traffic using Wireshark.

---

## Part 1: Theoretical Questions

Answer the following questions with proper technical explanations and practical examples.

1. What is Cryptography? Explain its importance in data security.
2. What is the difference between Symmetric and Asymmetric Cryptography?
3. What are AES and DES? Explain their basic differences.
4. What are Public Keys and Private Keys? Explain their roles in RSA.
5. What is Hashing? Explain the differences between MD5, SHA-1, and SHA-256.
6. What is Salt in password hashing? Why should passwords never be stored in plaintext?
7. What is Hash Cracking? Explain Dictionary Attack and Brute Force Attack.

---

## Part 2: Practical Tasks

### A. Hash Identification & Cracking

Identify the hash types and attempt to recover the original plaintext values of the following 10 hash samples.

**Tasks:**

- Identify the possible hashing algorithm for each hash.
- Use appropriate tools such as Hash-Identifier, Hashcat, or John the Ripper.
- Select an appropriate attack mode and wordlist.
- Attempt to crack each hash and recover its plaintext value.
- Document the commands and tools used.
- If a hash cannot be cracked, explain the analysis and attempts made.

**Hash Samples:**

**1.**
```text
3580c9267518807d14803ab6821fa067b4dba1210a4148a243b9e9383bae6a1e
```

**2.**
```text
2c4cc4fb10563f03af07c95a68c7d08ff025d5ef6a4064fc0244b27aadb5c8fad1b12184aaa37454f58b205bd852b694986b79e78fc790bc06ce63f57868cd0d
```

**3.**
```text
36d4e8faed0ed74720ce8729da1d181c9287f85c7790c33760f7a5a34bdec62c660c66922968a4329491d9d9765f1dcbc403426fa4999890c5c17d5ed029ccd4
```

**4.**
```text
59236c42845bb5b0206837b492ed18a2
```

**5.**
```text
$2a$06$2AMtXwnyKrm.q1KPOCG0V.LtXjUxJIQZmYTUj1P7d4BvtCbAa/9yO
```

**6.**
```text
fac889266af6336992cca9f1f7d390869f4d7a34c65f108c2dc1520a6b6d8677ba6e88e168203b6a495ad39f8ac7364baf3d6652e54a2b11d882e75d76b861fe
```

**7.**
```text
9ea73088f615ae9353f576a11ffd08c853c04e3a1e65b71365d82ccfca43d196e98bddfa1e52b48fd9466be000eedd7ca8ad132d5d7ac7d936d2afd27d0e7823
```

**8.**
```text
38de90475bb334fb3dea5d54f250500aba60fe2c6158115d342b06bcb46e39bf
```

**9.**
```text
ade3f083466787749e7fea347c6ce0a410a1a525f3d2eba7d714fae9f1e5f626
```

**10.**
```text
$2a$12$2X8SpHk7YoxLSeAxTOdUSOTV8tUc8Zm0qrQ1ysgB67.JjkERRBZfe
```

### B. Basic Packet Capture & Analysis with Wireshark

Perform basic network traffic capture and analysis using Wireshark.

**Tasks:**

- Start a live packet capture on your active network interface.
- Visit a website and observe the captured packets.
- Identify the Source IP and Destination IP addresses.
- Identify DNS Query and DNS Response packets.
- Identify TCP packets and their Source and Destination Ports.
- Apply basic display filters for DNS, TCP, HTTP, and HTTPS traffic.
- Save your packet capture as a PCAP file.
- Capture screenshots showing your analysis.

**Tools:** Wireshark and TShark.

---

## Part 3: Practical Submission Requirements

For each practical task, submit the following:

1. Task Name.
2. Tools Used.
3. Commands and Methodology.
4. Hash Identification Results (for Task A).
5. Recovered Plaintext Values (for Task A).
6. Packet Analysis Findings (for Task B).
7. Relevant Screenshots and Terminal Outputs.
8. PCAP File (for Task B).

---

**Topic:** Cyber Network Intelligence & Cryptography  
**Domain:** Cybersecurity  
**Practical Tools:** Hash-Identifier | Hashcat | John the Ripper | Wireshark | TShark
