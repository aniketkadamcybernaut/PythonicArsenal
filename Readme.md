# AV Service Configuration Checker

The AV Service Configuration Checker is a Python script designed to assist system administrators and security professionals in verifying the configuration of antivirus (AV) services on Windows systems.

## Overview

Antivirus (AV) software plays a crucial role in protecting computer systems from malware and other security threats. However, misconfigurations in AV services can lead to security vulnerabilities or system instability. This script provides a simple yet effective way to ensure that AV services are configured correctly on Windows machines.

## Features

- **Active Scanning**: Implements active reconnaissance techniques to interact with the target environment and determine the status of AV services.
- **Network Reconnaissance**: Utilizes active scanning to perform port scans and vulnerability scans against target IP addresses.
- **Scanning Networks with scapy**: Implements SYN scans and DNS scans using the `scapy` library in Python.
- **User-Friendly Output**: Provides clear and concise output, indicating the status of AV services and any vulnerabilities detected.

## Usage

To use the AV Service Configuration Checker:

1. Clone or download the repository to your local machine.
2. Install Python 3.x on your Windows system.
3. Install the required dependencies using pip:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the script using Python:

    ```bash
    python PortScan.py
    ```

5. Follow the on-screen instructions to enter the IP address of the target system.

## Contribution

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
