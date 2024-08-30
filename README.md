# StaffAsUsers

[![Archived](https://img.shields.io/badge/status-archived-lightgrey.svg)](https://github.com/RhamzThev/StaffAsUsers)

## Overview

**StaffAsUsers** is a utility designed to assist administrators in identifying staff members who also have student accounts within a specific system. The application processes a list of emails and outputs a list of staff members who are also students, making it easier to manage and update user account types.

## Features

- **Automated Email Processing:** Input a list of emails to automatically identify staff members with student accounts.
- **Clipboard Integration:** Quickly copy the identified users to the clipboard for easy pasting into other applications.
- **Admin Page Integration:** The results can be directly used in the Admin Page of CG to update user account types.

## Getting Started

### Prerequisites

- A Windows machine to run the executable.
- Access to the `staff_as_users_format.xlsx` file to format the list of emails.

### Installation

1. **Access the Application:**
   - Navigate to the folder `%ATC_IS_StudentStaff%\1_Rhamsez\staff_as_users` on your system.

2. **Prepare the Spreadsheet:**
   - Open the `staff_as_users_format.xlsx` file.
   - Fill in the necessary information, ensuring the spreadsheet is formatted correctly. Note that only the emails need to be copied onto the spreadsheet.

3. **Run the Application:**
   - Navigate to the `dist` folder within the `staff_as_users` directory.
   - Run the `staff_as_users.exe` file.

### Usage

1. Open the application by running the `staff_as_users.exe` file.
2. Click on "Open File" and select the spreadsheet you have prepared.
3. Once the program finishes processing, click the "Copy To Clipboard" button to retrieve the list of staff members with student accounts.
4. Log in to the Admin Page of CG, go to Users, and click "Paste List" to paste the list of emails.
5. Change the account type to "Student" for the identified users.

## Archiving Notice

This repository is about to be archived and will no longer be maintained. If you need to continue using this tool, ensure you have a local copy of all necessary files.

## License

This project is licensed under the MIT License.

## Acknowledgments

Special thanks to the contributors and maintainers of this project.

