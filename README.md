# Data Encryption/Decryption Software

This Java project is a simple command-line-based Data Encryption/Decryption software that allows users to encrypt and decrypt text using a basic algorithm. The software provides options to encrypt a given text or decrypt an encrypted text, either manually inputted or read from a file.

## How it works

The software uses a simple encryption algorithm that involves shifting characters in the text by a certain password-dependent amount. The password is incremented with each character to provide a varying encryption pattern. Decryption reverses this process to retrieve the original text.

## Getting Started

To use the software, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://https://github.com/RastogiTanishka/EndeCry.git
   ```

2. Compile the Java code:

   ```bash
   javac main.java
   ```

3. Run the compiled code:

   ```bash
   java main
   ```

## Usage

1. Upon running the program, you will be presented with a menu:

   ```
   DATA ENCRYPTION/DECRYPTION SOFTWARE v1.00

   Choose from one of the options below :

   1. Encryption of a text
   2. Decryption of a text
   3. Exit
   ```

2. Choose an option by entering the corresponding number.

### Encryption

- Option 1 allows you to encrypt text.
  - Sub-options:
    - Enter a text manually.
    - Choose a .txt or .dat (binary) file by giving its name and extension.

### Decryption

- Option 2 allows you to decrypt text.
  - Sub-options:
    - Paste the text to decrypt.
    - Decrypt the text saved to a file.

### Exiting

- Option 3 exits the program.

## Notes

- The program uses a simple shifting algorithm for encryption/decryption.
- Pay attention to the prompts for manual input or file input.

Feel free to explore and experiment with the software!

**Note:** This software is created for educational purposes, and the encryption algorithm used may not be suitable for secure applications. Always use secure and established encryption methods for real-world scenarios.
