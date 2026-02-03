## Cryptography Practice Lab

### Caesar Cipher

This repository contains solutions for a cryptography lab focused on the **Caesar Cipher**, completed both **manually** and **in JavaScript**.


## Concepts Covered

* Caesar Cipher encryption (shift right)
* Caesar Cipher decryption (shift left)
* Alphabet wrap-around using modulo (`% 26`)
* ASCII character codes in JavaScript

---

### Part 1: Manual Caesar Cipher

* **Encryption:** Shift letters to the right by a fixed number
* **Decryption:** Shift letters to the left by a fixed number

Examples completed in `caesar_cipher.txt`.

---

## Part 2: Caesar Cipher in JavaScript

Implemented in `caesar.js`:

### Functions included:

* `caesarEncrypt(text, shift)`
* `caesarDecrypt(text, shift)`

### Key logic:

* Uppercase letters use ASCII base **65**
* Lowercase letters use ASCII base **97**
* Wrap-around handled using modulo `26`

## How to Run

Make sure Node.js is installed, then run:

```
node caesar.js
```

Expected output:

```
Khoor Zruog
Hello World
```

---

## Key Formula

* **Encrypt:** `(position + shift) % 26`
* **Decrypt:** `(position - shift + 26) % 26`

---
