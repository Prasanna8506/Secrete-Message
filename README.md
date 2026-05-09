# Secrete-Message

A simple message encryption and decryption web application built using HTML and JavaScript.

## Features

- Encrypt text into ASCII/Unicode values
- Decrypt encrypted values back into text
- Copy encrypted message to clipboard
- Simple and beginner-friendly interface

## Technologies Used

- HTML
- JavaScript

## How It Works

### Encryption
Each character is converted into its ASCII/Unicode value using:

```javascript
charCodeAt()
```

Example:

HELLO

becomes:

72 69 76 76 79

### Decryption
The encrypted numbers are converted back into text using:

```javascript
String.fromCharCode()
```

## Project Structure

```text
project-folder/
│
├── index.html
├── encrypt.html
├── decrypt.html
└── README.md
```

## How To Run

1. Download the project
2. Open `index.html` in your browser
3. Start encrypting and decrypting messages

## Author

Prasanna Kulkarni

## License

This project is open source and free to use.
