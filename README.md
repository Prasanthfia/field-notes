
A quiet, local-first habit ledger. Add the habits you want to tend, mark them done each day, and watch a small "growth strip" build up next to each one — the longer the streak, the deeper the color.

No backend, no sign-up, no tracking. Everything is stored in your browser's localStorage.

Features
Add and remove habits
Mark a habit done for today with one click
Current streak + best streak shown per habit
A 13-week growth strip (like a contribution graph) that deepens in color the longer a streak runs
Fully responsive, keyboard-accessible, respects reduced-motion preferences
Zero dependencies — just HTML, CSS, and vanilla JS
Running it locally
No build step needed. Either:

Open index.html directly in your browser, or

Serve it locally for a cleaner experience:

python3 -m http.server 8000
# then visit http://localhost:8000
Deploying to GitHub Pages
Push this repo to GitHub.
Go to Settings → Pages.
Under "Build and deployment", set Source to Deploy from a branch, branch main, folder / (root).
Save — your tracker will be live at https://<your-username>.github.io/<repo-name>/ within a minute or two.
Project structure
field-notes/
├── index.html      # Markup and structure
├── styles.css       # Design tokens + styles
├── app.js           # State, streak logic, rendering
└── README.md
Ideas for extending it
Sync data across devices with a small backend or a service like Supabase
Weekly/monthly habit goals instead of daily-only
Export/import data as JSON
Light/dark theme toggle
