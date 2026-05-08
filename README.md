#  Library Management System

A terminal-based multi-library management system in Python, built for Google Colab with Google Drive storage.

## Features
- 3 libraries with independent book inventories
- Shared user registry — borrow from any library with one account
- Staff & user login with hashed passwords and hidden input
- Forgot password via security questions
- 7-day borrow limit, 5 EGP/day fine, max 3 books across all libraries
- Full cross-library borrow/return history logs

## How to Run
1. Open in **Google Colab** and mount Google Drive
2. Run the cell — default admin is created automatically
   - Username: `admin` | Password: `admin123`
3. Change the admin password after first login

## Tech
Python 3 · Google Colab · `hashlib` · `getpass` · `json`
