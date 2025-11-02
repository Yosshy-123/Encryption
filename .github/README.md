# Encryption - Local AES Encryption Tool

[日本語](./README.ja.md)

## Overview

This repository is an **offline-capable AES encryption tool that runs entirely in the browser**.

If you save and open [`index.html`](./index.html) locally, you can encrypt and decrypt text offline.

---

## How to use

### GitHub Pages

[https://yosshy-123.github.io/Encryption/](https://yosshy-123.github.io/Encryption/)

### Instructions

1. Enter the plaintext in the text input field and enter a passphrase in the password field.
2. Press the "Encrypt" button to display the encrypted text. To decrypt, press the "Decrypt" button with the same password.

---

## Implementation overview and important notes

* The encryption process is performed by JavaScript embedded in [`index.html`](./index.html).
* This implementation does not use the browser-native Web Crypto API.
* Password management is the user's responsibility. Short or simple passwords are easy to break, so a strong password is recommended.
* Even when running locally, be careful about how you store and share encrypted data. Consider sending via secure channels and storing it securely.

---

## Browser compatibility

Designed to work on modern browsers.

It may not work on older browsers or environments with limited capabilities, so we recommend using the latest browser versions.

---

## Contributing & Contact

Bug reports, improvement suggestions, and pull requests are welcome.

If you discover a security vulnerability, please contact *Yosshy_123@proton.me* if possible.
