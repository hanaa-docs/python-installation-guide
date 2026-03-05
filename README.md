# How to Install Python on Windows and Run Your First Program

Beginner-friendly guide to installing Python on Windows and running your first program.

---

## Overview

Python is a widely used programming language known for its simplicity and readability. It is used in web development, automation, and data analysis. This guide explains how to install Python on Windows and run your first program.

---

## Installing Python

1. Go to the official website: https://www.python.org  
2. Click **Downloads**, then select **Windows**.  
3. Download the Windows installer (64-bit version).

⚠ Make sure you download the correct installer file. The file name should look like:
python-3.x.x-amd64.exe
Avoid downloading files such as "python-manager".

4. Run the installer.

On the first installation screen:

- Check **Add Python to PATH**
- (Optional but recommended) Check **Use admin privileges when installing py.exe**

5. Click **Install Now** and wait for installation to complete.

---

## Verifying Installation

Open Command Prompt and run:
```
python --version
```
Example output:
```
Python 3.13.12
```

---

## Running Your First Program

Open Python and run:
```
print("Hello, World!")
```
Output:
```
Hello, World!
```

Congratulations! You have successfully run your first Python program.

---

## Troubleshooting

### Error: "Python was not found"

If you see this error:

- Make sure you downloaded Python from the official website.
- Ensure **Add Python to PATH** was selected during installation.
- Reinstall Python if necessary.
