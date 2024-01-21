# Phone Media Transfer Script
This powershell script can be used to copy image and videos from an iPhone to an external hard drive.

## Introduction

This PowerShell script is designed to automate the transfer of media files from a specific phone to a designated folder on a computer. It's particularly useful for organizing photos and videos from a phone like the Apple iPhone. The script supports filtering specific file types and handles the transfer process seamlessly.

## Requirements

- Windows Operating System
- PowerShell 5.1 or later
- The phone (e.g., Apple iPhone) must be connected to the computer and recognized by Windows

## Installation

1. Clone the repository or download the script file to your local machine.
    > git clone https://github.com/your-username/your-repo-name.git

2. Navigate to the script's directory.

    > cd your-repo-name


## Usage

1. Connect your phone to the computer.
2. Open PowerShell and navigate to the script's directory.
3. Run the script:
    > .\PhoneMediaTransfer.ps1
4. The script will automatically find the connected phone (configured as 'Apple iPhone' by default) and transfer the specified file types from the defined source folders to the target directory on your computer.

## Configuration

- Modify the $phoneName variable to match the name of your phone as recognized by Windows.
- Update the $sourceFolders array if you need to change the source directories from which files are fetched.
- Change the $targetRootFolder to the desired destination directory on your computer.
- Adjust the $filter variable to include or exclude specific file types.
