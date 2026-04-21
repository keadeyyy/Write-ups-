# 📊 Individual Progress Scorecard

## Daily Training Log

**Date:** February 27, 2026 | **Training Day:** 13/90
### 1. Time Investment

- [✔] Training time today: 5 hours
- [✔] Goal met? (Yes/No)
- [✔] Consistency streak: 13 days

**Points:**

- 2+ hours = 10 points
- 1-2 hours = 5 points
- <1 hour = 2 points
- Missed day = 0 points (streak resets)

### 2. Challenge Completion

| Difficulty      | Challenges Solved | Points Earned |
| --------------- | ----------------- | ------------- |
| Easy            | _____ × 5 pts     | _____         |
| Medium          | 1 × 15 pts    | 15         |
| Hard            | 3 × 30 pts    | _____         |
| Expert          | _____ × 50 pts    | _____         |
| **Daily Total** |                   | **105**     |

### 3. Quality Indicators

- [✔] Created writeup for at least 1 challenge (+10 pts)
- [✔] Reviewed 3+ writeups from others (+5 pts)
- [✔] Learned new technique/tool (+10 pts)
- [ ] Updated cheat sheet (+5 pts)
- [ ] Practiced timed challenge (+5 pts)

**Quality Points Total:** 45

### 4. Category Focus Today

Which categories did you practice?

- [ ] Web Exploitation
- [ ] Binary Exploitation / Pwn
- [✔] Cryptography
- [ ] Reverse Engineering
- [ ] Forensics
- [ ] OSINT
- [ ] Other: ___________

**Primary Specialty:** 300 minutes

**Secondary Specialty:** 0 minutes

**Other Categories:** 0 minutes

### 5. Reflection (Qualitative)

**What went well today?**

- I was able to understand how the RSA parity oracle works and how a single bit of information (even/odd)
  can be used to fully recover plaintext using a binary search approach.

**What challenged you?**

- Visualizing how repeated ciphertext manipulation (multiplying by 2e)
  affects the plaintext and how the bounds converge during the attack.
  
**Key learning:**

- Even minimal information leakage (like parity) can completely break RSA if the system allows repeated queries.
  This highlights the importance of secure padding and limiting oracle access.
  
**Tomorrow's focus:**

- Explore more attacks related to RSA and DSA, especially those involving weak randomness or improper implementations.
