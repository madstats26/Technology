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
- `junior-project-jc.html` is the Junior Cycle project section (3rd year, SEC brief): overview, the brief, step checklist, notes and examples. It has its own button in the Junior Cycle menu; `junior-projects.html` covers the 1st and 2nd year projects.
- `junior-electronics.html`, `junior-mechanisms.html`, `junior-design.html`, `junior-materials.html`, `junior-structures.html` and `junior-logic.html` are Junior Cycle topic pages (notes, worked examples, quiz), linked from Course > Topics.
- `senior-learn.html` is the Senior Cycle learning page (year plan, core and option notes, formulas, exam skills).
- `senior.html` is Leaving Cert Technology Higher Level (past papers, breakdown, topics, project, practice).
- No build step is needed.
- `papers/` holds the past papers, marking schemes, the 2027 Leaving Cert coursework brief and the 2027 Junior Cycle Applied Technology coursework briefs.
- `q/` holds the question images used by the practice modes.
- `project/lamp/` holds example photos for the 1st year Bedside lamp project (resized, with photo metadata removed), shown on `junior-project-lamp.html`, and a sample student project as a PDF (student name blurred).
- `project/design-process.pptx` is the design process slide deck, linked from Junior Cycle project > Notes and guides and from the Design process topic page.
- `project/jc-portfolio-template.pptx` is the Junior Cycle portfolio template, linked from Junior Cycle project > Examples.
- `project/` holds the 2027 exemplar folio (sections 1 to 3) as a Word file and its Gantt chart image, shown under Project > Exemplar folio.

Exam papers and marking schemes are copyright of the State Examinations Commission
(examinations.ie).

## Adding mock papers and solutions
1. Put the PDF files in the `mocks/` folder.
2. Open `mocks.js` and add one line per mock paper (there are example lines to copy).
3. Leave `solutions:""` until you want to release the solutions; students will see "Coming soon".
