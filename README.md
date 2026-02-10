# Add Students to Private YouTube Videos

## Overview
This project is an automation solution built using UiPath to manage adding students to private YouTube videos.  
The main purpose of the project is to demonstrate clean architecture, modular automation design, and correct usage of the REFramework in a real-world scenario, without exposing any confidential or business-related details.

The automation focuses on handling student data, storing it safely, and navigating YouTube and YouTube Studio in a controlled and scalable workflow.

---

## Project Objectives
- Apply UiPath REFramework in a practical automation project.
- Design the solution using independent and reusable modules.
- Separate responsibilities between data handling and UI automation.
- Simulate a production-style RPA project structure.

---

## Key Features
- Collects student name and email as user input.
- Stores student data in an Excel file for tracking and reference.
- Automatically opens and controls Google Chrome.
- Switches to the required YouTube account and channel.
- Navigates to YouTube Studio to manage private videos.
- Designed to add students to private videos.

---

## Workflow Explanation
### 1. Initialization Phase
- Uses REFramework to load configuration values and initialize required resources.
- Ensures stability and readiness before processing starts.

### 2. Student Data Handling
- Prompts the user for student name and email.
- Saves the collected data into an Excel file to maintain a record of enrolled students.

### 3. YouTube Navigation
- Opens Chrome and navigates to YouTube.
- Switches to the correct YouTube account.
- Opens YouTube Studio for access management.

### 4. Private Video Access
- The logic is designed to add students to private videos sequentially.

---

## Technologies & Concepts Used
- UiPath Studio
- Robotic Enterprise Framework
- Modular workflow design
- Excel integration
- Browser automation
- Exception handling and logging
- Configuration-driven execution

---

## Current Status
- Core framework and architecture completed.
- Excel data storage implemented and working.
- YouTube navigation and channel switching completed.
- Student-to-video assignment logic still in progress.

---

## Notes
- No sensitive, personal, or business data is included in this repository.
- The project focuses on automation logic, structure, and best practices.
- Intended for learning, demonstration, and portfolio purposes.

---

## Future Improvements
- Complete and stabilize the student-to-video assignment logic.
- Improve UI reliability and retry mechanisms.
- Enhance logging and reporting.
- Add additional input validation and error handling.