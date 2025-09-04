# Cryptography Libraries and Tools for CTF Challenges

Just like **pwntools** is the go-to library for binary exploitation, there are several Python (and other language) libraries/packages that are extremely useful for **cryptography CTF challenges**. These can help automate solving tasks, analyze math-heavy schemes, and attack weak crypto.

---

## 🔑 Core Crypto Libraries for CTF Work

### 1. [PyCryptodome](https://www.pycryptodome.org/)
- Actively maintained fork of PyCrypto.  
- Implements AES, RSA, ECC, SHA, HMAC, etc.  
- Useful for building quick scripts to attack or manipulate crypto.  
- Example: generate RSA keys, implement padding oracles, play with AES modes.

---

### 2. [SageMath](https://www.sagemath.org/)
- Full-fledged math system (Python-like syntax).  
- Excellent for number theory: factoring, modular arithmetic, elliptic curves.  
- Commonly used in RSA/ECC CTF challenges.  
- Standard toolkit in many high-level crypto writeups.

---

### 3. [gmpy2](https://pypi.org/project/gmpy2/)
- Python bindings for GMP (fast big integer arithmetic).  
- Efficient modular exponentiation, GCD, inverses.  
- Great for RSA challenges involving huge numbers.  
- Much faster than Python’s built-in operations.

---

### 4. [Sympy](https://www.sympy.org/)
- Symbolic math library for Python.  
- Can solve equations, modular arithmetic, and some discrete log problems.  
- Handy for algebraic “homebrew crypto” challenges.  

---

### 5. [RsaCtfTool](https://github.com/RsaCtfTool/RsaCtfTool)
- Designed specifically for **breaking weak RSA keys**.  
- Implements attacks: Wiener's attack, Fermat factorization, common modulus, small exponents, etc.  
- Can directly decrypt ciphertext if the key is vulnerable.  
- A must-have for RSA CTF problems.

---

### 6. [CryptoHack Utilities](https://github.com/cryptohack/cryptohack)
- Helper functions for the CryptoHack platform.  
- Includes modular inverses, LFSRs, encoding/decoding utilities, etc.  
- Lightweight and challenge-focused.  

---

## 🛠 Other Helpful Libraries/Tools
- **[bitstring](https://github.com/scott-griffiths/bitstring)** – for bit-level manipulation.  
- **[pwntools](https://docs.pwntools.com/en/stable/)** – not crypto-specific, but great for networking in remote challenges.  
- **[factordb-pycli](https://github.com/ryosan-470/factordb-pycli)** – query [factordb.com](http://factordb.com) to factor large integers automatically.  
- **[z3-solver](https://github.com/Z3Prover/z3)** – SMT solver for algebraic or modular equation systems in custom crypto.  
- **[fpylll (Lattice Reduction)](https://gith)**
