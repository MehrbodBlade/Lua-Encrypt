# Lua-Encrypt

Lua-Encrypt is a robust Python tool designed to securely encrypt and decrypt Lua files using industry-standard AES-256 encryption. Protect your Lua scripts with strong encryption to prevent unauthorized access and modifications.(beta version )

## Features

- **AES-256 Encryption**: Provides strong security for your Lua files.
- **Password-Based Encryption**: Uses a password provided by the user to generate an encryption key.
- **Handles Multiple Files**: Easily encrypt or decrypt all Lua files within a directory.
- **User-Friendly Interface**: Simple command-line interface for easy operation.



## Installation

### Prerequisites

Ensure that you have Python installed on your system. This script requires Python 3.x and the following Python packages:
- `pycryptodome`

### Steps

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/MehrbodBlade/Lua-Encrypt.git
    cd Lua-Encrypt
    ```

2. **Install Required Packages**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Prepare Your Lua Files**:
    - Place the Lua files you want to encrypt or decrypt in the `input` directory.

2. **Run the Script**:
    ```bash
    python lua_encryption.py
    ```
    - You will be prompted to choose whether to encrypt or decrypt the files.
    - You will also be asked to provide a password that will be used for encryption/decryption.

3. **Result**:
    - The encrypted or decrypted files will be saved in the `result` directory.

## Example

To encrypt files:
```bash
Do you want to encrypt or decrypt the files? (e/d): e
Enter the password for encryption/decryption: [YourPassword]
```
## Note 

- Password Security: Ensure that you use a strong and unique password to enhance the security of your encrypted Lua files.
- File Safety: Always back up your original Lua files before running encryption or decryption operations.

## Contributing

- Contributions are welcome! Please fork the repository and submit a pull request with your changes.


# License

This project is licensed under the MIT License

## Contact
- For issues or questions, please open an issue.
