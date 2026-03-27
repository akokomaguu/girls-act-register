# Girls Act Register

A beginner-friendly browser-based participant register built with **HTML, CSS, and Vanilla JavaScript**.

The project demonstrates how to use the **Web Storage API (`localStorage`)** to collect form data, save it in the browser, display it in a table, and export it as CSV or JSON.

## Project Goal

This project was created as a capstone for the Moringa AI class to explore and learn a new software development technology through AI prompting.

The chosen technology is:
- **Web Storage API (`localStorage`)** in Vanilla JavaScript.

## Features

- Participant registration form
- Data saved locally in the browser
- Saved entries displayed in a table
- Delete individual entries
- Export entries as CSV
- Export entries as JSON
- Simple single-file setup
- Easy deployment on GitHub Pages

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Web Storage API (`localStorage`)
- GitHub Pages for hosting

## Repository Structure

```text
.
|- index.html
|- README.md
```

## How to Run the Project

### Option 1: Open directly in the browser
1. Clone or download this repository.
2. Open `index.html` in your browser.

### Option 2: Run a simple local server

```bash
git clone https://github.com/akokomaguu/girls-act-register.git
cd girls-act-register
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## How to Use

1. Fill in the participant form.
2. Click **Save Entry**.
3. View saved rows in the table below.
4. Click **Export CSV** or **Export JSON** to download the saved data.
5. Click **Delete All Local Entries** to clear browser-stored records.

## Expected Output

- Entries appear in the saved table.
- Entries remain available after page refresh.
- CSV and JSON files download successfully when records exist.

## Important Safety Note

This version stores data only in the browser using `localStorage`.

That makes it good for:
- learning,
- prototyping,
- demos,
- non-sensitive practice data.

It is **not suitable for production use with sensitive participant or health data** because it has no secure backend, authentication, or server-side protection.

## Deployment with GitHub Pages

1. Push the code to GitHub.
2. Open the repository.
3. Go to **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the root folder.
6. Save and wait for deployment.

## Challenges Faced

Some common issues during development included:
- data not appearing after refresh until `JSON.stringify()` and `JSON.parse()` were used correctly,
- empty exports when no entries were saved,
- deciding how to explain the limits of `localStorage` for real-world sensitive data.

## Future Improvements

- Add edit/update functionality
- Add search and filter tools
- Add duplicate participant ID checking
- Add stronger form validation
- Connect to a secure backend such as Supabase
- Add authentication and role-based access

## Learning Reflection

This project helped me understand:
- how browser storage works,
- how form data can be converted into JavaScript objects,
- how to render saved data dynamically in the DOM,
- how to export browser-generated data as files,
- how AI can speed up learning and documentation.

## Author

GitHub: `akokomaguu`


