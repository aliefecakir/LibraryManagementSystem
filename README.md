# LibraryManagementSystem

This is a Library Management System written in C++.

## User Roles

  When you run the program, it asks whether you want to log in as an *admin* or a *student*.

  ### Admin Login
  Admins must log in using a username and password. The correct credentials are:

  - *Username:* admin  
  - *Password:* 1234  

  If the credentials are incorrect, the system displays an error and prompts the user to try again.

  ### Student Access
  Students do not need a username or password to log in. They are granted immediate access.

## Features

  ### Admin Capabilities
  Admins can perform the following operations:

  - Add new books  
  - Delete existing books  
  - Issue (lend) books to users  
  - Return books  
  - List all available books

  ### Student Capabilities
  Students can:

  - View a list of available books

## Notes

  Student actions are intentionally limited. This is designed to reflect the workflow in real-world libraries. Typically, students can only browse the collection, and if they wish to borrow a book, they must go to the        checkout desk, where the librarian (admin) handles the transaction. This system simulates that process.
