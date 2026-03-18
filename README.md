# Girls Act Register Starter

This is a simple starter project for an AHF Girls Act participant register.

## What it does
- Collects participant register data in a browser form
- Saves demo entries in the browser using localStorage
- Lets you export CSV and JSON files
- Works as a single-file static site, so it is easy to deploy on GitHub Pages

## Important safety note
This starter is good for:
- prototyping
- demos
- user testing
- non-sensitive practice data

This starter is **not** the correct final setup for storing sensitive participant or health data because GitHub Pages is a static hosting service. Use GitHub Pages for the interface only, then connect the form to a secure backend with access control.

## Recommended field design
Use the minimum data needed:
- Entry date
- Participant ID
- First name / last name
- Age group
- County / area
- School or community group
- Session type
- Consent status
- Referral needed
- Attendance status
- Facilitator
- Notes

## Suggested production stack
### Easiest beginner option
- Frontend: GitHub Pages
- Data storage: Google Form or Google Sheets with Apps Script
- Good for: non-sensitive data and small internal pilots

### Better option for growth
- Frontend: GitHub Pages
- Backend: Supabase
- Auth: Supabase Auth
- Data protection: Row Level Security
- Good for: controlled team access and multi-user data entry

### Best for health/research workflows
- KoboToolbox / ODK / REDCap
- Good for: structured field collection, auditability, and stronger data governance

## Deploy to GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html` to the repository.
3. Open the repository `Settings`.
4. Open `Pages`.
5. Under `Build and deployment`, choose `Deploy from a branch`.
6. Select the branch (usually `main`) and folder `/ (root)`.
7. Save.
8. Wait a minute or two and GitHub will publish your site.

## Next improvements
- Add login
- Send form submissions to a database
- Add edit/search/filter tools
- Add role-based access for program staff
- Split consent logs from attendance data
- Replace exact phone collection with unique IDs where possible

