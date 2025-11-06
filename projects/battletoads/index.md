<link rel="stylesheet" href="{{ '/assets/css/style.css?v=5' | relative_url }}">

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

<!-- Banner: show full image (no cropping) -->
<p style="background:#0f1215;border-radius:12px;display:block;max-width:980px;margin:0 auto;padding:8px 0;">
  <img
    src="{{ site.baseurl }}/projects/battletoads/media/poster.jpg"
    alt="Battletoads — cover"
    style="display:block;margin:0 auto;max-width:100%;height:auto;border-radius:10px;object-fit:contain;">
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

<hr>
<h2 id="applied-insight">🤝 Networking &amp; Applied Insight</h2>

<p><strong>Source:</strong> <a href="https://www.linkedin.com/in/raduposoi/" target="_blank" rel="noopener">Radu Posoi — Founder, Alkotech Labs (ex-Ubisoft QA Lead)</a></p>

<p><strong>One-line takeaway:</strong> Be deliberate — compare <em>same-dev</em> and <em>same-genre</em> titles, and write down <em>what happened</em> + <em>why it matters</em> for the player.</p>

<p><strong>How I applied it in this project</strong></p>
<ul>
  <li>Added a comparative pass: <em>Battletoads</em> vs <em>TMNT: Shredder’s Revenge</em> (same dev) and <em>Disney Illusion Island</em> (same genre).</li>
  <li>Logged <strong>presses to first control</strong>, <strong>Pause → Back</strong> behaviour, and <strong>HUD readability</strong> with “why it matters” notes.</li>
  <li>Turned notes into a <strong>comparison table + metrics</strong> (see next section).</li>
</ul>

<!-- Screenshot proof of networking (click to open full size) -->
<p>
  <a href="{{ site.baseurl }}/projects/battletoads/media/linkedin-radu-posoi-qa-mindset.png" target="_blank" rel="noopener">
    <img src="{{ site.baseurl }}/projects/battletoads/media/linkedin-radu-posoi-qa-mindset.png"
         alt="LinkedIn conversation with Radu Posoi about QA mindset"
         style="max-width:100%; height:auto; border-radius:10px; border:1px solid rgba(255,255,255,.08); box-shadow:0 6px 18px rgba(0,0,0,.35);">
  </a>
  <br><sub>Screenshot of LinkedIn exchange — demonstrating industry networking and applied learning.</sub>
</p>

<p><strong>Concrete outcome</strong></p>
<ul>
  <li><em>Battletoads</em> reaches first control in <strong>4 presses</strong> (faster than TMNT <strong>6</strong> and Illusion Island <strong>13</strong>) and resumes cleanly from Pause — a UX strength to highlight.</li>
</ul>
<hr>

<h2>🧭 Comparative Findings — First-Minute to Control, Pause → Back, HUD Readability</h2>
<p class="method-note">Method: <strong>hands-on</strong> for Battletoads/TMNT; <strong>footage review</strong> for Illusion Island.</p>

<style>
.method-note{ margin:-6px 0 10px; font-size:.95rem; color:#a9b3bd; opacity:.9; }
</style>

<h3>Summary metrics (across all three tests)</h3>

<h3>Key Metrics</h3>
<ul>
  <li><strong>Presses to first control (Title → Play):</strong> <strong>Battletoads:</strong> 4 • <strong>TMNT:</strong> 6 • <strong>Illusion Island:</strong> 13</li>
  <li><strong>Pause → Back (resume control):</strong> <strong>Battletoads:</strong> immediate • <strong>TMNT:</strong> immediate • <strong>Illusion Island:</strong> <em>not observed</em></li>
  <li><strong>HUD readability (combat):</strong> <strong>Battletoads:</strong> info spread to corners • <strong>TMNT:</strong> tiny unlabeled bars; pop-ups obscure UI</li>
</ul>

<!-- Comparison Table with thumbnails (fixed) -->
<style>
.table-compare { width:100%; border-collapse:collapse; }
.table-compare th, .table-compare td { border:1px solid rgba(255,255,255,.08); padding:10px 12px; vertical-align:middle; }
.table-compare thead th { background:rgba(0,255,240,.08); color:#00fff0; }
.table-compare td:nth-child(1){ width:140px; font-weight:700; }
.table-compare td:nth-child(2){ width:140px; white-space:nowrap; }
.table-compare td:nth-child(6){ width:190px; }
.thumb {
  width:160px; height:90px; object-fit:cover; border-radius:10px; display:block;
  border:1px solid rgba(255,255,255,.08); box-shadow:0 6px 18px rgba(0,0,0,.35);
}
.thumb.square { width:120px; height:120px; }
</style>

<table class="table-compare">
  <thead>
    <tr>
      <th>Game</th>
      <th>Timestamp</th>
      <th>Area / Feature</th>
      <th>What happened</th>
      <th>Why it matters</th>
      <th>Evidence</th>
    </tr>
  </thead>
  <tbody>
    <!-- === Battletoads === -->
    <tr>
      <td><strong>Battletoads</strong></td>
      <td>0:07–1:12 (1:05)</td>
      <td>Title → New Game</td>
      <td><strong>4 presses</strong> to first control</td>
      <td>Smooth first minute; low friction</td>
      <td>
        <a href="https://youtu.be/CN3oHz5fnFw" target="_blank" rel="noopener">
          <img class="thumb" src="https://img.youtube.com/vi/CN3oHz5fnFw/hqdefault.jpg" alt="Battletoads — New Game video">
        </a>
      </td>
    </tr>
    <tr>
      <td></td>
      <td>0:01–0:20 (0:19)</td>
      <td>Title → Continue</td>
      <td><strong>4 presses</strong>; intro dialogue skipped</td>
      <td>Faster return-to-play; risk of missed context</td>
      <td>
        <a href="https://youtu.be/iGk1TNBuZWc" target="_blank" rel="noopener">
          <img class="thumb" src="https://img.youtube.com/vi/iGk1TNBuZWc/hqdefault.jpg" alt="Battletoads — Continue video">
        </a>
      </td>
    </tr>
    <tr>
      <td></td>
      <td>0:04–0:13 (0:09)</td>
      <td>Pause → Back</td>
      <td>Immediate control; no unintended actions</td>
      <td>Prevents stray menu inputs</td>
      <td>
        <a href="https://youtu.be/P7QNSN-6wqI" target="_blank" rel="noopener">
          <img class="thumb" src="https://img.youtube.com/vi/P7QNSN-6wqI/hqdefault.jpg" alt="Battletoads — Pause to Back video">
        </a>
      </td>
    </tr>
    <tr>
      <td></td>
      <td>—</td>
      <td>HUD readability</td>
      <td>Info spread across corners; tracking health/rank/combo is hard mid-fight</td>
      <td>Accessibility/readability risk</td>
      <td>
        <a href="{{ site.baseurl }}/projects/battletoads/media/bt_observation4-hud-readability.png" target="_blank" rel="noopener">
          <img class="thumb square" src="{{ site.baseurl }}/projects/battletoads/media/bt_observation4-hud-readability.png" alt="Battletoads HUD screenshot">
        </a>
      </td>
    </tr>

    <!-- === Illusion Island === -->
    <tr>
      <td><strong>Illusion Island</strong></td>
      <td>0:09–3:11 (3:02)</td>
      <td>Title → Play</td>
      <td><strong>13 presses</strong> to first control</td>
      <td>Higher start friction than Battletoads (4) &amp; TMNT (6)</td>
      <td>
        <a href="https://youtu.be/Xq_XEP8lKZI" target="_blank" rel="noopener">
          <img class="thumb" src="https://img.youtube.com/vi/Xq_XEP8lKZI/hqdefault.jpg" alt="Illusion Island — Play video">
        </a>
      </td>
    </tr>
  <tr>
  <td></td>
  <td>—</td>
  <td>Pause → Back</td>
  <td>Not observed in available public footage (longplay/stream review)</td>
  <td>No inference without evidence</td>
  <td>—</td>
</tr>
      <td></td>
      <td>3:11</td>
      <td>Onboarding</td>
      <td>Just-in-time jump prompt</td>
      <td>Clear guidance for new players</td>
      <td>
        <a href="{{ site.baseurl }}/projects/battletoads/media/ii_observation6onboarding_prompt_00MM_playable_v01.png" target="_blank" rel="noopener">
          <img class="thumb square" src="{{ site.baseurl }}/projects/battletoads/media/ii_observation6onboarding_prompt_00MM_playable_v01.png" alt="Illusion Island onboarding screenshot">
        </a>
      </td>
    </tr>

    <!-- === TMNT === -->
    <tr>
      <td><strong>TMNT</strong></td>
      <td>0:01–3:55 (3:54)</td>
      <td>Title → Start</td>
      <td><strong>6 presses</strong> to first control</td>
      <td>Higher friction than Battletoads</td>
      <td>
        <a href="https://youtu.be/Xq_XEP8lKZI" target="_blank" rel="noopener">
          <img class="thumb" src="https://img.youtube.com/vi/Xq_XEP8lKZI/hqdefault.jpg" alt="TMNT — Start video">
        </a>
      </td>
    </tr>
    <tr>
      <td></td>
      <td>0:06–0:16 (0:10)</td>
      <td>Pause → Back</td>
      <td>Immediate control; no unintended actions</td>
      <td>Consistent resume behaviour</td>
      <td>
        <a href="https://youtu.be/MDEyQjmjfFU" target="_blank" rel="noopener">
          <img class="thumb" src="https://img.youtube.com/vi/MDEyQjmjfFU/hqdefault.jpg" alt="TMNT — Pause to Back video">
        </a>
      </td>
    </tr>
    <tr>
      <td></td>
      <td>—</td>
      <td>HUD readability</td>
      <td>Tiny blue/green unlabeled bars; score pop-ups obstruct</td>
      <td>Readability risk in combat</td>
      <td>
        <a href="{{ site.baseurl }}/projects/battletoads/media/TMNT_observation7-hud-readability.png" target="_blank" rel="noopener">
          <img class="thumb square" src="{{ site.baseurl }}/projects/battletoads/media/TMNT_observation7-hud-readability.png" alt="TMNT HUD screenshot">
        </a>
      </td>
    </tr>
  </tbody>
</table>

<p><sub><strong>Method (Illusion Island rows):</strong> Not hands-on — I reviewed public longplay/stream footage. Where behaviour wasn’t visible, it’s recorded as <em>Not observed in available footage</em> rather than guessed.</sub></p>

<blockquote><strong>Takeaway:</strong> Battletoads reaches first control fastest (<strong>4 presses</strong>) and resumes cleanly from Pause. Biggest risk is <strong>HUD readability</strong> during combat. Next test: verify onboarding prompt timing and confirm Pause → Back on Illusion Island with hands-on capture.</blockquote>

<details>
<summary class="details-btn">Show raw notes (from QA workbook)</summary>

  <div class="notes-wrap">
    <h4>Context</h4>
    <ul>
      <li><strong>Environment:</strong> Win11 · 1080p@144Hz · Xbox-layout controller (Dhaose 360)</li>
      <li><strong>Tools:</strong> Xbox Game Bar · Snipping Tool · YouTube</li>
      <li><strong>Builds:</strong> Battletoads (PC Game Pass) v1.1F.42718 · TMNT (PC Game Pass) v1.2407.17.0 · Illusion Island (Switch video reference)</li>
      <li><strong>Lenses:</strong> First-minute · Co-op join/leave · Pause→Back · HUD · Retry · Onboarding</li>
      <li><strong>Evidence:</strong> Timestamps + up to 2 screenshots per title</li>
    </ul>

    <h4>Comparative highlights</h4>
    <ul>
      <li><strong>Similarity (same-dev):</strong> Both resume cleanly after Pause (immediate control; no unintended actions).</li>
      <li><strong>Difference (same-dev):</strong> Start friction — TMNT needs <strong>6 presses</strong> vs Battletoads <strong>4</strong>; TMNT HUD uses small, unlabeled bars; Battletoads spreads info to corners.</li>
      <li><strong>Takeaway (same-dev):</strong> Battletoads is faster to first control; both have readability risks in different ways.</li>
      <li><strong>Difference (same-genre):</strong> Illusion Island shows higher start friction; onboarding prompts are timely.</li>
      <li><strong>Takeaway (same-genre):</strong> Illusion Island emphasises guided onboarding; Battletoads faster to first control.</li>
    </ul>
  </div>
</details>

<!-- Scoped styles for the notes block -->
<style>
.notes .details-btn{display:inline-block;padding:12px 18px;border-radius:12px;background:#0d1117;border:1px solid #2b2f36;color:#14b8a6;font-weight:700;letter-spacing:.2px;box-shadow:0 2px 10px rgba(0,0,0,.25);cursor:pointer;transition:background .15s,color .15s}
.notes .details-btn:hover{background:#14b8a6;color:#0b0f14}
.notes summary{list-style:none}
.notes summary::-webkit-details-marker{display:none}
.notes .details-btn::before{content:"▶ "}
.notes[open] .details-btn::before{content:"▼ "}

.notes-wrap{margin:12px 0 2px; padding:12px 14px; background:#0f1215; border:1px solid rgba(255,255,255,.08); border-radius:10px}
.notes-wrap h4{margin:4px 0 8px; color:#cfd6dd; opacity:.95}
.notes-wrap ul{margin:0 0 10px 0; padding-left:1.1rem}
.notes-wrap li{margin:6px 0; line-height:1.55}
.notes-wrap strong{color:#cfd6dd}
</style>

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
<hr>

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
<p><em>This is a personal, non-commercial portfolio for educational and recruitment purposes. I’m not affiliated with or endorsed by any game studios or publishers. All trademarks, logos, and game assets are the property of their respective owners. Any screenshots or short clips are included solely to document testing outcomes. If anything here needs to be removed or credited differently, please contact me and I’ll update it promptly.</em></p>


