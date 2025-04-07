# Internet Speed Test Monitor

## Project Overview

This project is a Python-based internet speed test monitoring tool. It periodically checks your internet speed (download and upload) using the `speedtest-cli` library and logs the results to a file. The program is designed to run at regular intervals and tracks your internet performance over time. 

## Features

- Periodically runs speed tests to measure download and upload speeds.
- Logs the results to a status file for later analysis.
- Allows for easy monitoring of internet speed fluctuations and downtime.

## Current Limitations

- The program doesn't have a defined end condition, meaning it will continue running indefinitely until manually stopped. Future improvements will include a more user-friendly way to stop the program and handle exceptions.
- An alert mechanism to be implemented during network downtime to inform on network issues. 

## Requirements

To run the project, you'll need:
- Python 3.x
- `speedtest-cli` library
- Python `subprocess` module (for running system commands)

You can install the `speedtest-cli` library via pip:

```bash
pip install speedtest-cli
