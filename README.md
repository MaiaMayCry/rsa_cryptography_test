# RSA Cryptography Test

A Windows Forms proof-of-concept encryption application that implements RSA public-key cryptography for encrypting and decrypting messages with visual GUI interaction.

The application is designed to:

- Generate RSA key pairs for encryption and decryption
- Encrypt plaintext messages using RSA public-key cryptography
- Decrypt encrypted messages using the corresponding private key
- Persist private keys to a local file for later use
- Provide a user-friendly interface for encryption/decryption operations

## Features

- Windows Forms-based graphical user interface
- RSA key pair generation
- Text encryption using public key
- Text decryption using private key
- Private key storage and retrieval from `PrivateKey.txt`
- Visual feedback for encryption and decryption operations
- Multi-step workflow for secure message handling

## Requirements

- Windows OS (for Windows Forms)
- .NET Framework (version compatible with the project)
- Visual Studio or equivalent C# compiler

## Getting Started

1. **Clone or download the project**

```text
git clone https://github.com/MaiaMayCry/rsa\_cryptography\_test.git
```
2. **Open the project**
- Navigate to the `WindowsFormsApplication1` folder
- Open the project file in Visual Studio

3. **Build the project**
- Build the solution in Visual Studio

4. **Run the application**
- Execute the compiled `criptografia.exe` file or run directly from Visual Studio

## Usage

1. Enter plaintext in the top text box
2. Click the encrypt button to generate an encrypted message
3. Copy the encrypted text to the second text box
4. Extract the private key from the `PrivateKey.txt` file
5. Paste the private key into the third text box
6. Click the decrypt button to retrieve the original message
