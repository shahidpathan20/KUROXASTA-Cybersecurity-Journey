# Cryptography Basics

## importance of cryptography

cryptography is the technique of protecting information by converting it into a form that unauthorized people cannot understand.

It helps keep data secure when we store it or send it over a network.

example: Imagine you want to send your friend a secret message: HELLO.

## 2. Importance of Cryptography

Cryptography is important for these five reasons:

1. Confidentiality: Keeps private information secret from unauthorized people.
2. Integrity: Helps detect whether data has been changed or tampered with.
3. Authentication: Helps verify the identity of a user, server, or device.
4. Secure communication: Protects information exchanged through HTTPS websites and other secure communication systems.
5. Data protection: Helps protect sensitive information such as passwords, financial data, and personal information

### key terms

- Plaintext: Original readable data.
- Ciphertext: Encrypted data.
- Encryption: Converting data into a protected form.
- Decryption: Recovering the original data.
- Key: A value used by a cryptographic algorithm.
- Hashing: Producing a one-way digest of data; unlike encryption, it isn't designed to be reversed.

## plaintext to ciphertext

### 1. What is Plaintext?

Plaintext is the original, readable message before encryption.

**Example:** HELLO WORLD

### 2. What is Ciphertext?

**Example:** KHOOR ZRUOG

Ciphertext is the encrypted form of a message that is not normally readable without decrypting it.

### 3. What is Encryption?

Encryption is the process of converting plaintext into ciphertext using an encryption method and, when required, a key.

**Example:**

- Plaintext: HELLO
- Encryption method: Caesar Cipher (shift by 3)
- Ciphertext: KHOOR

### 4. What is Decryption?

Decryption is the process of converting ciphertext back into its original readable form using the appropriate method and key.

**Example:**

- Ciphertext: KHOOR
- Decryption: Shift each letter backward by 3
- Plaintext: HELLO

### 5. What is the Caesar Cipher?

The Caesar Cipher is a simple substitution cipher that shifts each letter of the alphabet by a fixed number of positions.

for a shit 3

| Letter | Shift by 3 |
|---|---|
| A | D |
| B | E |
| C | F |
| D | G |
| X | A |
| Y | B |
| Z | C |

When the alphabet ends, the shift wraps around to the beginning.

### key terms

- **Plaintext:** Original readable message.
- **Ciphertext:** Encrypted message.
- **Encryption:** Plaintext → Ciphertext.
- **Decryption:** Ciphertext → Plaintext.
- **Cipher:** An algorithm used to encrypt and decrypt information.
- **Key:** Information that controls how encryption or decryption works.

## Types of Encryption

### Symmetric Encryption

Symmetric encryption uses the **same secret key** to encrypt and decrypt data.

### 2. Asymmetric Encryption

Asymmetric encryption uses **two different keys**: a public key and a private key.

## BASIC MATH

### 1. XOR operation (Exclusive OR)

XOR is a bitwise operation used in cryptography. It compares two bits and returns `1` when they are different, and 0 when they are the same.

rules

| A | B | A XOR B |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

different=1: same=0

### 2. Modulo operation (MOD)

Modulo gives you the remainder after division.
