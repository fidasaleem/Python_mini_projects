# Vigenère Cipher – Python Implementation

This mini-project implements a simple **Vigenère Cipher**, a classical encryption technique that uses a repeating key to shift letters in the alphabet.

The program supports:
- Encrypting a message  
- Decrypting a message  
- Handling spaces and non-alphabet characters  
- Automatic key cycling  

---

## 🔑 How It Works
The Vigenère Cipher shifts each letter of the message based on the corresponding letter of the key.  
For example, if the key is **python**, each letter contributes a different shift value.

This script defines three main functions:

- `vigenere(message, key, direction=1)`  
- `encrypt(message, key)`  
- `decrypt(message, key)`

---

## 📌 Example Used in This Project

**Encrypted text:**

```bash
mrttaqrhknsw ih puggrur
```

**Key:**

**Output after decryption:**

your original decrypted message will appear here


---

## ▶️ How to Run

1. Make sure you have Python installed (Python 3 recommended).
2. Save the script as `cipher.py`.
3. Run it:

python cipher.py

---

## 📝 Notes
- Non-alphabet characters (spaces, punctuation) are preserved.
- The key repeats automatically if shorter than the message.
- Only lowercase letters are processed (uppercase is converted automatically).

---

## 👤 Author
Fathima Fida 
