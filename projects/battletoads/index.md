<link rel="stylesheet" href="{{ site.baseurl }}/assets/css/style.css?v=3">

<!-- Page-scoped CSS (3-column grid) -->
<style>
  .grid-3{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin:16px 0;align-items:stretch}
  .card{background:#0f1215;border:1px solid rgba(0,255,240,.15);border-radius:12px;padding:16px 18px;box-shadow:0 4px 20px rgba(0,0,0,.25)}
  .card h3{color:#00fff0;margin:0 0 10px}
  .card p{margin:0 0 6px}
  .card ul{margin:6px 0 0;padding-left:1.1rem}
  .card li{margin:4px 0}
  @media (max-width:980px){.grid-3{grid-template-columns:1fr 1fr}}
  @media (max-width:680px){.grid-3{grid-template-columns:1fr}}
</style>

<p>
  <img src="./media/battletoads_header.jpg"
       alt="Battletoads — cover"
       style="width:100%;max-width:980px;height:240px;object-fit:cover;border-radius:12px;display:block;margin:0 auto;">
</p>

<h1>🎮 Battletoads — Functional Testing (PC Game Pass)</h1>

<p><a href="{{ site.baseurl }}/">⬅ Back to Portfolio Home</a></p>

<table>
  <thead><tr><th>Studio</th><th>Platform</th><th>Scope</th></tr></thead>
  <tbody>
    <tr><td>Dlala Studios / Rare</td><td>PC (Game Pass)</td><td>Gameplay logic • UI • Audio • Performance</td></tr>
  </tbody>
</table>

<!-- Three-up feature grid -->
<div class="grid-3">
  <section class="card">
    <h3>🎯 Goal</h3>
    <p>Demonstrate core QA fundamentals by validating key gameplay flows and documenting reproducible defects with clear severity and repro steps.</p>
  </section>

  <section class="card">
    <h3>🧭 Focus Areas</h3>
    <ul>
      <li>Gameplay logic</li>
      <li>UI / navigation</li>
      <li>Input &amp; controller</li>
      <li>Audio</li>
      <li>Performance</li>
    </ul>
  </section>

  <section class="card">
    <h3>📄 Deliverables</h3>
    <ul>
      <li>Test plan (Google Sheets)</li>
      <li>Bug report (PDF)</li>
      <li>Evidence videos (YouTube)</li>
      <li>Jira workflow / board screenshots</li>
      <li>STAR summary</li>
    </ul>
  </section>
</div>
<!-- /grid -->

<h2>📊 Metrics</h2>
<table>
  <thead><tr><th>Metric</th><th>Value</th></tr></thead>
  <tbody>
    <tr><td>Total Bugs Logged</td><td>4</td></tr>
    <tr><td>Critical</td><td>0</td></tr>
    <tr><td>Major</td><td>4</td></tr>
    <tr><td>Minor</td><td>0</td></tr>
    <tr><td>Repro Consistency</td><td><strong>100%</strong> (16/16 across 4 issues)</td></tr>
  </tbody>
</table>

<h2>🧠 STAR SUMMARY – Battletoads QA (PC Game Pass)</h2>
<p><strong>Situation:</strong> One-week functional test of Battletoads on Win11, Game Pass build 1.1F.42718, 1920×1080@144Hz, Xbox-layout controllers + keyboard.</p>
<p><strong>Task:</strong> Validate core gameplay logic, UI flow, input handling (keyboard/controller focus), audio cues, and basic performance.</p>
<p><strong>Action:</strong> Built a test plan, executed the suite daily, captured repro video with Xbox Game Bar/OBS, and logged defects in Jira with clear titles, steps, and evidence.</p>
<p><strong>Result:</strong> All four issues were fully reproducible (<strong>16/16 attempts</strong>), with clear evidence clips for each.</p>

<h2>⚙ Jira &amp; Agile Practice</h2>
<p>I applied fundamentals from two beginner Jira courses to keep this project structured and evidence-driven.</p>
<ul>
  <li><strong>Intro to JIRA (Simplilearn):</strong> Set up a clean board and project from scratch, defined issue types, and used attachments/comments for evidence (short clips + screenshots). This kept every defect self-contained and easy to triage.</li>
  <li><strong>Get Started with Jira (Coursera):</strong> Built a Kanban workflow with clear transitions (To Do → In Progress → Blocked → Verified), added simple WIP limits, and used labels (e.g., <code>pc-gamepass</code>, <code>test-execution</code>) so the board stayed filterable during runs.</li>
</ul>
<p><strong>Practice in this project</strong></p>
<ul>
  <li>Created issues directly from test runs, attaching repro clips and exact steps.</li>
  <li>Used <strong>Blocked</strong> to surface input-ownership problems quickly, then moved to <strong>Verified</strong> with video proof after re-test.</li>
  <li>Maintained short, consistent titles so tickets were scannable on the board and in the README.</li>
</ul>
<p><strong>Certificates (PDF)</strong></p>
<ul>
  <li><a href="../../jira_training/screenshots/intro-to-jira_simplilearn_cert.pdf">Intro to JIRA — certificate</a></li>
  <li><a href="../../jira_training/screenshots/get-started-with-jira_coursera_cert.pdf">Get Started with Jira — certificate</a></li>
</ul>

<h2>📷 Evidence &amp; Media</h2>
<table>
  <thead><tr><th>Type</th><th>File / Link</th></tr></thead>
  <tbody>
    <tr>
      <td><strong>QA Workbook (Google Sheets)</strong></td>
      <td><a href="https://docs.google.com/spreadsheets/d/17_BCpZrtCTItn-ieGcG1PExIGnlLe1Bg/edit?usp=sharing">Open Workbook</a></td>
    </tr>
    <tr>
      <td><strong>QA Workbook (PDF Export)</strong></td>
      <td><a href="./bug_reports/Battletoads_QA_Functional_TestPlan_PCGamePass_Kelina_Cowell_PORTFOLIO.pdf">Battletoads_QA_Functional_TestPlan_PCGamePass_Kelina_Cowell_PORTFOLIO.pdf</a></td>
    </tr>
  </tbody>
</table>

<h3>Jira Board Screenshot - Overview</h3>
<p>
  <a href="./jira_workflow/battletoads_jira_board_overview.png" target="_blank">
    <img src="./jira_workflow/battletoads_jira_board_overview.png"
         alt="Battletoads QA board overview — To Do, Blocked, In Progress, Verified"
         style="max-width:100%; width:900px;">
  </a>
</p>

<h3>Jira Board — Verified Screenshots (thumbnails)</h3>
<table>
  <tr>
    <td><a href="./jira_workflow/battletoads_jira_board_verified.png" target="_blank"><img src="./jira_workflow/battletoads_jira_board_verified.png" alt="Verified – set 1" style="width:160px;height:160px;object-fit:cover;border-radius:8px;"></a></td>
    <td><a href="./jira_workflow/battletoads_jira_board_verified2.png" target="_blank"><img src="./jira_workflow/battletoads_jira_board_verified2.png" alt="Verified – set 2" style="width:160px;height:160px;object-fit:cover;border-radius:8px;"></a></td>
    <td><a href="./jira_workflow/battletoads_jira_board_verified3.png" target="_blank"><img src="./jira_workflow/battletoads_jira_board_verified3.png" alt="Verified – set 3" style="width:160px;height:160px;object-fit:cover;border-radius:8px;"></a></td>
    <td><a href="./jira_workflow/battletoads_jira_board_verified4.png" target="_blank"><img src="./jira_workflow/battletoads_jira_board_verified4.png" alt="Verified – set 4" style="width:160px;height:160px;object-fit:cover;border-radius:8px;"></a></td>
  </tr>
</table>
<p><sub>Click any thumbnail to view the full-size image.</sub></p>

<h3>Bugs — summary + videos</h3>
<table>
  <thead><tr><th>ID</th><th>Title</th><th>Sev</th><th>Repro</th><th>Video</th></tr></thead>
  <tbody>
    <tr><td>01</td><td>Pause: keyboard (Esc/P) does not open Pause – controller Start works</td><td>High</td><td>5/5</td><td><a href="https://www.youtube.com/watch?v=2CAUt8gxH3M" target="_blank" rel="noopener"><img src="https://img.youtube.com/vi/2CAUt8gxH3M/hqdefault.jpg" alt="Bug 01 video" width="140"></a></td></tr>
    <tr><td>02</td><td>Keyboard input ignored on Pause menu after using controller</td><td>High</td><td>5/5</td><td><a href="https://www.youtube.com/watch?v=5DZjJc4y_yA" target="_blank" rel="noopener"><img src="https://img.youtube.com/vi/5DZjJc4y_yA/hqdefault.jpg" alt="Bug 02 video" width="140"></a></td></tr>
    <tr><td>03</td><td>Pause menu keyboard/controller hand-off</td><td>High</td><td>3/3</td><td><a href="https://www.youtube.com/watch?v=EJFduFM28Is" target="_blank" rel="noopener"><img src="https://img.youtube.com/vi/EJFduFM28Is/hqdefault.jpg" alt="Bug 03 video" width="140"></a></td></tr>
    <tr><td>04</td><td>Pause/Join In: Enter opens Join In &amp; disables controller input (only Enter/Esc work)</td><td>High</td><td>3/3</td><td><a href="https://www.youtube.com/watch?v=CXFI2a6DEpM" target="_blank" rel="noopener"><img src="https://img.youtube.com/vi/CXFI2a6DEpM/hqdefault.jpg" alt="Bug 04 video" width="140"></a></td></tr>
  </tbody>
</table>
<p><sub>Repro totals = sum of all successful attempts ÷ sum of attempts (e.g., 5/5 + 5/5 + 3/3 + 3/3 = 16/16 = 100%).</sub></p>

<!-- Inline video toggle -->
<style>
  .details-btn{display:inline-block;padding:12px 18px;border-radius:12px;background:#0d1117;border:1px solid #2b2f36;color:#14b8a6;font-weight:700;letter-spacing:.2px;box-shadow:0 2px 10px rgba(0,0,0,.25);cursor:pointer;transition:background .15s ease,color .15s ease}
  .details-btn:hover{background:#14b8a6;color:#0b0f14}
  details summary{list-style:none}
  details summary::-webkit-details-marker{display:none}
  .details-btn::before{content:"▶ "}
  details[open] .details-btn::before{content:"▼ "}
  .embed{position:relative;padding-top:56.25%;margin:12px 0}
  .embed>iframe{position:absolute;inset:0;width:100%;height:100%;border:0}
</style>

<details id="inline-videos">
  <summary><span class="details-btn">Show inline videos</span></summary>
  <p><em>If you’re viewing this on github.com, embeds may not display. Use the thumbnails/links above or open this page on the published site (GitHub Pages) to watch inline.</em></p>
  <div class="embed"><iframe src="https://www.youtube.com/embed/2CAUt8gxH3M?modestbranding=1&rel=0" title="Bug 01 — Pause: keyboard does not open Pause" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></div>
  <div class="embed"><iframe src="https://www.youtube.com/embed/5DZjJc4y_yA?modestbranding=1&rel=0" title="Bug 02 — Keyboard input ignored on Pause menu after controller use" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></div>
  <div class="embed"><iframe src="https://www.youtube.com/embed/EJFduFM28Is?modestbranding=1&rel=0" title="Bug 03 — Pause menu keyboard/controller hand-off" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></div>
  <div class="embed"><iframe src="https://www.youtube.com/embed/CXFI2a6DEpM?modestbranding=1&rel=0" title="Bug 04 — Pause/Join In: Enter opens Join In & disables controller input" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></div>
</details>

<h2>🧩 Lessons Learned</h2>
<ul>
  <li>Clear steps beat clever wording — they made my re-tests painless.</li>
  <li>Input hand-off needed its own checks; that’s where the real bugs were.</li>
  <li>Short videos did the heavy lifting when explaining severity.</li>
</ul>

<h2>📎 Disclaimer</h2>
<p>This is a personal, non-commercial portfolio project for learning and recruitment purposes. I’m not affiliated with or endorsed by Dlala Studios, Rare, or Microsoft. All trademarks, logos, and game assets are the property of their respective owners. Any screenshots or short clips are included solely to document testing outcomes. If something here needs to be removed or credited differently, please contact me and I’ll fix it promptly.</p>

