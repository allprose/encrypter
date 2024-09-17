====================
Encryption/Decryption Tool
====================

This Python-based tool allows users to encrypt and decrypt text or files using AES encryption. The script automatically installs any missing libraries and provides a simple terminal interface for encryption and decryption tasks.

====================
Requirements
====================
1. Python 3.x
2. `cryptography` library (the script installs it automatically if missing)

====================
How to Run
====================

1. Run the script:
python3 encrypter.py (on Linux/macOS) 
python encrypter.py (on Windows)

2. The encryption tool will allow you to:
- Encrypt text
- Decrypt text
- Encrypt files
- Decrypt files

====================
How It Works
====================
1. **Salting**: A random salt is generated and used alongside the user-provided password to derive the encryption key, making encryption unique even if the same password is used multiple times.
2. **Password-Based Encryption**: The key is derived from the user-provided password using PBKDF2HMAC with SHA-256 hashing and 100,000 iterations.
3. **Automatic Library Installation**: The script automatically installs the `cryptography` library if it's not installed.

====================
Author EY
====================

