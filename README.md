# TDTTI THURAVOOR - General School Election

## Overview
This is a comprehensive web application designed to manage the general school election for TDTTI Thuravoor. The system facilitates staff login, voter management, polling control, ballot processing, voting records, home voting, and election result publishing with PDF export capability.

---

## Features

### 1. Authentication
- **Staff Login:** Multiple roles with different access permissions (Admin, Polling, Control, Ballot, Presiding Officer, Results).
- **Home Voting:** Allows absentee voters to securely login via registered mobile number.

### 2. Admin Panel
- Search and fetch voters by Admission Number or Name.
- Add and save candidates including their photo and symbol uploads via an image hosting API.

### 3. Voters List
- View pending and processed voters filtered by Class and Division.
- Mark attendance instantly as Present or Absent.

### 4. Control Unit
- Start and manage polling sessions for a selected Class and Division.
- Displays real-time voter status with visual LED indicators.
- Allow voters to proceed to the ballot unit.
- End polling session for each class.

### 5. Ballot Unit
- Display candidates for voting.
- Allow casting votes including NOTA option.
- Visual LED indicators for unit status.
- Separate voting process for home voters with 5-minute timer.

### 6. Voting Records
- View total votes, male votes, and female votes.
- Option to securely end the entire election globally.

### 7. Home Voting Booth
- Home voters have a 5-minute time window to cast their vote.
- Displays personalized voting interface.

### 8. Results
- Fetch and display detailed election results by Class and Division.
- Animated leaderboard with vote counts and percentages.
- Export results to PDF report.

---

## Technologies Used
- HTML5 and CSS for structure and styling.
- JavaScript for dynamic behavior and API interactions.
- External Libraries:
  - [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) for PDF export.
- Imgbb API for uploading candidate photos and symbols.

---

## Configuration

- **Script URL:** Points to Google Apps Script endpoint handling backend operations.
- **Image Upload API:** Imgbb API key for image hosting.
- **Roles & Passwords:** Defined in front-end JS for demonstration (replace in production).

---

## Usage Instructions

1. Open `index.html` in a modern browser.
2. Login as staff using one of the predefined roles or login for home voters.
3. Navigate through tabs to perform actions according to your role.
4. Use the Admin Panel to add candidates after fetching voter details.
5. Mark attendance and start control unit sessions to manage polling.
6. Cast votes in the Ballot Unit.
7. View voting records and manage election closure.
8. Access results tab to view and export final results per class and division.

---

## Notes
- This application requires a backend Google Apps Script service for data processing.
- For full functionality, ensure network access to the external APIs and script URL.
- All actions show loading indicators and modal dialogs for feedback.

---

## License
This project is for educational and organizational use within TDTTI Thuravoor and is not licensed for external commercial use.

---
