# Leaving Cert Technology (Higher Level) revision site

A single-page revision site for students: past papers and marking schemes, exam breakdown,
topic frequency, project and portfolio guidance, and practice quizzes.

## Publish with GitHub Pages
1. Create a repository and upload everything in this folder (the three `.html` files, `papers/`, `q/`).
2. Settings > Pages > Build and deployment > Deploy from a branch > `main` / `(root)` > Save.
3. After a minute the site is at `https://<your-username>.github.io/<repository-name>/`.

## Contents
- `index.html` is the home page where students choose Junior Cycle or Senior Cycle.
- `junior.html` is Junior Cycle Applied Technology (course, learning outcomes checklist, assessment, key terms, quiz).
- `junior-projects.html`, `junior-tinkercad.html` and `junior-onshape.html` are Junior Cycle guides (project checklists and learning log, Tinkercad circuits and Arduino, Onshape CAD).
- `senior-learn.html` is the Senior Cycle learning page (year plan, core and option notes, formulas, exam skills).
- `senior.html` is Leaving Cert Technology Higher Level (past papers, breakdown, topics, project, practice).
- No build step is needed.
- `papers/` holds the past papers, marking schemes and the 2027 coursework brief.
- `q/` holds the question images used by the practice modes.

Exam papers and marking schemes are copyright of the State Examinations Commission
(examinations.ie).

## Adding mock papers and solutions
1. Put the PDF files in the `mocks/` folder.
2. Open `mocks.js` and add one line per mock paper (there are example lines to copy).
3. Leave `solutions:""` until you want to release the solutions; students will see "Coming soon".
