# PDHCP: An Efficient Programmable BOOTP/DHCP Client/Server/Relay 🌐

![PDHCP](https://img.shields.io/badge/PDHCP-v1.0-blue.svg) ![License](https://img.shields.io/badge/License-MIT-green.svg) ![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)

Welcome to the **PDHCP** repository! This project provides a highly efficient, programmable BOOTP/DHCP client, server, and relay. It is designed for ease of use and flexibility, making it an ideal choice for developers and network administrators alike.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features ✨

- **Programmable Interface**: Easily customize the behavior of the BOOTP/DHCP client/server/relay.
- **Efficiency**: Optimized for speed and low resource usage.
- **Compatibility**: Works seamlessly with various network setups.
- **Extensive Logging**: Keep track of requests and responses for better debugging.
- **Cross-Platform**: Runs on multiple operating systems, including Linux, Windows, and macOS.

## Installation 🛠️

To get started with PDHCP, you can download the latest release from our [Releases section](https://github.com/GabrielGouveia2023944/pdhcp/releases). After downloading, follow these steps to install:

1. **Download the Release**: Navigate to the provided link and download the appropriate file for your operating system.
2. **Extract the Files**: If the downloaded file is compressed, extract it to your desired location.
3. **Run the Executable**: Open your terminal or command prompt, navigate to the extracted folder, and execute the program.

```bash
cd path/to/extracted/folder
./pdhcp
```

## Usage 📖

Once installed, you can start using PDHCP. Here’s a quick overview of how to run the client, server, or relay.

### Starting the Server

To start the DHCP server, use the following command:

```bash
./pdhcp server
```

### Starting the Client

To run the DHCP client, use:

```bash
./pdhcp client
```

### Running as a Relay

For relay functionality, execute:

```bash
./pdhcp relay
```

### Command-Line Options

You can view all available options by running:

```bash
./pdhcp --help
```

This will display a list of commands and their descriptions.

## Configuration ⚙️

PDHCP is highly configurable. You can modify the settings through a configuration file or command-line arguments.

### Configuration File

Create a file named `pdhcp.conf` in the same directory as the executable. Here’s a sample configuration:

```ini
[server]
port = 67
max_clients = 100

[client]
timeout = 10
```

### Command-Line Arguments

You can also pass configurations directly via command-line arguments:

```bash
./pdhcp server --port 67 --max_clients 100
```

## Contributing 🤝

We welcome contributions! If you’d like to help improve PDHCP, please follow these steps:

1. **Fork the Repository**: Click the fork button at the top right of the page.
2. **Clone Your Fork**: Use the command:
   ```bash
   git clone https://github.com/yourusername/pdhcp.git
   ```
3. **Create a Branch**: 
   ```bash
   git checkout -b feature-branch
   ```
4. **Make Your Changes**: Implement your feature or fix.
5. **Commit Your Changes**: 
   ```bash
   git commit -m "Add a feature"
   ```
6. **Push to Your Fork**: 
   ```bash
   git push origin feature-branch
   ```
7. **Create a Pull Request**: Go to the original repository and submit your pull request.

## License 📜

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact 📫

For any inquiries or issues, please contact the maintainer:

- **Name**: Gabriel Gouveia
- **Email**: gabriel@example.com
- **GitHub**: [GabrielGouveia2023944](https://github.com/GabrielGouveia2023944)

Feel free to visit our [Releases section](https://github.com/GabrielGouveia2023944/pdhcp/releases) for the latest updates and releases. 

Thank you for your interest in PDHCP! We hope you find it useful for your networking needs.