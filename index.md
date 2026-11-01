<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Imaad Petersen | Digital Portfolio</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Newsreader:opsz,wght@6..72,500;6..72,700&family=Manrope:wght@400;500;700&display=swap" rel="stylesheet">
<style>
:root{color-scheme:light;--ink:#0f1b2d;--text:#3d4a5c;--muted:#66758a;--bg:#f4f7fa;--card:#fff;--line:#dbe2ea;--accent:#0b6fa8;--tint:rgba(11,111,168,.07);--s2:#a8691a;--s2tint:rgba(168,105,26,.08)}
*{box-sizing:border-box}
html{scroll-behavior:smooth;scroll-padding-top:72px}
body{margin:0;font:16px/1.7 Manrope,system-ui,-apple-system,"Segoe UI",sans-serif;color:var(--text);background:var(--bg)}
h1,h2,h3,h4{font-family:Newsreader,Georgia,serif;color:var(--ink);line-height:1.2;margin:0}
a{color:var(--accent);font-weight:700}
a:focus-visible,summary:focus-visible{outline:3px solid var(--accent);outline-offset:2px}
.wrap{max-width:900px;margin:0 auto;padding:0 20px}
nav{position:sticky;top:0;z-index:5;background:rgba(255,255,255,.92);backdrop-filter:blur(8px);border-bottom:1px solid var(--line)}
nav .wrap{display:flex;gap:6px;overflow-x:auto;padding:10px 20px;white-space:nowrap}
nav a{padding:6px 12px;border-radius:6px;text-decoration:none;font-size:.9rem;color:var(--text);font-weight:500}
nav a:hover{background:var(--tint);color:var(--accent)}
nav a.sec{color:var(--accent);font-weight:700}
nav a.sec+a~a.sec{color:var(--s2)}
header{background:radial-gradient(800px 320px at 85% -10%,rgba(11,111,168,.14),transparent 70%),radial-gradient(500px 260px at 0% 110%,rgba(168,105,26,.1),transparent 70%),#fff;padding:72px 0 60px;border-bottom:1px solid var(--line)}
header h1{font-size:clamp(2.4rem,7vw,3.8rem);letter-spacing:-.01em}
header p{margin:.4rem 0 0}
.role{font-size:1.15rem;color:var(--accent)}
.contact{display:flex;flex-wrap:wrap;gap:6px 22px;margin:22px 0;font-size:.95rem}
.contact a{color:var(--ink)}
.btns{display:flex;flex-wrap:wrap;gap:10px}
.btn{display:inline-block;padding:10px 20px;border-radius:6px;background:var(--accent);color:#fff;text-decoration:none}
.btn.ghost{background:transparent;color:var(--ink);border:1px solid #b9c4d0}
.btn:hover{filter:brightness(1.12)}
.banner{margin:56px 0 8px;padding:28px;border-radius:10px;background:var(--tint);border:1px solid var(--line);border-left:6px solid var(--accent)}
.banner.two{background:var(--s2tint);border-left-color:var(--s2)}
.banner small{display:block;font-weight:700;color:var(--accent);margin-bottom:4px}
.banner.two small{color:var(--s2)}
.banner h2{font-size:2rem}
.banner p{margin:.5rem 0 0}
section.blk{padding:36px 0 4px}
section.blk>h3{font-size:1.5rem;padding-bottom:10px;border-bottom:1px solid var(--line);margin-bottom:18px}
.card{background:var(--card);border:1px solid var(--line);border-radius:8px;padding:22px 24px;margin:14px 0;box-shadow:0 1px 2px rgba(15,27,45,.05)}
.chips{display:grid;grid-template-columns:repeat(auto-fill,minmax(120px,1fr));gap:12px;padding:0;list-style:none;margin:0}
.chips li{display:flex;flex-direction:column;align-items:center;gap:8px;padding:16px 8px;border-radius:8px;background:var(--card);border:1px solid var(--line);font-weight:700;font-size:.9rem;color:var(--ink)}
.chips img{width:40px;height:40px}
.video{background:#0f1b2d;border:1px solid var(--line);border-radius:8px;padding:10px;max-width:560px}
.video video{width:100%;display:block;border-radius:4px}
.job+.job{margin-top:18px;padding-top:18px;border-top:1px solid var(--line)}
.job h4{font-size:1.1rem}.job em{color:var(--muted);font-size:.92rem}
ul{padding-left:1.2rem;margin:.5rem 0}
.refs{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:14px}
.refs .card{margin:0}.refs b{color:var(--ink)}
.art{margin:0 0 28px}
.art img{width:100%;height:auto;border:1px solid var(--line);border-radius:8px;background:#fff;margin:6px 0 14px;display:block}
.label{font-weight:700;color:var(--s2);font-size:.95rem;margin:0 0 4px}
.epic{border:1px solid var(--line);border-radius:8px;background:var(--card);margin:10px 0}
.epic summary{cursor:pointer;padding:12px 16px;font-weight:700;color:var(--ink)}
.epic ul{margin:0;padding:0 16px 14px 36px}
.epic li{margin:6px 0;font-style:italic}
.refl{background:var(--card);border:1px solid var(--line);border-left:5px solid var(--accent);border-radius:8px;padding:18px 22px;margin:16px 0}
.two-s .refl{border-left-color:var(--s2)}
.refl h4{font-size:1.1rem;margin-bottom:10px}
.refl dl{margin:0;display:grid;grid-template-columns:96px 1fr;gap:8px 16px}
.refl dt{font-weight:700;color:var(--accent)}
.two-s .refl dt{color:var(--s2)}
.refl dd{margin:0}
footer{margin-top:64px;padding:28px 0;border-top:1px solid var(--line);color:var(--muted);font-size:.9rem}
@media(max-width:600px){.refl dl{grid-template-columns:1fr;gap:0}.refl dd{margin-bottom:8px}.banner{padding:22px}}
@media(prefers-reduced-motion:reduce){html{scroll-behavior:auto}}

/* sleek overrides */
body{font-size:15.5px;line-height:1.75}
nav .wrap{padding:8px 20px}
nav a{font-size:.85rem;border-radius:99px;padding:5px 14px}
header{padding:88px 0 72px;border-bottom:0}
header h1{font-size:clamp(2.6rem,8vw,4.4rem);font-weight:700;letter-spacing:-.025em}
.role{font-size:1.1rem;font-weight:500}
.btn{border-radius:99px;padding:11px 24px;font-weight:700;font-size:.92rem}
.banner{background:none;border:0;border-top:3px solid var(--accent);border-radius:0;padding:22px 0 0;margin:84px 0 4px}
.banner.two{background:none;border-top-color:var(--s2)}
.banner h2{font-size:2.5rem;letter-spacing:-.02em}
.banner small{font-size:.85rem;margin-bottom:6px}
section.blk>h3{font-size:1.35rem;border:0;margin-bottom:14px;letter-spacing:-.01em}
section.blk{padding:30px 0 2px}
.card{border:0;border-radius:14px;box-shadow:0 1px 2px rgba(15,27,45,.05),0 8px 24px rgba(15,27,45,.06)}
.refl{border:0;border-radius:14px;box-shadow:inset 0 3px 0 var(--accent),0 1px 2px rgba(15,27,45,.05),0 8px 24px rgba(15,27,45,.06);padding:22px 26px}
.two-s .refl{box-shadow:inset 0 3px 0 var(--s2),0 1px 2px rgba(15,27,45,.05),0 8px 24px rgba(15,27,45,.06)}
.epic{border:0;border-radius:14px;box-shadow:0 1px 2px rgba(15,27,45,.05),0 4px 14px rgba(15,27,45,.05)}
.art img{border:0;border-radius:14px;box-shadow:0 8px 28px rgba(15,27,45,.12)}
.video{border:0;border-radius:14px;box-shadow:0 10px 30px rgba(15,27,45,.18)}
.video video{border-radius:8px}
.chips{grid-template-columns:repeat(auto-fill,minmax(104px,1fr))}
.chips li{border:0;border-radius:14px;padding:20px 8px 16px;box-shadow:0 1px 2px rgba(15,27,45,.05),0 6px 18px rgba(15,27,45,.06);font-size:.85rem;transition:transform .15s}
.chips li:hover{transform:translateY(-3px)}
.chips svg{width:44px;height:44px}
.refs .card{box-shadow:0 1px 2px rgba(15,27,45,.05),0 6px 18px rgba(15,27,45,.06)}
</style>
</head>
<body>
<nav aria-label="Portfolio sections"><div class="wrap">
<a class="sec" href="#section-1">Section 1: Profile and CV</a>
<a href="#summary">Summary</a><a href="#interview">Interview</a><a href="#experience">Experience</a><a href="#reflections">Reflections</a>
<a class="sec" href="#section-2">Section 2: Agile Artefacts</a>
<a href="#charter">Charter</a><a href="#stories">User stories</a><a href="#product-backlog">Product backlog</a><a href="#sprint-backlog">Sprint backlog</a><a href="#logbook">Logbook</a>
</div></nav>

<header><div class="wrap">
<h1>Imaad Petersen</h1>
<p class="role">ICT Applications Development student, Cape Peninsula University of Technology</p>
<div class="contact"><span>Cape Town, South Africa</span><a style="color:#fff" href="mailto:petersenimaad3@gmail.com">petersenimaad3@gmail.com</a><span>068 061 8314</span></div>
<div class="btns"><a class="btn" href="Imaad_Petersen_CV%20(2).pdf">Download CV (PDF)</a><a class="btn ghost" href="https://www.linkedin.com/in/imaad-petersen-b02ab22aa">LinkedIn profile</a></div>
</div></header>

<main class="wrap">

<div class="banner" id="section-1">
<small>Section 1</small><h2>Profile and CV</h2>
<p>My background, skills, mock interview and professional reflections from earlier assessments.</p>
</div>

<section class="blk" id="summary"><h3>Professional summary</h3>
<div class="card"><p style="margin:0">Motivated ICT (Applications Development) student seeking a WIL placement to apply programming skills in PHP, JavaScript, HTML, CSS and Java. I want to contribute to a development team while gaining practical experience. My focus is solving complex problems through clean, efficient code and structured application design.</p></div>
<h3 style="border:0;font-size:1.2rem;margin:24px 0 10px">Technical stack</h3>
<ul class="chips"><li><svg viewBox="0 0 40 40" aria-hidden="true"><path d="M8 18h20v8a8 8 0 0 1-8 8h-4a8 8 0 0 1-8-8z" fill="#e76f00"/><path d="M28 20h2a4 4 0 0 1 0 8h-2" fill="none" stroke="#e76f00" stroke-width="2.5"/><path d="M14 4c3 3-3 5 0 9M20 4c3 3-3 5 0 9" fill="none" stroke="#5382a1" stroke-width="2" stroke-linecap="round"/><rect x="6" y="36" width="24" height="2.5" rx="1.2" fill="#5382a1"/></svg>Java</li><li><svg viewBox="0 0 40 40" aria-hidden="true"><ellipse cx="20" cy="20" rx="18" ry="11" fill="#777bb4"/><text x="20" y="25" text-anchor="middle" font-size="14" font-family="Arial,Helvetica,sans-serif" font-weight="700" fill="#fff">php</text></svg>PHP</li><li><svg viewBox="0 0 40 40" aria-hidden="true"><rect x="3" y="3" width="34" height="34" rx="4" fill="#f7df1e"/><text x="34" y="33" text-anchor="end" font-size="16" font-family="Arial,Helvetica,sans-serif" font-weight="700" fill="#111">JS</text></svg>JavaScript</li><li><svg viewBox="0 0 40 40" aria-hidden="true"><rect x="3" y="3" width="34" height="34" rx="9" fill="#ff2d20"/><text x="20" y="28" text-anchor="middle" font-size="22" font-family="Arial,Helvetica,sans-serif" font-weight="700" fill="#fff">L</text></svg>Laravel</li><li><svg viewBox="0 0 40 40" aria-hidden="true"><rect x="3" y="3" width="34" height="34" rx="9" fill="#00758f"/><text x="20" y="25" text-anchor="middle" font-size="12" font-family="Arial,Helvetica,sans-serif" font-weight="700" fill="#fff">SQL</text></svg>MySQL</li><li><svg viewBox="0 0 40 40" aria-hidden="true"><path d="M5 3h30l-2.7 30L20 37 7.7 33z" fill="#e44d26"/><text x="20" y="26" text-anchor="middle" font-size="17" font-family="Arial,Helvetica,sans-serif" font-weight="700" fill="#fff">5</text></svg>HTML5</li><li><svg viewBox="0 0 40 40" aria-hidden="true"><path d="M5 3h30l-2.7 30L20 37 7.7 33z" fill="#1572b6"/><text x="20" y="26" text-anchor="middle" font-size="17" font-family="Arial,Helvetica,sans-serif" font-weight="700" fill="#fff">3</text></svg>CSS3</li><li><svg viewBox="0 0 40 40" aria-hidden="true"><rect x="8" y="8" width="24" height="24" rx="4" fill="#f05133" transform="rotate(45 20 20)"/><path d="M15 14v13M15 20h11" stroke="#fff" stroke-width="2.2" fill="none"/><circle cx="15" cy="14" r="2.8" fill="#fff"/><circle cx="15" cy="27" r="2.8" fill="#fff"/><circle cx="26" cy="20" r="2.8" fill="#fff"/></svg>Git</li></ul>
</section>

<section class="blk" id="interview"><h3>Mock interview video</h3>
<div class="video"><video controls preload="metadata"><source src="MockInterviewVideoImaadPetersen.mp4" type="video/mp4">Your browser does not support the video tag.</video></div>
</section>

<section class="blk"><h3>Education</h3>
<div class="card"><div class="job"><h4>Diploma in ICT: Applications Development, CPUT</h4><em>2023 to present</em></div>
<div class="job"><h4>Livingstone High School</h4><em>Matric certificate, 2018 to 2022</em></div></div>
</section>

<section class="blk" id="experience"><h3>Work experience</h3>
<div class="card">
<div class="job"><h4>Seasonal cricket coach, Under the Sun Cricket Coaching</h4><em>Oct 2024 to Jan 2025</em><ul><li>Planned practice sessions and developed player skills and team strategies.</li><li>Assessed individual strengths for team selection.</li></ul></div>
<div class="job"><h4>Seasonal cashier, Howler Events</h4><em>June 2020 to May 2025</em><ul><li>Processed sales, scanned items, verified armbands and handled payments.</li><li>Provided friendly service in a high-pressure environment.</li></ul></div>
<div class="job"><h4>Event staff, R&amp;S Catering</h4><ul><li>Assisted with table setup and food arrangement.</li><li>Provided courteous service to guests.</li></ul></div>
</div></section>

<section class="blk"><h3>Professional references</h3>
<div class="refs">
<div class="card"><b>Sazi</b><br>Events Manager, Howler Events<br>071 489 9861</div>
<div class="card"><b>Patrick Van Niekerk</b><br>Head Coach, Under The Sun<br>081 335 7696</div>
<div class="card"><b>Rijana Petersen</b><br>Owner, R&amp;S Catering<br>081 430 4801</div>
</div></section>

<section class="blk" id="reflections"><h3>Professional reflections (STAR method)</h3>
<div class="refl"><h4>1. Coding in Markdown</h4><dl>
<dt>Situation</dt><dd>My Digital Portfolio needed a way to present my background and technical skills using a lightweight markup language.</dd>
<dt>Task</dt><dd>Use GitHub Flavored Markdown to create a clear, organised and professional CV that shows I am work-ready.</dd>
<dt>Action</dt><dd>I used Markdown syntax to structure headings, display my technical stack and organise my experience, keeping the document easy to read and the evidence properly categorised.</dd>
<dt>Result</dt><dd>I produced a professional document that meets the rubric and understood better how developers use Markdown for documentation.</dd></dl></div>
<div class="refl"><h4>2. Mock interview experience</h4><dl>
<dt>Situation</dt><dd>For PRP370S I took part in a mock interview that simulated a professional recruitment process in the ICT industry.</dd>
<dt>Task</dt><dd>Demonstrate my communication skills and technical knowledge on camera, then reflect on how this shows growth.</dd>
<dt>Action</dt><dd>I reviewed my past projects, practised explaining my problem-solving steps, and focused on professional body language and structured technical answers during the recording.</dd>
<dt>Result</dt><dd>Watching the recording showed me where my verbal delivery can improve and linked my coding ability to the communication a development career needs.</dd></dl></div>
<div class="refl"><h4>3. Using GitHub Pages</h4><dl>
<dt>Situation</dt><dd>After designing my portfolio in Markdown, I needed to make it publicly accessible to lecturers and potential employers.</dd>
<dt>Task</dt><dd>Deploy my repository to GitHub Pages as live evidence of my digital presence and deployment skills.</dd>
<dt>Action</dt><dd>I enabled GitHub Pages in the repository settings, set the correct source, and checked that the video and links worked in the live environment.</dd>
<dt>Result</dt><dd>Publishing to my github.io domain gave me practical experience of e-portfolio creation and of taking a project from development to production.</dd></dl></div>
</section>

<div class="banner two" id="section-2">
<small>Section 2</small><h2>Agile project artefacts: Perfume Velour Essence</h2>
<p>Agile documentation from our custom fragrance platform. Team: Imaad Petersen (Product Owner), Anas Pansari, Dayyaan Francis, Zia Modarrisi and M. Jawaad Allie. Each artefact below is followed by my reflection.</p>
</div>

<div class="two-s">

<section class="blk art" id="charter"><h3>Section 2.1: Agile Team Charter</h3>
<img src="images/agile-team-charter.png.jpeg" alt="Agile Team Charter for Perfume Velour Essence" loading="lazy">
<p class="label">Evidence</p>
<p>Our team agreement: the project purpose and each member's responsibilities for the Velour Essence custom fragrance platform. Imaad Petersen led as Product Owner, working with Anas Pansari, Dayyaan Francis, Zia Modarrisi and M. Jawaad Allie.</p>
<div class="refl"><h4>Reflection: Agile Team Charter</h4><dl>
<dt>Situation</dt><dd>To start the project well, our team needed one framework for working agreements, communication channels and shared objectives.</dd>
<dt>Task</dt><dd>As Product Owner, I set out to create a formal charter that aligned everyone around the project goals and their individual responsibilities.</dd>
<dt>Action</dt><dd>I worked with the team to define core values, set expectations for sprint accountability and document our operating rules.</dd>
<dt>Result</dt><dd>The charter removed ambiguity from day one and kept the team focused throughout development.</dd></dl></div>
</section>

<section class="blk art" id="stories"><h3>Section 2.2: User Stories and Tasks</h3>
<img src="images/user-stories-tasks.png" alt="User stories and Trello tasks" loading="lazy">
<p class="label">Evidence</p>
<p>High-level requirements were broken into six epics and user stories, then into Trello tasks with actionable checklists.</p>
<details class="epic" open><summary>Epic 1: Custom Scent Builder</summary><ul>
<li>As a customer, I want to select scent notes and adjust intensity, so that I can build a fragrance that matches my taste.</li>
<li>As a customer, I want to see a live preview or summary of my custom blend, so that I know exactly what I'm ordering before I pay.</li>
<li>As a customer, I want the system to suggest complementary notes, so that I don't have to be a perfume expert to get a good blend.</li></ul></details>
<details class="epic"><summary>Epic 2: Label and Bottle Personalisation</summary><ul>
<li>As a customer, I want to design a custom label with my own text or name, so that my bottle feels personal and giftable.</li>
<li>As a customer, I want to choose a bottle size (small, medium or large), so that I can pick what fits my budget and usage.</li></ul></details>
<details class="epic"><summary>Epic 3: Checkout and Payments</summary><ul>
<li>As a customer, I want to add my custom scent to a cart and check out securely, so that I can complete my purchase with confidence.</li>
<li>As a customer, I want to see the final price update as I customise, so that there are no surprises at checkout.</li></ul></details>
<details class="epic"><summary>Epic 4: Account and Order Tracking</summary><ul>
<li>As a customer, I want to create an account and log in, so that I can save my favourite blends and reorder easily.</li>
<li>As a customer, I want to track my order status and delivery, so that I know when my perfume will arrive.</li></ul></details>
<details class="epic"><summary>Epic 5: Admin and Operations</summary><ul>
<li>As an admin, I want to manage product stock (oils, bottles, boxes), so that I can avoid running out during peak demand.</li>
<li>As an admin, I want to view and export customer survey results, so that I can adjust pricing and scent offerings based on real feedback.</li></ul></details>
<details class="epic"><summary>Epic 6: Marketing and Engagement</summary><ul>
<li>As a customer, I want to share my custom bottle design on social media, so that I can show off my creation and bring friends to the brand.</li>
<li>As a marketing team member, I want to schedule and publish launch content, so that our campaign runs on time across channels.</li></ul></details>
<div class="refl"><h4>Reflection: User Stories and Tasks</h4><dl>
<dt>Situation</dt><dd>A web application with a custom scent builder, live preview and secure checkout needed precise functional requirements.</dd>
<dt>Task</dt><dd>Translate high-level system goals into standard user stories and break them into actionable task checklists on Trello.</dd>
<dt>Action</dt><dd>I wrote requirements in user story format and mapped them to developer checklists assigned across our sprints.</dd>
<dt>Result</dt><dd>Everyone could see the technical deliverables, which bridged customer expectations and development work.</dd></dl></div>
</section>

<section class="blk art" id="product-backlog"><h3>Section 2.3: Product Backlog</h3>
<img src="images/product-backlog.png" alt="Product backlog on Trello" loading="lazy">
<p class="label">Evidence</p>
<p>Our prioritised master list of features, sprint objectives and product requirements, managed on Trello (for example, Sprint 6: Marketing and Launch).</p>
<div class="refl"><h4>Reflection: Product Backlog</h4><dl>
<dt>Situation</dt><dd>Several development tracks for Perfume Velour Essence ran at once, so we needed a central, prioritised backlog to control scope.</dd>
<dt>Task</dt><dd>Maintain a living backlog that ordered upcoming features by business value and user demand.</dd>
<dt>Action</dt><dd>I reviewed backlog items regularly, prioritised marketing and technical milestones, and updated card statuses as priorities shifted.</dd>
<dt>Result</dt><dd>An organised backlog prevented scope creep and gave the team a clear roadmap.</dd></dl></div>
</section>

<section class="blk art" id="sprint-backlog"><h3>Section 2.4: Sprint Backlog</h3>
<img src="images/sprint-backlog.png" alt="Sprint backlog Trello board" loading="lazy">
<p class="label">Evidence</p>
<p>Our active Trello board with Product Backlog, In Progress and Completed columns, tracking sprint tasks across team members.</p>
<div class="refl"><h4>Reflection: Sprint Backlog</h4><dl>
<dt>Situation</dt><dd>For continuous delivery, we needed a transparent workspace showing task allocation and progress in real time.</dd>
<dt>Task</dt><dd>Manage the sprint columns so team members were aligned on daily deliverables.</dd>
<dt>Action</dt><dd>I monitored tasks as they moved across the board, updated sprint statuses and coordinated responsibilities between members.</dd>
<dt>Result</dt><dd>A visible workflow improved transparency and helped us complete sprints on schedule.</dd></dl></div>
</section>

<section class="blk art" id="logbook"><h3>Section 2.5: Agile Logbook</h3>
<img src="images/agile-logbook.png" alt="Agile logbook table" loading="lazy">
<p class="label">Evidence</p>
<p>A logbook table recording daily stand-ups, completed tasks, planned actions and risks or impediments across the sessions of 14 to 17 July.</p>
<div class="refl"><h4>Reflection: Agile Logbook and Stand-ups</h4><dl>
<dt>Situation</dt><dd>Accountability and risk tracking were critical for getting past roadblocks in the design and planning phases.</dd>
<dt>Task</dt><dd>Document stand-up outcomes, completed work and team impediments consistently.</dd>
<dt>Action</dt><dd>I kept the daily logbook up to date, recording task updates and upcoming goals, and raised blockers about feature prioritisation.</dd>
<dt>Result</dt><dd>Regular entries kept the team aligned and left a clear historical record of our progress.</dd></dl></div>
</section>

<section class="blk" id="connect"><h3>Section 2.6: Connecting the artefacts</h3>
<div class="refl"><h4>How the five artefacts fit together</h4><dl>
<dt>Link</dt><dd>The charter set how we work. User stories turned the customer's needs into the product backlog, the sprint backlog selected what to build next, and the logbook recorded what actually happened each day.</dd>
<dt>Learning</dt><dd>Writing the reflections showed me that Agile only works when these artefacts stay current. Each one fed the next, and gaps in one (such as unclear stories) showed up later as blockers in the logbook.</dd></dl></div>
</section>

</div>
</main>

<footer><div class="wrap">Imaad Petersen. PRP370S Digital Portfolio, CPUT Faculty of Informatics and Design, October 2026.</div></footer>
</body>
</html>
