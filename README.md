# SI - System Information Script for Debian

`si` is a bash script inspired by neofetch, designed to quickly retrieve system information relevant to developers and admins. Unlike neofetch, `si` focuses on providing a concise overview of the system's key components, making it easier for developers to understand their working environment or diagnose issues with their setup.

## Features

`si` displays the following system information:

- **Host:** User and hostname with DNS resolution.
- **OS:** Operating System name.
- **CPU:** Processor model.
- **Kernel:** Kernel version.
- **Uptime:** System uptime.
- **CPU Usage:** Current CPU usage percentage.
- **Memory Usage:** Used and total memory (in MB).

## Requirements

`si` is intended for use on Debian-based systems. It requires bash and the standard utilities (`grep`, `awk`, `sed`, `uname`, `uptime`, `top`, `free`, `nslookup`) that are typically pre-installed on most Linux distributions.

## Installation

1. Download the `si` script to a directory of your choice.
2. Make the script executable with the command: `chmod +x si`.
3. Optionally, move the script to a directory in your PATH for easier access.

## Usage

To run the script, navigate to the directory where `si` is located and execute:

```bash
./si
```

Or, if you've placed `si` in your PATH:

```bash
si
```

## Customization

`si` is easily customizable. Users can modify the script to add or remove information based on their specific needs. The script uses standard Linux commands and utilities, making it straightforward to edit.

## Contributing

Contributions to `si` are welcome! Whether you have suggestions for new features, improvements, or have found a bug, please feel free to open an issue or submit a pull request.

## Acknowledgments

- Inspired by neofetch.
- Thanks to the Linux community for the tools and utilities utilized in this script.

