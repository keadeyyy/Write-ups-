# 📊 Individual Progress Scorecard

## Daily Training Log

**Date:** February 28, 2026 | **Training Day:** 14/90

### 1. Time Investment

- [✔] Training time today: 5 hours
- [✔] Goal met? (Yes/No)
- [✔] Consistency streak: 14 days

**Points:**

- 2+ hours = 10 points
- 1-2 hours = 5 points
- <1 hour = 2 points
- Missed day = 0 points (streak resets)

### 2. Challenge Completion

| Difficulty      | Challenges Solved | Points Earned |
| --------------- | ----------------- | ------------- |
| Easy            | 1 × 5 pts     | 5         |
| Medium          | _____ × 15 pts    | _____         |
| Hard            | 3 × 30 pts    | _____         |
| Expert          | _____ × 50 pts    | _____         |
| **Daily Total** |                   | **95**     |

### 3. Quality Indicators

- [✔] Created writeup for at least 1 challenge (+10 pts)
- [✔] Reviewed 3+ writeups from others (+5 pts)
- [✔] Learned new technique/tool (+10 pts)
- [ ] Updated cheat sheet (+5 pts)
- [ ] Practiced timed challenge (+5 pts)

**Quality Points Total:** 35

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

- I successfully applied the XOR operation to transform characters and reveal the hidden string
  and how weak or reused nonces (k) in DSA can lead to private key recovery, including both brute-force
  attacks and attacks using repeated nonces.

**What challenged you?**

- Understanding how XOR operations affect ASCII values when applied to characters.
- Understanding the mathematical relationship between k, the signature values (r, s),
  and how they can be rearranged to solve for the private key.

**Key learning:**

- XOR is a fundamental operation used in many cryptographic algorithms to transform or encrypt data.
- The nonce k must always be random and unique. Any weakness or reuse in k directly exposes the private
  key, making the entire system insecure.

**Tomorrow's focus:**

- Continue practicing cryptographic attacks and focus on strengthening understanding of modular arithmetic and number theory.
