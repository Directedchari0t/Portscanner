# Port Scanner

A simple Python-based port scanner that helps identify open ports on a specified target (IP address or hostname). It supports scanning a range of ports, handling timeouts, and running multiple scans in parallel for faster results.

## Features

- Scan open ports on a specific target host (IP or hostname).
- Scan a range of ports or a list of individual ports.
- Parallel port scanning using threads to speed up the process.
- Customizable timeout for faster or more accurate scans.
- Simple command-line interface (CLI).

## Requirements

- Python 3.x
- No additional dependencies are required; this tool uses the built-in `socket` and `concurrent.futures` libraries.

## Installation

1. Clone this repository or download the `port_scanner.py` script.

    ```bash
    git clone https://github.com/the0ffs3c/port-scanner.git
    cd port-scanner
    ```

2. There are no external dependencies, so no need for `pip` installs.

## Usage

The port scanner can be run from the command line with various options to customize the scan.

### Basic Usage

To scan the default port range (1-1024) on a target host:

```bash
python port_scanner.py -t 192.168.1.1
