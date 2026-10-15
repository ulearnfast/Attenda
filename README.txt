ATTENDA UPDATE v4 — HOW TO INSTALL

This update contains only two files to replace in your existing GitHub repository:
- index.html
- sw.js

Before updating:
1. Open your installed Attenda app.
2. Go to Settings > Data & privacy > Export and save a backup as a precaution.

Upload:
1. Open your existing repository: https://github.com/ulearnfast/Attend-
2. Use Add file > Upload files.
3. Extract this ZIP on your phone/computer, then upload ONLY index.html and sw.js to the repository root (the same place as manifest.json).
4. GitHub should show that these files replace existing files. Scroll down, enter a commit message, and tap Commit changes.
5. Wait 1–3 minutes for GitHub Pages to publish.
6. Open the website in Chrome, refresh it, then close and reopen the installed Attenda app. If it still looks old, fully close the app and reopen it again.

Your app data is stored locally on your device and replacing these files should not erase it. The update migrates existing subjects, recurring classes and attendance records to the new class-type structure. Exporting a backup first is still recommended.

WHAT'S NEW
- Compact calendar counts (small number badges rather than “1 class / 2 classes” labels).
- Quick P / A / C buttons for Present, Absent and Cancelled; tap the selected button again to clear the mark.
- Edit class details or delete only one date's occurrence without deleting the recurring schedule.
- Subject creation no longer asks Lecture/Posting. Each subject has class types under Settings > Subjects > Types.
- Every class type has its own editable required attendance percentage (default 75%).
- Attendance page shows class-type attendance, required percentage, possible additional absences, and classes to attend consecutively to recover the target.
- Date generation uses local calendar dates to avoid timezone date shifts.
