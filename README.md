# Equil — Monthly Report (encrypted)

This repository hosts a single **encrypted** page. It contains no readable business data.

`docs/index.html` is ciphertext: AES-256-GCM, with the key derived from a passphrase via
PBKDF2-SHA256 (600,000 iterations). Decryption happens in the reader's browser using
WebCrypto — nothing is transmitted anywhere, and there is no server or API involved.

Without the passphrase there is nothing here to read.

Built from a separate private repository. Ask G for access to the source.
