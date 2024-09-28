


# Task Nine: HTML and Python Script Editing

## Overview

In this task, I installed VSCodium on Kali Linux, edited an HTML file, and updated a Python script as part of my coursework. This README outlines the steps I followed, including installation, editing, and submission.

## Prerequisites

- Kali Linux
- Basic understanding of HTML and Python
- Internet connection for downloading VSCodium

## Steps

### 1. Install VSCodium on Kali Linux

To install VSCodium, I followed these steps:

1. Open the terminal.
2. Add the VSCodium repository:
   ```bash
   echo "deb [arch=amd64] https://git.io/vscodium-deb stable main" | sudo tee /etc/apt/sources.list.d/vscodium.list
   ```
3. Add the GPG key:
   ```bash
   wget -qO - https://git.io/vscodium-gpgkey | sudo apt-key add -
   ```
4. Update the package list:
   ```bash
   sudo apt update
   ```
5. Install VSCodium:
   ```bash
   sudo apt install codium
   ```

For more details, refer to the [VSCodium Installation Guide](https://vscodium.com/#install).

### 2. Open and Edit HTML File

1. Launched VSCodium and opened the HTML file from Task Three.
2. Noticed syntax highlighting features.
3. Used Emmet to improve the HTML structure. For example, typing `!` and pressing Tab generated a boilerplate.
4. Edited the HTML file to ensure it was valid and well-structured.

### 3. Open and Edit Python Script

1. Opened the Python script from Task Three in VSCodium.
2. Added a shebang line at the top:
   ```python
   #!/usr/bin/env python3
   ```
   This allows the script to be executed directly without needing to call Python explicitly.

3. Made necessary changes to the script to improve functionality.
4. Saved the changes.

### 4. Execute the Python Script

1. Made the script executable:
   ```bash
   chmod +x your_script.py
   ```
2. Executed the script directly:
   ```bash
   ./your_script.py
   ```
   This executed the script without using the `python` command
