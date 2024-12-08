# Employee-Work-Report

# Employee Work Report System

## Overview
This project is a web-based application for T Skill Foundation to facilitate employees in submitting their work reports and allow admins to view, edit, or delete the reports efficiently. The application includes responsive design and uses HTML, CSS, and JavaScript with local storage for data persistence.

## Features
- **Employee Report Submission:**
  - Form to submit Name, Mobile Number, TC Name, and Work Description.
  - Automatically captures and displays the date and time of submission.
  - Form validations to ensure correct data entry.

- **Admin View Reports:**
  - Displays all submitted reports in a tabular format.
  - Includes "Edit" and "Delete" buttons for each report.
  - Data is preserved across page refreshes using local storage.

- **Responsive Design:**
  - Optimized for mobile and desktop views.
  - Dynamic layout adjustments based on screen size.

- **Footer:**
  - Displays copyright information and creator's name.

## Technologies Used
- **Frontend:** HTML, CSS
- **Functionality:** JavaScript
- **Storage:** Local Storage for data persistence

## File Structure
- `index.html` : Main file containing the structure of the application.
- Inline CSS : Styles for the application to ensure responsiveness and an interactive design.
- Inline JavaScript : Handles form submissions, data storage, and dynamic UI updates.

## How to Use
1. Open the application in a browser.
2. The homepage displays the company name "T Skill Foundation" with two buttons:
   - **Report:** Opens a form for employees to submit their work reports.
   - **View Reports:** Displays all reports submitted, with options to edit or delete them.
3. Fill out the form under the "Report" section and submit.
4. View all reports in the "View Reports" section, where admins can edit or delete reports.

## Local Storage Details
- Data is stored in the browser's local storage to ensure persistence.
- On page load, reports are fetched from local storage and displayed automatically.
- Deleting or editing a report updates the local storage in real-time.

## Footer
- Footer text: `&copy; T Skill Foundation, Website created by Mr. Prakash Sharma`.
- Stays fixed at the bottom of the page.

## Future Enhancements
- Integration with a backend database for centralized data management.
- Adding authentication for admin access.
- Export reports to PDF or Excel format.

---
Thank you for using the Employee Work Report System. For queries or feedback, contact **Mr. Prakash Sharma** at T Skill Foundation.

