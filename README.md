# Disk Sanitization Utility

This PowerShell script is designed to securely erase data on a specified disk using the diskpart utility. Please read the instructions carefully before using this utility to avoid data loss.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
  - [1. Running the Script](#1-running-the-script)
  - [2. User Input](#2-user-input)
  - [3. Sanitization Process](#3-sanitization-process)
- [Caution](#caution)
- [Contributing](#contributing)

## Features

- Securely erases data on a specified disk using diskpart.
- User-friendly prompts for disk selection and configuration.

## Prerequisites

- PowerShell (Run the script with administrative privileges)
- Windows Operating System
- Understanding of the consequences of data loss

## Usage

### 1. Running the Script

- Clone or download this repository to your local machine.
- Open a PowerShell session with administrative privileges.
- Navigate to the directory where the script is located.

### 2. User Input

Run the script by entering the following command:
powershell
Copy code
.\DiskSanitization.ps1
Follow the on-screen prompts to select the disk for sanitization, set the number of passes, and confirm the process.

### 3. Sanitization Process

The script will execute the secure erasure process based on the user's input.
It will display progress updates during the process.
Once completed, the script will provide a confirmation message.

### Caution
Data Loss: Running this script will irreversibly erase all data on the specified disk. Ensure you have backed up important data before proceeding.
Confirmation: Take extra care to confirm your selections, as there is no way to recover data after the process is initiated.


### Contributing
Contributions are welcome! If you have suggestions or improvements, please open an issue or create a pull request.
