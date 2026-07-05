# File Integrity Monitor - PowerShell for macOS

## Project Description
This project is a simple File Integrity Monitor built with PowerShell on macOS. The script creates a baseline of file hashes and checks if files have been changed, added, or deleted.

## Why I Built This
I built this project to practice PowerShell scripting, file monitoring, and basic cybersecurity concepts. File integrity monitoring is useful because it can help detect unauthorized changes to important files.

## Tools Used
- macOS
- PowerShell
- Terminal
- SHA256 hashing
- GitHub

## What the Script Does
- Creates a baseline of files inside the `TestFiles` folder
- Uses SHA256 hashes to identify file changes
- Detects modified files
- Detects new files
- Detects deleted files

## How to Run the Project

1. Open Terminal.
2. Go to the project folder:
   ```bash
   cd ~/File-Integrity-Monitor-PowerShell
