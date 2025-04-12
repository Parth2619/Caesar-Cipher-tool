# 🔐 Caesar Cipher Tool

A simple Caesar Cipher encryption and decryption tool built in Python. This program lets you encode or decode messages using a shift cipher, with a user-friendly interactive terminal interface.

## 📜 What is a Caesar Cipher?

The Caesar Cipher is one of the earliest and simplest ciphers known. It works by shifting each letter in the plaintext by a fixed number of positions down or up the alphabet.

For example, with a shift of 1:  
- `a` becomes `b`  
- `b` becomes `c`  
- ...  
- `z` becomes `a`

This tool can **encode** (encrypt) and **decode** (decrypt) messages using this method.

## 🛠 Features

- Encode and decode messages with a custom shift
- Handles non-alphabet characters without altering them
- Loop functionality to process multiple messages without restarting
- ASCII art logo via the `art` module for a fun UI touch

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- The `art` module

### Install Dependencies

```bash
pip install art
```

### Run the Program

```bash
python caesar_cipher.py
```

Follow the interactive prompts in your terminal:

```plaintext
Type 'encode' to encrypt, type 'decode' to decrypt:
Type your message:
Type the shift number:
```

## 🧠 Example

```plaintext
Type 'encode' to encrypt, type 'decode' to decrypt:
> encode
Type your message:
> hello world
Type the shift number:
> 5

Here is the encoded result: mjqqt btwqi
```

## 👨‍💻 Code Overview

The key function in the script is:

```python
def caesar(original_text, shift_amount, encode_or_decode):
```

It handles both encoding and decoding depending on the mode you select. The program keeps running until the user decides to exit.

## ✅ To-Do / Improvements

- Add support for upper-case letters (preserve original case)
- Add GUI version (Tkinter or web-based)
- Save encrypted/decrypted messages to a file
- Handle edge cases like very large shift values

## 🧡 Credits

- Built with Python by Parth Koshti
- ASCII art logo from the `art` package
