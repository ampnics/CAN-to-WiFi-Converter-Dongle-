Overview
This repository contains the PCB design files for a CAN to WiFi converter based on the ESP32. The design allows seamless communication between a Controller Area Network (CAN) bus and WiFi, making it ideal for automotive and IoT applications.



Features

ESP32-based CAN to WiFi bridge

Supports CAN 2.0 communication

Onboard 12V to 5V buck converter for efficient power management

Designed using KiCad
Compact and optimized PCB layout for reliable signal integrity

Project Structure
/schematics/ – KiCad schematic files
/pcb/ – PCB layout files
/gerber/ – Fabrication-ready Gerber files
/bom/ – Bill of Materials (BOM)
/firmware/ – (Optional) ESP32 firmware for CAN-WiFi bridging
Getting Started

Clone the repository:
bash
Copy
Edit
git clone https://github.com/ampnics/CAN-to-WiFi-Converter-Dongle-/
Open the KiCad project files in KiCad v6 or later.
Modify or generate Gerber files for PCB fabrication.
(Optional) Flash the ESP32 firmware for testing.

Requirements

KiCad 6+ for schematic and PCB design
ESP32 Development Environment (if using firmware)
CAN Transceiver Module (e.g., SN65HVD230)

License

This project is licensed under the MIT License – feel free to modify and distribute!

Contributing
Pull requests and improvements are welcome! If you find any issues, feel free to open an issue in the repository.

Author
Developed by Md Ammar Maniyar (@ampnics). Reach out for collaboration or feedback!
