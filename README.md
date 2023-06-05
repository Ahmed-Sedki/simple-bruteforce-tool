# Bruteforce Login Tool

## Description

This is a Python tool designed to automate and simplify the process of bruteforcing logins on web pages. The tool attempts to log in with a specified username and various passwords until it either finds a match or exhausts the supplied list of passwords.

## Features
- Attempts multiple passwords with a specific username
- Can take a list of passwords from a user-specified file
- Allows optional cookie data
- Notifies user when correct credentials are found
- Neat and efficient output with colored text

## Prerequisites

- Python 3.x
- `requests` library
- `termcolor` library

## How to Install

First, you need to have Python installed on your machine. You can download it from the [official site](https://www.python.org/downloads/).

After installing Python, open your terminal/command prompt and install the necessary Python libraries with the following commands:

```bash
pip install requests
pip install termcolor
```

## How to Use

1. Clone this repository or download the script to your local machine.
2. Open your terminal/command prompt and navigate to the script's directory.
3. Run the script with the command `python bruteforce.py`.
4. The script will then prompt you for the following details:
   - Page URL: The URL of the login page you want to bruteforce.
   - Username: The username for the account you want to bruteforce.
   - Password File: The path to the file that contains the list of passwords to be tried.
   - Login Failed String: A unique string that appears when a login attempt fails on the target page.
   - Cookie Value (Optional): If there is any cookie value required.

## Note

This tool is intended for educational purposes and legal use only. The user assumes all responsibility for any misuse or damage caused by this tool.

## Contribution

If you want to contribute to this project, please make a pull request. We appreciate your help!
