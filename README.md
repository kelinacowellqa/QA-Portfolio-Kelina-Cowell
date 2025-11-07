# Kelina Cowell — Manual & Automation QA Engineer | Games & Software Testing Portfolio

**Live site:**  
▶ https://kelinacowellqa.github.io/Manual-QA-Portfolio-Kelina-Cowell/

This repo hosts a single, static portfolio page (`index.html`) with dark theme, “Metrics”-style tables, and project cards.

---

## What’s inside

- `index.html` — the entire site (HTML + inline CSS).  
- `assets/` — images and media used on the page (banner, project posters, gifs).  
- `README.md` — this file (how to edit/update).

> No build tools. No JS required. GitHub Pages serves `index.html` directly.

---

## Update the Coverage Map (table)

1. Open **`index.html`**.
2. Find the **Coverage Map** section.
3. Edit the rows inside the table (add/remove projects).
4. Commit to `main` — Pages will update automatically.

**Tip:** Keep column order as-is: *Project · QA Type · Platform · Focus · Status*.

---

## Add or edit a Project Card

1. Open **`index.html`**.
2. Duplicate an existing `.project-block` and edit the content:
   ```html
   <div class="project-block with-thumb">
     <img class="thumb" src="assets/img/REPLACE.webp" alt="Poster for REPLACE (short, descriptive alt)">
     <p><strong>Title — Platform</strong></p>
     <p><em>Scope:</em> e.g., Functional · Regression · Cross-platform input</p>
     <p><em>Focus:</em> e.g., Core flows · Input ownership · UI/menus</p>
     <p><em>Links:</em> <a href="https://github.com/kelinacowellqa/REPO">Repo</a> · <a href="#evidence">Evidence</a></p>
   </div>
 






