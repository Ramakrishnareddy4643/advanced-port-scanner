# Advanced Port Scanner

A Python-based advanced port scanner that identifies open ports on a target IP address using multi-threading for faster scanning.

## Features
- Scan a range of ports on a target IP address
- Multi-threaded scanning for efficiency
- Displays open ports found during the scan
- Easy to use via command line

## Requirements
- Python 3.x
- Standard libraries: `socket`, `threading`, `sys`

## Usage

```bash
python port_scanner.py <target_ip> <start_port> <end_port>
