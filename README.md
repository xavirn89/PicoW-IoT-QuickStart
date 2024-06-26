# PicoW-IoT-QuickStart Template

A MicroPython-based IoT template tailored for the Raspberry Pi Pico W. This project streamlines the initial setup, offering a web interface for WiFi configuration, secure credential management, and a solid foundation for building IoT applications.

## Features

- **Web-based WiFi Configuration**: Easily configure your device's WiFi connection through a user-friendly web interface.
- **Secure Credential Storage**: Utilizes encryption to ensure WiFi credentials are securely stored on the device.
- **Modular Design**: Crafted for flexibility, allowing for easy adaptation and extension for a variety of IoT projects.
- **Detailed Instructions**: Accompanied by a comprehensive user guide to facilitate a smooth setup process.

## Getting Started

### Prerequisites

Ensure you have the following before starting:

- Raspberry Pi Pico W
- Micro USB cable
- A computer with Python 3.x installed

### Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/xavirn89/PicoW-IoT-QuickStart.git
   ```
2. Navigate to the project directory:
   ```bash
   cd PicoW-IoT-QuickStart
   ```

## Running the Project

1. Connect the Pi Pico W to your computer using the Micro USB cable.
2. Execute `main.py` to initialize the device.

## Configuring WiFi

1. Once active, connect another device to the WiFi network created by the Pi Pico W.
2. A prompt will automatically guide you through the configuration process on smartphones, while on laptops or tablets, any attempt to navigate to a URL will redirect you to the configuration page.
3. Submit your WiFi network's SSID and password through the web interface.
4. The device will save the credentials, attempt to connect, and reboot upon successful connection.

## Verifying the Connection

The Pi Pico W will try to reconnect using the new credentials upon reboot. Success is indicated by the onboard LED blinking and the periodic display of the device's IP address in the console, signifying readiness for IoT development.

## Contributing

We invite contributions to make this template even better. Fork the repository, commit your improvements, and submit a pull request.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more information.

## Acknowledgments

- Kudos to the Raspberry Pi Foundation for the versatile Pi Pico W.

## Contact

Explore the project further at [https://github.com/xavirn89/PicoW-IoT-QuickStart](https://github.com/xavirn89/PicoW-IoT-QuickStart).
#