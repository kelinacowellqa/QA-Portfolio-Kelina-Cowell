<p>
  <img src="./media/battletoads_header.jpg"
       alt="Battletoads — cover"
       style="width:100%;max-width:980px;height:240px;object-fit:cover;border-radius:12px;display:block;margin:0 auto;">
</p>

# 🎮 Battletoads — Functional Testing (PC Game Pass)

[⬅ Back to Portfolio Home](https://kelinacowellqa.github.io/QA-Portfolio-Kelina-Cowell/)

| Studio | Platform | Scope |
|:--|:--|:--|
| Dlala Studios / Rare | PC (Game Pass) | Gameplay logic • UI • Audio • Performance |

---

## 🎯 Goal
Demonstrate core QA fundamentals by validating key gameplay flows and documenting reproducible defects with clear severity and repro steps.

---

## 🧩 Focus Areas

* Gameplay logic
* UI / navigation
* Input & controller
* Audio
* Performance

---

## 🧾 Deliverables

* Test plan (Google Sheets)
* Bug report (PDF)
* Evidence videos (YouTube)
* Jira workflow / board screenshots
* STAR summary

---

## 📊 Metrics

| Metric            | Value |
| :---------------- | :---- |
| Total Bugs Logged |   4    |
| Critical          |   0    |
| Major             |    4  |
| Minor             |   0    |
| Repro Consistency |    **100%** (16/16 across 4 issues)   |

---

## 🧠 STAR SUMMARY – Battletoads QA (PC Game Pass)

**Situation:** One-week functional test of Battletoads on Win11, Game Pass build 1.1F.42718, 1920×1080@144Hz, Xbox-layout controllers + keyboard.

**Task:**  Validate core gameplay logic, UI flow, input handling (keyboard/controller focus), audio cues, and basic performance.

**Action:**  Built a test plan, executed the suite daily, captured repro video with Xbox Game Bar/OBS, and logged defects in Jira with clear titles, steps, and evidence.

**Result:**  All four issues were fully reproducible (**16/16 attempts**), with clear evidence clips for each.


---

## ⚙ Jira & Agile Practice

I applied fundamentals from two beginner Jira courses to keep this project structured and evidence-driven.

- **Intro to JIRA (Simplilearn):** Set up a clean board and project from scratch, defined issue types, and used attachments/comments for evidence (short clips + screenshots). This kept every defect self-contained and easy to triage.
- **Get Started with Jira (Coursera):** Built a Kanban workflow with clear transitions (To Do → In Progress → Blocked → Verified), added simple WIP limits, and used labels (e.g., `pc-gamepass`, `test-execution`) so the board stayed filterable during runs.

**Practice in this project**
- Created issues directly from test runs, attaching repro clips and exact steps.
- Used **Blocked** to surface input-ownership problems quickly, then moved to **Verified** with video proof after re-test.
- Maintained short, consistent titles so tickets were scannable on the board and in the README.
  
**Certificates (PDF)**
- [Intro to JIRA — certificate](../../jira_training/screenshots/intro-to-jira_simplilearn_cert.pdf)
- [Get Started with Jira — certificate](../../jira_training/screenshots/get-started-with-jira_coursera_cert.pdf)

---

## 📷 Evidence & Media

| Type                               | File / Link |
|:-----------------------------------|:------------|
| **QA Workbook (Google Sheets)**    | [Open Workbook](https://docs.google.com/spreadsheets/d/17_BCpZrtCTItn-ieGcG1PExIGnlLe1Bg/edit?usp=sharing) |
| **QA Workbook (PDF Export)**       | [Battletoads_QA_Functional_TestPlan_PCGamePass_Kelina_Cowell_PORTFOLIO.pdf](./bug_reports/Battletoads_QA_Functional_TestPlan_PCGamePass_Kelina_Cowell_PORTFOLIO.pdf) |

### Jira Board Screenshot - Overview

<a href="./jira_workflow/battletoads_jira_board_overview.png" target="_blank">
  <img src="./jira_workflow/battletoads_jira_board_overview.png"
       alt="Battletoads QA board overview — To Do, Blocked, In Progress, Verified"
       style="max-width:100%; width:900px;">
</a>

### Jira Board — Verified Screenshots (thumbnails)

<table>
  <tr>
    <td>
      <a href="./jira_workflow/battletoads_jira_board_verified.png" target="_blank">
        <img src="./jira_workflow/battletoads_jira_board_verified.png"
             alt="Verified – set 1"
             style="width:160px; height:160px; object-fit:cover; border-radius:8px;">
      </a>
    </td>
    <td>
      <a href="./jira_workflow/battletoads_jira_board_verified2.png" target="_blank">
        <img src="./jira_workflow/battletoads_jira_board_verified2.png"
             alt="Verified – set 2"
             style="width:160px; height:160px; object-fit:cover; border-radius:8px;">
      </a>
    </td>
    <td>
      <a href="./jira_workflow/battletoads_jira_board_verified3.png" target="_blank">
        <img src="./jira_workflow/battletoads_jira_board_verified3.png"
             alt="Verified – set 3"
             style="width:160px; height:160px; object-fit:cover; border-radius:8px;">
      </a>
    </td>
    <td>
      <a href="./jira_workflow/battletoads_jira_board_verified4.png" target="_blank">
        <img src="./jira_workflow/battletoads_jira_board_verified4.png"
             alt="Verified – set 4"
             style="width:160px; height:160px; object-fit:cover; border-radius:8px;">
      </a>
    </td>
  </tr>
</table>

<sub>Click any thumbnail to view the full-size image.</sub>

### Bugs — summary + videos

| ID | Title | Sev | Repro | Video |
|:--:|:------|:---:|:-----:|:------|
| 01 | Pause: keyboard (Esc/P) does not open Pause – controller Start works | High | 5/5 | <a href="https://www.youtube.com/watch?v=2CAUt8gxH3M" target="_blank" rel="noopener"><img src="https://img.youtube.com/vi/2CAUt8gxH3M/hqdefault.jpg" alt="Bug 01 video" width="140"></a> |
| 02 | Keyboard input ignored on Pause menu after using controller | High | 5/5 | <a href="https://www.youtube.com/watch?v=5DZjJc4y_yA" target="_blank" rel="noopener"><img src="https://img.youtube.com/vi/5DZjJc4y_yA/hqdefault.jpg" alt="Bug 02 video" width="140"></a> |
| 03 | Pause menu keyboard/controller hand-off | High | 3/3 | <a href="https://www.youtube.com/watch?v=EJFduFM28Is" target="_blank" rel="noopener"><img src="https://img.youtube.com/vi/EJFduFM28Is/hqdefault.jpg" alt="Bug 03 video" width="140"></a> |
| 04 | Pause/Join In: Enter opens Join In & disables controller input (only Enter/Esc work) | High | 3/3 | <a href="https://www.youtube.com/watch?v=CXFI2a6DEpM" target="_blank" rel="noopener"><img src="https://img.youtube.com/vi/CXFI2a6DEpM/hqdefault.jpg" alt="Bug 04 video" width="140"></a> |

<sub>Repro totals = sum of all successful attempts ÷ sum of attempts (e.g., 5/5 + 5/5 + 3/3 + 3/3 = 16/16 = 100%).</sub>

<style>
.details-btn{
  display:inline-block;padding:12px 18px;border-radius:12px;
  background:#0d1117;border:1px solid #2b2f36;
  color:#14b8a6;font-weight:700;letter-spacing:.2px;
  box-shadow:0 2px 10px rgba(0,0,0,.25);cursor:pointer;
  transition:background .15s ease,color .15s ease;
}
.details-btn:hover{ background:#14b8a6; color:#0b0f14; }
details summary{ list-style:none; }
details summary::-webkit-details-marker{ display:none; }
.details-btn::before{ content:"▶ "; }
details[open] .details-btn::before{ content:"▼ "; }
.embed{ position:relative; padding-top:56.25%; margin:12px 0; }
.embed > iframe{ position:absolute; inset:0; width:100%; height:100%; border:0; }
</style>

<details id="inline-videos">
  <summary><span class="details-btn">Show inline videos</span></summary>

  <p><em>If you’re viewing this on github.com, embeds may not display. 
  Use the thumbnails/links above or open this page on the published site (GitHub Pages) to watch inline.</em></p>

  <div class="embed">
    <iframe src="https://www.youtube.com/embed/2CAUt8gxH3M?modestbranding=1&rel=0"
            title="Bug 01 — Pause: keyboard does not open Pause"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe>
  </div>

  <div class="embed">
    <iframe src="https://www.youtube.com/embed/5DZjJc4y_yA?modestbranding=1&rel=0"
            title="Bug 02 — Keyboard input ignored on Pause menu after controller use"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe>
  </div>

  <div class="embed">
    <iframe src="https://www.youtube.com/embed/EJFduFM28Is?modestbranding=1&rel=0"
            title="Bug 03 — Pause menu keyboard/controller hand-off"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe>
  </div>

  <div class="embed">
    <iframe src="https://www.youtube.com/embed/CXFI2a6DEpM?modestbranding=1&rel=0"
            title="Bug 04 — Pause/Join In: Enter opens Join In & disables controller input"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe>
  </div>
</details>

---

## 🧩 Lessons Learned

- Clear steps beat clever wording — they made my re-tests painless.
- Input hand-off needed its own checks; that’s where the real bugs were.
- Short videos did the heavy lifting when explaining severity.
  
  ## 📎 Disclaimer
This is a personal, non-commercial portfolio project for learning and job-search purposes. I’m not affiliated with or endorsed by Dlala Studios, Rare, or Microsoft. All trademarks, logos, and game assets are the property of their respective owners. Any screenshots or short clips are included solely to document testing outcomes. If something here needs to be removed or credited differently, please contact me and I’ll fix it promptly.


---

