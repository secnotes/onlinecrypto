# Online Crypto Tool

[English](README.md) | [中文](README_CN.md)

A frontend encryption/decryption tool based on Crypto.js. All operations are performed locally in your browser - your data never leaves your device.

## Features

### Symmetric Encryption
- **AES** - Advanced Encryption Standard, the most popular symmetric encryption algorithm
- **DES** - Data Encryption Standard (legacy, recommend using AES instead)
- **TripleDES** - Triple DES, more secure than DES but slower
- **Blowfish** - Fast, secure symmetric encryption with variable key length
- **Rabbit** - High-performance stream cipher, suitable for real-time encryption
- **RC4** - Stream cipher, simple and fast
- **RC4Drop** - Improved RC4 version with better security

### Hash Algorithms
- **MD5** - 128-bit hash (not recommended for security purposes)
- **SHA-1** - 160-bit hash (being phased out)
- **SHA-224** - SHA-2 family, 224-bit hash
- **SHA-256** - SHA-2 family, 256-bit hash, widely used
- **SHA-384** - SHA-2 family, 384-bit hash
- **SHA-512** - SHA-2 family, 512-bit hash, highly secure
- **SHA-3** - Next generation hash algorithm based on Keccak
- **RIPEMD-160** - 160-bit hash

### HMAC
- Hash-based Message Authentication Code for data integrity and authenticity verification

### Encoding Tools
- **Base64** - Base64 encode/decode
- **Hex** - Hexadecimal encode/decode
- **Latin1** - ISO-8859-1 encode/decode
- **UTF-8** - UTF-8 byte encoding viewer
- **Universal Converter** - Auto-detect input format and convert to all other formats

Supported input formats for Universal Converter:
- UTF-8 String (plain text)
- Hex (e.g., `48656c6c6f`)
- Base64
- Inline (e.g., `\x48\x65\x6c\x6c\x6f`)
- C-Array (e.g., `unsigned char data[] = { 0x48, 0x65, 0x6C };`)
- Python (e.g., `data = [ 0x48, 0x65, 0x6C ]`)

### Key Derivation
- **PBKDF2** - Password-based key derivation function
- **EvpKDF** - OpenSSL EVP key derivation function

## Advanced Options

### Cipher Modes
- CBC (Cipher Block Chaining) - Recommended
- ECB (Electronic Codebook) - Not recommended (insecure)
- CFB (Cipher Feedback)
- OFB (Output Feedback)
- CTR (Counter Mode)

### Padding Modes
- PKCS#7 (Most common)
- Zero Padding
- No Padding
- ISO/IEC 9797-1
- ANSI X.923

### Key Formats
- String (UTF-8)
- Hex
- Base64
- Latin1

## Security & Privacy

- All encryption/decryption operations are performed locally in your browser
- No data is uploaded to any server
- Supports auto-generated random keys
- Dark/Light theme support
- Chinese/English language support (auto-detect based on browser settings)

## Usage

Simply open `index.html` in your browser. No installation or server required.

## Technology

- Pure HTML/CSS/JavaScript
- [Crypto.js](https://github.com/brix/crypto-js) for cryptographic operations
- Responsive design for desktop and mobile

## License

MIT License

## Author

[Security Notes](https://github.com/secnotes)