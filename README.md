# Cipher Website

![Cipher Website Screenshot]([image](https://github.com/user-attachments/assets/c5536f2d-6e55-48a5-81f7-e0bb6b0ea602)
) <!-- Add a screenshot if available -->

A web application that allows users to encrypt and decrypt text using various cipher algorithms, including AES, Caesar, Monoalphabetic, Playfair, and Vigenere ciphers. Built with HTML, CSS, and JavaScript.

## Table of Contents
- [Features](#features)
- [Algorithms](#algorithms)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)
- [Screenshots](#screenshots)
- [Acknowledgments](#acknowledgments)

## Features
- **Multiple Cipher Algorithms**: Supports encryption and decryption using 5 different cipher algorithms.
- **User-Friendly Interface**: Simple and intuitive design for easy use.
- **Responsive Design**: Works seamlessly on desktop and mobile devices.
- **Dark Mode Support**: Automatically adapts to the user's system preferences.

## Algorithms
The website supports the following cipher algorithms:

- **AES (Advanced Encryption Standard)**: A symmetric encryption algorithm.
- **Caesar Cipher**: A substitution cipher that shifts letters by a fixed number.
- **Monoalphabetic Cipher**: A substitution cipher using a custom alphabet mapping.
- **Playfair Cipher**: A digraph substitution cipher.
- **Vigenere Cipher**: A method of encrypting alphabetic text using a simple form of polyalphabetic substitution.

## Installation
To run this project locally, follow these steps:

### Clone the Repository:
```bash
git clone https://github.com/your-username/cipher-website.git
```

### Navigate to the Project Directory:
```bash
cd cipher-website
```

### Open the Project:
Open the `index.html` file in your browser.

Alternatively, use a local server (e.g., Python's HTTP server or http-server).

#### Using Python:
```bash
python -m http.server 8000
```
Then, open [http://localhost:8000](http://localhost:8000) in your browser.

#### Using Node.js:
```bash
npx http-server
```
Then, open [http://localhost:8080](http://localhost:8080) in your browser.

## Usage
1. Open the website in your browser.
2. Select a cipher algorithm from the homepage.
3. Enter the text you want to encrypt or decrypt.
4. Provide the required key or shift value (depending on the algorithm).
5. Click **Encrypt** or **Decrypt** to see the result.

## File Structure
The project is organized as follows:
```plaintext
/cipher-website
│
├── index.html          # Main landing page
├── styles.css          # Global styles
├── ase.html            # AES Cipher page
├── ase.js              # AES Cipher logic
├── caser.html          # Caesar Cipher page
├── caser.js            # Caesar Cipher logic
├── mono.html           # Monoalphabetic Cipher page
├── mono.js             # Monoalphabetic Cipher logic
├── playfair.html       # Playfair Cipher page
├── playfair.js         # Playfair Cipher logic
├── vigenere.html       # Vigenere Cipher page
├── vigenere.js         # Vigenere Cipher logic
└── README.md           # Project documentation
```

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Screenshots
<!-- Add screenshots of your project here -->
- Homepage
- AES Cipher
- Caesar Cipher

## Acknowledgments
- Inspired by classic cryptography techniques.
- Built with HTML, CSS, and JavaScript.

Enjoy encrypting and decrypting! 🔐
