## Crypto Hash

### Project Description

Crypto Hash is a command-line tool that provides basic cryptographic operations, including file and text hashing. It utilizes the Python cryptography library and offers a user-friendly interface for secure and efficient hashing tasks.

### Installation

To install Crypto Hash, ensure you have Python 3 or higher and pip installed. Then, run the following command:

```
pip install crypto-hash
```

### Usage Examples

```
# Compute SHA-256 hash of a file
crypto-hash hash-file -a sha256 file.txt

# Compute MD5 hash of a string
crypto-hash hash-text -a md5 "Hello World"

# Verify the integrity of a file using its hash
crypto-hash verify-file -f original.txt -h original.txt.sha256
```

### Security Warnings

Use Crypto Hash cautiously, as it involves handling sensitive cryptographic data. Ensure you follow best practices for data security, including strong passwords and secure storage methods.

### License

Crypto Hash is licensed under the GNU General Public License v3.0. It is owned and maintained by CY83R-3X71NC710N.