# User Management Screen UI Specification Document

## Introduction

This document serves as a guide for user interface (UI) specifications for user management screens. The User Management screen provides administrators with the ability to effectively manage user accounts.

## Target Users

- System Administrators
  
## Requirements

- The system should allow authorized users to view a list of all users.
- The system should differentiate between enabled and disabled users (possibly by greying out disabled users).
- The system should allow authorized users to create a new user by specifying the user's username, display name, phone number, email address, user role, and enabled status.
- The system should require certain user roles (guest, admin or superadmin) to create new users.

## 3. Screen Layout

The user management screen is divided into two main sections:

- **User Table**: This section displays the list of existing users in the system.
- **New User Table**: This section shows details and allows editing of the selected user.
1. **New User Button**: A button that, when clicked, opens a modal dialog or redirects the user to a separate screen for creating a new user.
2.  **Hide Disabled User Checkbox**: If Checkbox is selected, disabled users are not shown in the user table. If Checkbox is not selected, disabled users are shown in the user table.
3. **Save User Button (Disabled)**: A button that, when clicked, saves the changes made to a user's information. This button should be initially disabled and only enabled when a user makes changes to the user information.
   
   ## Initial Screen Load

- The user table should display a list of all users in the system.
- The "Hide Disabled User" checkbox should be checked for all enabled users and unchecked for disabled users.
- The "Save User" button should be disabled.


## 4. User Table

### 4.1 UI Components

- **Table**: This table displays a list of users. Each row represents a single user.
- **Columns**:
  - **ID**: Displays the unique identifier for each user (non-editable).
  - **Username**: Displays the username for each user.
  - **Email**: Displays the email address for each user.
  - **Enabled**: Displays a checkbox indicating whether the user account is enabled or disabled.
 




## 5. New User Table

### 5.1 UI Components

- **Username**: Text field displaying the username for the selected user.
- **Display Name**: Text field displaying the display name for the selected user.
- **Phone**: Text field displaying the phone number for the selected user.
- **Email**: Text field displaying the email address for the selected user.
- **User Roles**: Dropdown menu allowing selection of user roles for the selected user.(Guest, Admin, SuperAdmin)
- **Enabled**: Checkbox indicating whether the user account is enabled or disabled.
- **Save User**: Button that saves any changes made to the user details.



## 6. Initial Screen Load

- Upon initial load, the user table displays a list of all users in the system.
- The user details section is empty or displays default information.



