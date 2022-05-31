# User Management Screen

This page is accessed with authorization only. It displays the registered users and allows to create a new user.

This page has three parts:

1. Options Bar
2. Users Table
3. New User Creation

## Options Bar

This bar includes the followings:

- New User button

  - Activates the visibility of the New User Creation Screen for the user to fill.

- Hide Disabled Users checkbox

  - This consist of a checkbox and a text which indicates the function of the checkbox.
  
  - User checks the checkbox to modify the Users Table for only displaying the active users.

- Save User button

  - Checks and saves the new user information from New User Creation inputs.

## Users Table

This table displays the users as rows.

- Columns should consist of the following:

  1. ID
  2. User Name
  3. Email
  4. Enabled (Indication for Enabled/Disabled accounts)

- Filter results by active users if the Hide Disabled Users checkbox in the Options Bar is checked.

## New User Creation

This part is placed inside the page and only visible when user presses the New User button in the Options Bar. Included elements are as follows:

1. A header that reads as "New User"
2. A label and textbox for Username input
3. A label and textbox for Display Name input
4. A label and textbox for Phone input
5. A label and textbox for Email input
6. A label and dropbox for User Roles
    - (User roles are "Guest", "Admin", "SuperAdmin", etc.)
7. A label and checkbox for Enabled/Disabled user
