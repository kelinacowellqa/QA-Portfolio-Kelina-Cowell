# 🎮 Battletoads — Functional Testing (PC Game Pass)

[⬅ Back to Portfolio Home](https://kelinacowellqa.github.io/QA-Portfolio-Kelina-Cowell/)

**Studio:** Dlala Studios / Rare
**Platform:** PC (Game Pass)
**Scope:** Gameplay logic • UI • Audio • Performance

---

## 🎯 Goal

Validate core gameplay flows and document reproducible defects with clear severity and repro steps.

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
* Evidence screenshots
* Evidence video (YouTube)
* Jira workflow / board screenshot
* STAR summary

---

## 📊 Metrics

| Metric            | Value |
| :---------------- | :---- |
| Total Bugs Logged |       |
| Critical          |       |
| Major             |       |
| Minor             |       |
| Repro Consistency |       |

> Replace values with your actual counts from the board/report.

---

## 🧠 STAR SUMMARY – Battletoads QA (PC Game Pass)

**Situation:** One-week functional test of Battletoads on Win11, Game Pass build 1.1F.42718, 1920×1080@144Hz, Xbox-layout controllers + keyboard.

**Task:**  Validate core gameplay logic, UI flow, input handling (keyboard/controller focus), audio cues, and basic performance.

**Action:**  Built a test plan, executed the suite daily, captured repro video with Xbox Game Bar/OBS, and logged defects in Jira with clear titles, steps, and evidence.

**Result:**  Surface-level stability is good, but testing revealed several high-impact defects blocking keyboard-only play and local co-op start; findings are prioritised and linked with clips for rapid triage.

---

## ⚙ Jira & Agile Practice

Brief note connecting this project to your current Jira course learnings (board setup, transitions, evidence attachments, etc.).

---

## 📷 Evidence & Media

| Type                               | File / Link |
|:-----------------------------------|:------------|
| **QA Workbook (Google Sheets)**    | [Open Workbook](https://docs.google.com/spreadsheets/d/17_BCpZrtCTItn-ieGcG1PExIGnlLe1Bg/edit?usp=sharing) |
| **QA Workbook (PDF Export)**       | [Battletoads_QA_Functional_TestPlan_PCGamePass_Kelina_Cowell_PORTFOLIO.pdf](./bug_reports/Battletoads_QA_Functional_TestPlan_PCGamePass_Kelina_Cowell_PORTFOLIO.pdf) |
| Jira Board Screenshots              | ### Jira Board — Overview

<a href="./jira_workflow/battletoads_jira_board_overview.png" target="_blank">
  <img src="./jira_workflow/battletoads_jira_board_overview.png"
       alt="Battletoads QA board overview — To Do, Blocked, In Progress, Verified"
       style="max-width:100%; width:900px;">
</a>

### Jira Board — Verified (thumbnails)

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
| 01 | Pause: keyboard (Esc/P) doesn’t open Pause; controller Start works | High | 5/5 | <a href="https://www.youtube.com/watch?v=YOUTUBE_ID_01&t=0s" target="_blank" rel="noopener"><img src="https://img.youtube.com/vi/YOUTUBE_ID_01/hqdefault.jpg" alt="Bug 01 video" width="140"></a> |
| 02 | Pause menu: controller→keyboard hand-off fails (keyboard ignored) | High | 5/5 | <a href="https://www.youtube.com/watch?v=YOUTUBE_ID_02&t=0s" target="_blank" rel="noopener"><img src="https://img.youtube.com/vi/YOUTUBE_ID_02/hqdefault.jpg" alt="Bug 02 video" width="140"></a> |
| 03 | Resume misroute: **Enter** on *Resume* opens *Join In* overlay | High | 3/3 | <a href="https://www.youtube.com/watch?v=YOUTUBE_ID_03&t=0s" target="_blank" rel="noopener"><img src="https://img.youtube.com/vi/YOUTUBE_ID_03/hqdefault.jpg" alt="Bug 03 video" width="140"></a> |
| 04 | Keyboard-only path blocked for local co-op start | High | 3/3 | <a href="https://www.youtube.com/watch?v=YOUTUBE_ID_04&t=0s" target="_blank" rel="noopener"><img src="https://img.youtube.com/vi/YOUTUBE_ID_04/hqdefault.jpg" alt="Bug 04 video" width="140"></a> |

<details>
  <summary><strong>Show inline videos</strong> (opens four embeds)</summary>

  <div style="position:relative;padding-top:56.25%;margin:12px 0;">
    <iframe src="https://www.youtube.com/embed/YOUTUBE_ID_01?modestbranding=1&rel=0" title="Bug 01" style="position:absolute;top:0;left:0;width:100%;height:100%;border:0;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
  </div>

  <div style="position:relative;padding-top:56.25%;margin:12px 0;">
    <iframe src="https://www.youtube.com/embed/YOUTUBE_ID_02?modestbranding=1&rel=0" title="Bug 02" style="position:absolute;top:0;left:0;width:100%;height:100%;border:0;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
  </div>

  <div style="position:relative;padding-top:56.25%;margin:12px 0;">
    <iframe src="https://www.youtube.com/embed/YOUTUBE_ID_03?modestbranding=1&rel=0" title="Bug 3" style="position:absolute;top:0;left:0;width:100%;height:100%;border:0;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
  </div>

  <div style="position:relative;padding-top:56.25%;margin:12px 0;">
    <iframe src="https://www.youtube.com/embed/YOUTUBE_ID_04?modestbranding=1&rel=0" title="Bug 4" style="position:absolute;top:0;left:0;width:100%;height:100%;border:0;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
  </div>
</details>

 |
| Workflow Screenshot                | [workflow.png](./jira_workflow/workflow.png) |
| Video Clip (YouTube)               | [Watch evidence clip](https://www.youtube.com/...) |
| Key Bug Screenshot 1               | [bug_01.png](./media/bug_01.png) |
| Key Bug Screenshot 2               | [bug_02.png](./media/bug_02.png) |

---

## 🧩 Lessons Learned

One to two concise insights on documentation clarity, reproducibility, or workflow.

---

## 🔗 Related Files

* [`bug_reports/`](./bug_reports/)
* [`jira_workflow/`](./jira_workflow/)
* [`media/`](./media/)
