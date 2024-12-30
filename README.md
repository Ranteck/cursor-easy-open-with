# Cursor Easy Open With

A simple Windows Registry script that adds an "Open with Cursor" context menu option for folders in Windows Explorer.

## Features

- Adds "Open with Cursor" option to the context menu when right-clicking on folders
- Uses the installed Cursor editor executable
- Easy to install and uninstall

## Installation

1. Make sure you have [Cursor](https://cursor.sh/) installed on your system
2. Download the `cursor-registry.reg` file
3. Double click the file to add it to your Windows Registry
4. Accept the Windows Registry Editor prompt

## Requirements

- Windows Operating System
- Cursor Editor installed in the default location (`C:\Users\%USERNAME%\AppData\Local\Programs\cursor\Cursor.exe`)

## How it Works

The registry script adds two main keys:
- Creates an "Open with Cursor" option in the context menu for directories
- Associates the command to open Cursor with the selected folder

## Uninstallation

To remove the "Open with Cursor" context menu option:
1. Open Registry Editor (regedit)
2. Navigate to `HKEY_CLASSES_ROOT\Directory\shell\OpenWithCursor`
3. Delete the `OpenWithCursor` key

## License

MIT License

## Author

[Ranteck](https://github.com/Ranteck) 