# WindowsTempCleaner

A batch script for cleaning temporary files and folders in Windows to help optimize system performance and free up disk space.

## Overview

This script deletes temporary files from various directories in Windows, including the system temp folder, the Windows prefetch directory, and other common temporary file locations.

## Features

- Cleans up the following directories:
  - `C:\Windows\Temp`
  - `%temp%`
  - `C:\Windows\Prefetch`
  - `C:\Windows\History`
  - `C:\Windows\Cookies`
  - `C:\Windows\Recent`
  - `C:\Windows\Spool\Printers`

## How to Use

1. Download or clone this repository.
2. Open Command Prompt as Administrator.
3. Navigate to the directory where the script is located.
4. Run the script by typing `clean_temp.bat` and hitting Enter.

**Note:** This script deletes files permanently. Ensure that you understand its function before executing.

## Caution

Use this script with care. It will permanently delete files from the specified directories. Make sure to back up any important data before running the script.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

