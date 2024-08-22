# Task 1 : Caesar Cipher Encryption/Decryption Tool

This Python script provides a simple Caesar Cipher tool to encrypt and decrypt messages by shifting the alphabet by a specified number of positions. The tool supports both upper and lower case letters and leaves non-alphabetic characters unchanged.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Encrypt and Decrypt Messages:** The tool can encrypt a message by shifting the letters forward and decrypt it by reversing the shift.
- **Custom Shift Value:** You can specify the number of positions by which to shift the alphabet (e.g., a shift of 3 turns 'A' into 'D').
- **Case Sensitivity:** The tool maintains the case of the original message (uppercase and lowercase letters are handled separately).
- **Handles Non-Alphabetic Characters:** Any characters that are not part of the alphabet (e.g., punctuation, spaces) are left unchanged.

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/caesar-cipher-tool.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd caesar-cipher-tool
   ```

## Usage
To run the Caesar Cipher tool, simply execute the script:

```bash
python caesar_cipher.py
```

You will be prompted to enter a message and a shift value. The tool will then display the encrypted message followed by the decrypted message.

## Example
Here's an example of how the script works:

```bash
HI! Caesar Cipher Encr/Decr tool is here
What's Your Message Sirr Tell me: Hello, World!
Enter the shift value: 3
Encrypted Message: Khoor, Zruog!
Decrypted Message: Hello, World!
```

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Submit a pull request with a clear description of your changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

# Task 3 : Password Complexity Checker

This Python script helps assess the strength of a password by checking the following criteria:
- Length of the password (between 8 and 20 characters)
- Inclusion of at least one uppercase letter
- Inclusion of at least one lowercase letter
- Inclusion of at least one number
- Inclusion of at least one special character

The script provides feedback on each of these criteria and gives an overall assessment of the password's strength.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)

## Features
- Validates if the password is within the acceptable length.
- Checks for the presence of uppercase letters, lowercase letters, numbers, and special characters.
- Provides clear feedback on each aspect of the password.
- Offers an overall assessment of the password's strength.

## Installation
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/password-strength-assessor.git
   ```
2. Navigate to the project directory:
   ```bash
   cd password-strength-assessor
   ```

## Usage
To use the password strength assessor, simply run the script and enter a password when prompted:

```bash
python password_strength_assessor.py
```

You will receive feedback on the strength of your password based on the criteria outlined.

## Example
Here's an example of how the script works:

```bash
Enter a password to assess: My$ecur3P@ssw0rd

Length of password: 15
Password length is nice.
Password contains uppercase letters.
Password contains lowercase letters.
Password contains numbers.
Password contains special characters.
Password is strong.
```

## Contributing
If you'd like to contribute to this project, please fork the repository and submit a pull request. We welcome improvements and new features!

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

# Task 4: Simple Keylogger

This Python script utilizes the `pynput` library to create a simple keylogger that logs all keystrokes to a file named `keylog.txt`. The keylogger runs until the `ESC` key is pressed.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Disclaimer](#disclaimer)
- [Contributing](#contributing)
- [License](#license)

## Features
- Logs every key pressed, including both character keys and special keys.
- Stores key logs in a text file (`keylog.txt`).
- Runs until the `ESC` key is pressed to stop the logger.

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/keylogger-script.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd keylogger-script
   ```
3. **Install the necessary Python package:**
   ```bash
   pip install pynput
   ```

## Usage
To start the keylogger, simply run the script:

```bash
python keylogger.py
```

The script will begin logging all keystrokes to the `keylog.txt` file. The logging will continue until the `ESC` key is pressed, at which point the script will stop.

## Disclaimer
**Important:** This keylogger is intended for educational purposes only. Unauthorized use of a keylogger to capture keystrokes without explicit consent is illegal and unethical. Always ensure you have permission to log keystrokes on any device.

## Contributing
Contributions to improve this script are welcome! To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Submit a pull request with a detailed description of the changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
 
## TASK 5 : Network Packet Analyzer

Overview

This repository contains the code for a Network Packet Analyzer developed during a recent project at Prodigy Infotech. The tool is designed to capture and analyze network packets, providing detailed insights into network traffic, including source and destination IP addresses, protocols, and payload data. The primary focus of this project is to ensure the ethical use of network analysis for educational and security purposes.

##Features

- Packet Capture: Intercept and capture live network packets.
- Protocol Analysis: Identify and categorize network protocols.
- Data Inspection: Inspect the payload of captured packets for detailed analysis.
- User-Friendly Interface: Command-line interface for easy interaction and operation.
- Ethical Use: Emphasis on ethical hacking practices and responsible use of network analysis tools.

## Installation

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- `pip` (Python package installer)
- `scapy` or any other necessary network analysis libraries

### Steps

1. Clone the Repository

   ```bash
   git clone https://github.com/your-username/network-packet-analyzer.git
   cd network-packet-analyzer
   ```

2. Install Dependencies

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Analyzer

   ```bash
   python packet_analyzer.py
   ```

## Usage

To start analyzing network packets, simply run the script as shown above. The tool will begin capturing packets from the network interface and display the analysis in the terminal. You can customize the capture filters and analysis parameters within the code to suit your specific needs.

## Example Output

Here is an example of what the output might look like:

```
[INFO] Capturing packets...
[INFO] Packet captured: Source IP: 192.168.1.2, Destination IP: 192.168.1.1, Protocol: TCP
[INFO] Analyzing packet data...
[INFO] Payload: (Hexadecimal or ASCII representation of the packet data)
```

## Contributing

Contributions to enhance the tool are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-new-feature`
3. Commit your changes: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature-new-feature`
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments

- Thanks to Prodigy Infotech for the opportunity to work on this project.
- Gratitude to the open-source community for providing the tools and libraries that made this project possible.
 
