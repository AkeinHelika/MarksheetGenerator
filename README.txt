Marksheet Dashboard - Ready to run

Files:
- marksheet_app.html : single-file web app (open in browser)

How to use:
1. Download and unzip the package.
2. Open marksheet_app.html in Chrome/Firefox (double-click).
3. HOME: Enter School, Class, Teacher, Subjects (comma separated). You may upload a small logo.
4. Import students: use 'Import Excel (Names)' on Home or 'Upload Excel Names' on Marksheet. Use .xlsx with first sheet; first two columns should be Reg and Name.
5. Click Start to go to Marksheet. Use Pick Table to choose 'Full Marksheet' or a subject table.
6. Enter marks (text allowed, e.g., AB) inline. Grades are shown next to marks.
7. Export: click Export, choose options, then Download PDF (black & white stroked tables) or Download Excel (.xlsx with Marksheet and Summary).
8. Save/Load uses browser localStorage.

Notes:
- Excel import/export uses SheetJS.
- PDF uses jsPDF + autoTable.
- The app runs entirely in your browser; no server needed.

If you want, I can modify grade boundaries, change PDF header styling, or create a zipped sample with a demo Excel to import.
