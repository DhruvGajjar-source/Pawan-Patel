# Pawan-Patel
# SecureNet Scanner

## Overview

SecureNet Scanner is a web-based network scanning application developed using Python and Flask. It enables users to scan IP addresses or hostnames for open ports, identify running services, and gather basic network information through an intuitive web interface. The application uses multithreading to perform fast scans and displays results in real time.

## Features

- Quick, Common, Full, and Custom Port Scanning Profiles
- Multithreaded Scanning for Faster Performance
- Real-Time Scan Result Updates
- Service Detection Using Banner Grabbing
- Basic Operating System Identification
- Host Reachability Checking
- User-Friendly Web Interface

## Technologies Used

- Python
- Flask
- Flask-CORS
- HTML
- CSS
- JavaScript
- Socket Programming
- ThreadPoolExecutor

## How It Works

1. Enter a target IP address or hostname.
2. Select a scan profile.
3. Start the scan.
4. The scanner checks the specified ports.
5. Open ports and detected services are displayed in real time.
6. The application attempts to identify the operating system based on discovered services.

## Installation

### Step 1: Download the Project

Download and extract the ZIP file.

### Step 2: Create a Virtual Environment

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
