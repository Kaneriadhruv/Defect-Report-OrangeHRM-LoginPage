# OrangeHRM Portal - Login Page Defect Report

## Overview
This repository contains the defect report for the login page of the OrangeHRM portal. The defects were identified during manual testing across multiple browsers. Below is a summary of the issues found and documented in the Excel file.

## Defects Identified
1. **Misaligned Login button** - The login button is not properly aligned on the login page.
2. **Incorrect password not handled** - When entering an incorrect password, the system does not display an appropriate error message.
3. **Password field not masked** - The password input field does not mask the characters entered, displaying them in plain text.
4. **No 'Forgot your password?' checkbox** - The login page is missing a checkbox or link for "Forgot your password?" functionality.
5. **Typo in error message** - There is a typo in the error message when incorrect login details are submitted ("Incorect password").
6. **Login button not responsive in Safari** - The login button is not responsive when clicked in the Safari browser.
7. **Improper tab order** - The tab order between input fields on the login page is incorrect, making navigation via keyboard difficult.
8. **Unable to login with valid credentials** - Despite entering valid credentials, users are unable to log in.
9. **Slow login response** - The login page takes more than 5 seconds to respond after submitting valid credentials, resulting in a poor user experience.

## File Contents
The defect report (`defect_report_login_page.xlsx`) includes:
- **Defect ID**: Unique identifier for each defect.
- **Summary**: Short description of the defect.
- **Steps to Reproduce**: Detailed steps that were followed to reproduce the defect.
- **Expected Result**: The expected behavior of the system.
- **Actual Result**: The actual observed behavior.
- **Severity and Priority**: Each defect is classified by its impact on the system and urgency.
- **Status**: Current status of the defect (e.g., Open, In Progress).
- **Environment**: The testing environment, including browser and OS details.

## Environment Tested
- **Browsers**: Google Chrome, Edge, Safari
- **Operating System**: Windows 10, macOS

## Conclusion
This report provides detailed insights into the defects found on the OrangeHRM portal's login page. These defects should be addressed to improve user experience and functionality.

