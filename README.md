# File Sharing Web Application

## Overview
A secure file sharing web application that enables users to upload, manage, and organize files within personal directories. The system was deployed on AWS EC2 and designed with a focus on usability, security, and efficient file handling.

This project was developed as part of a computer science course and extended with additional features and enhancements.

---

## Features
- User authentication system with session management
- Upload, download, delete, and manage files
- Personal directory for each authenticated user
- File renaming functionality (custom-built feature)
- Automatic file versioning:
  - Prevents overwriting existing files
  - Adds incremental prefixes (e.g., `1-file.txt`, `2-file.txt`)
- Responsive UI built with Bootstrap

---

## Tech Stack
- **Backend:** PHP, Apache
- **Frontend:** HTML, CSS, Bootstrap
- **Infrastructure:** AWS EC2
- **Server Environment:** Linux

---

## System Behavior
- Each user is assigned a secure personal directory upon login
- Uploaded files are stored and managed per user
- Duplicate filenames are automatically handled via versioning logic
- Users can rename, delete, and access their files through the interface

---

## Notes
This project was originally based on a structured academic framework and significantly extended with custom features, improved usability, and additional functionality.

The application was deployed on AWS EC2 for testing and development purposes.
