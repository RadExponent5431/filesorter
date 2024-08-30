# File Sorter Script

This script automatically sorts files in your Downloads folder into designated subfolders based on their file types. It is particularly useful for organizing downloaded files, keeping your Downloads directory clean and easy to navigate.

## Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)

## Features

- Automatically sorts files into folders based on their file extensions.
- Moves specific folders (like Minecraft) into designated directories.
- Handles creation of new folders if they do not exist.
- Runs continuously, checking for new files every 5 minutes.

## How It Works

The script:
1. Identifies the default Downloads directory of the current user.
2. Creates folders for different file types if they do not already exist.
3. Moves files into their respective folders based on their extensions as defined in `data.py`.
4. Continuously monitors the Downloads folder and sorts files every 5 minutes.

## Project Structure

```plaintext
├── data.py              # Contains file type and folder configuration
├── file_sorter.py       # Main script for sorting files (this file)
└── README.md            # Documentation for the script
```

## Installation
```plaintext
git clone https://github.com/RadExponent5431/filesorter.git
cd filesorter
```
Press windows + R and time

```cmd
shell:startup
```

In this folder make a shortcut to the filesorter.pyw and restart your device

### Now your download folder should automatically be sortet!
