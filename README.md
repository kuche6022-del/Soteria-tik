# School Attendance Management Website

A responsive browser-based attendance manager for:
- Business Administration
- Computer Science
- Accountancy
- Foundation, ND1 and ND2

## Included
- Student register (add, edit, search, filter and delete)
- Class attendance marking (Present, Absent, Late, Excused)
- Attendance history, CSV export and printable class sheets
- Lecturer and administrator signature spaces on printouts
- Timetable manager
- School/session settings
- JSON backup and restore
- Responsive desktop, tablet and mobile layout

## Run locally
Open `index.html` in a modern browser. No build command or package installation is required.

## Deploy on Render
1. Upload the contents of this ZIP to a GitHub repository (make `index.html` the repository root file).
2. In Render choose **New + → Static Site** and connect the repository.
3. Build command: leave blank.
4. Publish directory: `.`
5. Deploy.

## Important data note
This version saves information in the browser's local storage on the device/browser being used. It is suitable as a working prototype or single-device register. It does not synchronise records between lecturers or devices and does not provide secure user accounts. For a school-wide live system, connect a secure database and authentication service before using it as the official central attendance register. Download JSON backups regularly.
