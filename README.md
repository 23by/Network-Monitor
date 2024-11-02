# NetworkMonitor

## Overview
**NetworkMonitor** is a Python-based application that allows users to monitor their network connections and bandwidth usage. With a sleek dark-themed interface, users can view active connections, their associated processes, and track upload and download speeds in real time. The application also features a context menu for easy copying of connection details.

## Features
- **View Active Network Connections**: Displays a list of current connections along with details such as PID, process name, local and remote addresses, and connection status.
- **Real-time Bandwidth Monitoring**: Tracks upload and download speeds and displays them in the user interface.
- **Copy Functionality**: Right-click on any connection entry to copy details such as PID, process name, local address, remote address, and status to the clipboard.
- **Dark Theme**: An aesthetically pleasing dark interface for a modern look and better visibility.

## Requirements
To run this project, ensure you have the following installed:
- Python 3.x
- Required Python packages:
  - `psutil`
  
You can install the necessary packages using pip:

```bash
pip install psutil

## Usage

- Run the application using the following command:

```bash
python main.py

## How to Use

- Click the "Update Connections" button to refresh the list of active network connections.
- Right-click on any entry in the connections list to see options to copy various details to the clipboard.
