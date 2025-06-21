# Amo-Sus CLI Tool

Amo-Sus is a lightweight command-line utility to manage files and text with ease on Windows.  
It supports listing directories with different modes, reading files, and manipulating text files with simple commands.

---

## Features

- List files and folders with filtering and detailed info  
- Read file contents to console  
- Echo text to screen or files (overwrite or append)  
- Progress bars and spinner animations for a slick CLI experience  

---

## Installation

1. Download the latest [Amo-Sus installer](https://github.com/arlotalkington/Amo-Sus) and run it.  
2. Follow the prompts to install Amo-Sus.  
3. Make sure the install directory is in your PATH or navigate to it in your terminal.

---

## Usage

```bash
# List files in C:\Users\arlo with normal mode (hides system files)
amo-sus.exe ls C:\Users\arlo

# Show all files including system files
amo-sus.exe ls C:\Users\arlo --mode all

# Display detailed info about files
amo-sus.exe ls C:\Users\arlo --mode long

# Print text to the console
amo-sus.exe echo "Hello, Amo-Sus!"

# Overwrite a file with text
amo-sus.exe echo> output.txt "Overwritten text"

# Append text to a file
amo-sus.exe echo>> output.txt "Additional line"

# Read and display a file's content
amo-sus.exe read output.txt
