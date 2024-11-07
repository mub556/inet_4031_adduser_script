# inet_4031_adduser_script
# Automated User Creation Script

## Overview
This Python script automates the creation of users and assigns them to specified groups on a Linux system. It reads user data from `create-users.input`.

## Files
- `create-users.py`: Python script for user and group creation.
- `create-users.input`: Sample file with user details.
- `README.md`: Documentation.

## Usage

1. **Prepare Input File**:
   - Add each user’s details in `create-users.input` in this format:
     ```
     username:password:last name:first name:group1,group2
     ```
   - Example:
     ```
     user04:pass04:Last04:First04:group01
     user05:pass05:Last05:First05:group02
     ```

2. **Run the Script**:
   ```bash
   sudo ./create-users.py < create-users.input
