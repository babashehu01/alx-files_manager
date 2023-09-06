# Files Manager

This project is a back-end Files Manager application built using JavaScript (ES6), Node.js, Express.js, MongoDB, Redis, and Kue. It is part of the 0x04 Back-end curriculum at Holberton School, led by Guillaume, the CTO.

## Project Overview

- **Project Weight:** 1
- **Team:** Babashehu Shettima Musti
- **Project Duration:** August 31, 2023, 6:00 AM - September 7, 2023, 6:00 AM
- **Checker Release Date:** September 2, 2023, 12:00 AM
- **Manual QA Review:** Mandatory (Request upon project completion)
- **Auto Review:** Scheduled at the project deadline

## Project Description

This project encapsulates the knowledge acquired throughout the back-end trimester, covering areas such as authentication, Node.js, MongoDB, Redis, pagination, and background processing. The primary objective is to create a straightforward platform for uploading and viewing files, including the following features:

1. **User Authentication via a Token**
2. **Listing All Files**
3. **Uploading a New File**
4. **Changing Permissions of a File**
5. **Viewing a File**
6. **Generating Thumbnails for Images**

While you will receive guidance and step-by-step instructions for building the application, you have the freedom to make implementation decisions, such as organizing code into separate files and leveraging utility functions in the "utils" folder.

It's important to note that similar services exist in the real world; however, this project's purpose is to help you understand and assemble each component to create a complete product.

## Learning Objectives

Upon completing this project, you should be able to explain the following concepts without relying on external sources:

- Creating an API with Express.js
- User authentication mechanisms
- Storing and managing data in MongoDB
- Utilizing Redis for temporary data storage
- Setting up and employing a background worker for asynchronous tasks

## Requirements

- Allowed Editors: vi, vim, emacs, Visual Studio Code
- Code will be interpreted/compiled on Ubuntu 18.04 LTS using Node.js (version 12.x.x)
- Ensure all code files end with a new line
- A mandatory README.md file at the root of the project folder
- Use the .js extension for your code files
- Code will be verified against linting rules using ESLint

## Provided Files

- **package.json:** Manages project dependencies and defines useful scripts for project tasks.
- **.eslintrc.js:** Configuration for ESLint, ensuring code quality and style consistency.
- **babel.config.js:** Configuration for Babel, enabling ES6+ features in Node.js.

## Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/files-manager.git
   cd files-manager
