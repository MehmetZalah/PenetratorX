# PenetratorX - Embedded Devices Penetration Testing PCB

## Overview

PenetratorX addresses the need for tools that facilitate penetration testing of embedded devices to ensure their security. The custom-designed PCB enables comprehensive security tests and data extraction from embedded devices, allowing for the identification of vulnerabilities and the assessment of encryption methods, The PCB includes EEPROM and external flash memory interfaces to facilitate the reading of stored parameters, optical IR LEDs for executing replay attacks, a USB interface with a desktop application for reading EEPROM and external flash, and a UART interface for data bus analysis.

## PCB Images and Testing

<img width="270" alt="PenetratorX PCB Front" src="https://github.com/MehmetZalah/PenetratorX/assets/19867149/0786cf29-5fc4-4cbf-b800-5cf8c1ce9a0b">
<img width="270" alt="PenetratorX PCB Back" src="https://github.com/MehmetZalah/PenetratorX/assets/19867149/6a29ab44-ea44-41ca-8ea1-9aa7979cbf52">
<img width="270" alt="PenetratorX Testing" src="https://github.com/MehmetZalah/PenetratorX/assets/19867149/d8428dae-197b-4aaa-8150-8d398723dae8">
<img width="410" alt="PenetratorX Printed PCB Front" src="https://github.com/MehmetZalah/PenetratorX/assets/19867149/cf99096b-5947-4a20-8cf3-206c7ca8eb09">
<img width="410" alt="PenetratorX Printed PCB Back" src="https://github.com/MehmetZalah/PenetratorX/assets/19867149/2e2303e0-d66c-486b-95b5-db030c45248e">

## Author

- **Designed By**: Mohamed Salah Abdelfattah
- **Email**: MehmetZalah@gmail.com
- **Version**: PenetratorX V1.0.0
- **GitHub**: https://github.com/MehmetZalah
- **LinkedIn**: https://linkedin.com/in/mohamed-salah-abdelfatah

## Features

1. **EEPROM and External Flash Integration**:
    - **Function**: The PCB includes interfaces for EEPROM and external flash memory chips.
    - **Usage**: Unsolder the EEPROM or flash memory from the embedded device and place it into the PCB to read and analyze the data.
    - **Purpose**: To check for plaintext data and verify if the stored data is properly encrypted.

2. **Optical IR LEDs for Replay Attacks**:
    - **Function**: The PCB includes optical IR LEDs to perform replay attacks.
    - **Usage**: Send and receive data packets to and from the embedded devices using the IR LEDs.
    - **Purpose**: To test the embedded device's vulnerability to replay attacks.

3. **USB Interface with Desktop Application**:
    - **Function**: The PCB Includes a USB interface for communication between the PCB and a desktop application.
    - **Usage**: Connect the PCB to a computer via USB to read data from the EEPROM and external flash memory.
    - **Purpose**: To provide an easy-to-use interface for data extraction and analysis.

4. **UART Interface**:
    - **Function**: A UART interface is available for reading data buses.
    - **Usage**: Connect the UART interface to the embedded device's data bus to monitor and capture communication.
    - **Purpose**: To intercept and analyze data bus communication for security assessment.
  
5. **JTAG Interface**:
    - **Function**: A JTAG interface is included for debugging the firmware.
    - **Usage**: Use JTAG pins to perform debugging tasks like stepping through code.
    - **Purpose**: To facilitate in-depth debugging and analysis of the microcontroller firmware, enhancing the ability to identify and fix security vulnerabilities.

6. **Smart Card Interface**:
    - **Function**: A Smart Card interface is included to interact with ISO7816 smart cards.
    - **Usage**: Connect the Smart Card interface PINs to your smart card to read and write data, Test the card with various APDU commands, and test unauthorized access to files.
    - **Purpose**: To test the security of smart cards, ensuring that sensitive data is properly protected.

## PCB Design and Components

- **EEPROM Interface**: For placing and reading EEPROM chips.
- **External Flash Interface**: For placing and reading external flash memory chips.
- **Optical IR LEDs**: For sending and receiving infrared signals.
- **USB Interface**: For connecting to a desktop application.
- **UART Interface**: For connecting to and reading data buses.
- **JTAG Interface**: To facilitate in-depth debugging.
- **Smart Card Interface**: To test the security of ISO7816 smart cards.

## Results

PenetratorX successfully enables extracting and analyzing data from embedded devices, identifying vulnerabilities, and verifying the effectiveness of encryption methods. The PCB is a valuable tool for penetration testers and security researchers working on embedded devices.

## License

This project is licensed under A Custom Usage License. See the [LICENSE](LICENSE) file for details.

For any questions or further information, please feel free to contact me. [mehmetzalah@gmail.com](mailto:mehmetzalah@gmail.com)
