<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Mincheol Seong</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="PhD Student, Texas A&M University | Wireless Networks & Reinforcement Learning">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#ffffff; --text:#111827; --muted:#6b7280; --accent:#0ea5e9; --link:#2563eb;
      --border:#e5e7eb; --chip:#f3f4f6;
    }
    *{box-sizing:border-box}
    body{
      margin:0; background:var(--bg); color:var(--text);
      font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;
      line-height:1.6;
    }
    a{color:var(--link); text-decoration:none}
    a:hover{text-decoration:underline}
    /* Top nav */
    .topbar{
      position:sticky; top:0; z-index:10;
      background:linear-gradient(90deg,#1f7aa8,#159957); color:#fff;
      padding:12px 20px; border-bottom:1px solid rgba(255,255,255,.15);
    }
    .nav{
      max-width:1100px; margin:0 auto; display:flex; gap:20px; align-items:center;
      justify-content:space-between;
    }
    .nav h1{margin:0; font-size:22px; font-weight:700}
    .nav-links a{color:#eaf6ff; margin-left:16px; font-weight:600}
    .nav-links a:hover{color:#fff}

    /* Layout */
    .wrap{max-width:1100px; margin:28px auto; padding:0 20px; display:grid; grid-template-columns:280px 1fr; gap:28px}
    @media (max-width:900px){ .wrap{grid-template-columns:1fr} .sidebar{position:static; top:auto}}
    .sidebar{
      position:sticky; top:76px; align-self:start; border:1px solid var(--border);
      border-radius:14px; padding:20px; background:#fff;
    }
    .avatar{width:120px; height:120px; border-radius:999px; object-fit:cover; display:block; margin:0 auto 12px auto}
    .name{font-size:22px; font-weight:700; text-align:center; margin:6px 0}
    .subtitle{color:var(--muted); text-align:center; margin:0 0 12px 0; font-size:14px}
    .side-list{list-style:none; padding:0; margin:10px 0 0 0}
    .side-list li{display:flex; align-items:center; gap:10px; padding:8px 4px; border-radius:10px}
    .chip{background:var(--chip); padding:2px 8px; border-radius:999px; font-size:12px; color:var(--muted)}
    .icon{width:16px; height:16px; display:inline-block; border-radius:3px; background:var(--muted)}

    .card{
      border:1px solid var(--border); border-radius:14px; background:#fff; padding:22px; margin-bottom:18px;
    }
    .card h2{margin:0 0 12px 0; font-size:20px}
    .muted{color:var(--muted)}
    .bullets{margin:0; padding-left:20px}
    .bullets li{margin:6px 0}
    .pill{display:inline-block; background:#fff3cd; color:#a16207; padding:1px 8px; border-radius:999px; font-size:12px; border:1px solid #fde68a}
    .pub a{font-weight:600}
    .section-grid{display:grid; gap:18px}

    footer{max-width:1100px; margin:18px auto 40px; padding:0 20px; color:var(--muted); font-size:14px}
  </style>
</head>
<body>

  <!-- Top navigation -->
  <div class="topbar">
    <div class="nav">
      <h1>Mincheol Seong</h1>
      <div class="nav-links">
        <a href="#news">News</a>
        <a href="#publications">Publications</a>
        <a href="#honors">Honors</a>
        <a href="#education">Education</a>
        <a href="#talks">Talks</a>
        <a href="#internships">Internships</a>
        <a href="#contact">Contact</a>
      </div>
    </div>
  </div>

  <div class="wrap">
    <!-- Sidebar -->
    <aside class="sidebar">
      <img class="avatar" src="assets/img/profile.jpg" alt="profile">
      <div class="name">Mincheol Seong</div>
      <div class="subtitle">PhD student @ Texas A&amp;M University</div>

      <ul class="side-list">
        <li><span class="icon"></span> College Station, TX, USA</li>
        <li><span class="icon"></span> <a href="mailto:YOUR_EMAIL">Email</a></li>
        <li><span class="icon"></span> <a href="https://github.com/mincheolseong">GitHub</a></li>
        <li><span class="icon"></span> <a href="https://scholar.google.com/">Google Scholar</a></li>
        <li><span class="icon"></span> <a href="https://www.linkedin.com/">LinkedIn</a></li>
        <li><span class="chip">Wireless Networks · RL</span></li>
      </ul>
    </aside>

    <!-- Main content -->
    <main class="section-grid">
      <div class="card">
        <p>Hi! I’m Mincheol, a Ph.D. student at Texas A&amp;M University advised by <a href="#">Prof. I-Hong Hou</a>.  
        My research interests are in wireless networks and reinforcement learning, focusing on constrained RL (CMDP), zero-shot adaptation, and actor–critic methods.</p>
      </div>

      <div class="card" id="news">
        <h2>🔥 News</h2>
        <ul class="bullets">
          <li><span class="pill">Aug 2025</span> Preparing for <strong>MobiHoc 2025</strong> (Rice University, Houston).</li>
          <li><span class="pill">Jul 2025</span> Verified zero-shot updates in PPO; moving to actor–critic (RCPO).</li>
        </ul>
      </div>

      <div class="card" id="publications">
        <h2>📚 Publications</h2>
        <ul class="bullets pub">
          <li><a href="#">Understanding the Fundamental Trade-Off Between Age of Information and Throughput in Unreliable Wireless Networks</a> — accepted to MobiHoc 2025.</li>
          <!-- Add more items -->
        </ul>
      </div>

      <div class="card" id="honors">
        <h2>🏅 Honors and Awards</h2>
        <ul class="bullets">
          <li>2024 National Scholarship (Graduate)</li>
        </ul>
      </div>

      <div class="card" id="education">
        <h2>🎓 Education</h2>
        <ul class="bullets">
          <li><strong>Texas A&amp;M University</strong>, Ph.D., 2024–Present</li>
          <li><strong>[Prev Univ]</strong>, M.S., 2021–2024</li>
          <li><strong>[Prev Univ]</strong>, B.S., 2017–2021</li>
        </ul>
      </div>

      <div class="card" id="talks">
        <h2>🎤 Invited Talks</h2>
        <p class="muted">(Coming soon…)</p>
      </div>

      <div class="card" id="internships">
        <h2>💼 Internships</h2>
        <ul class="bullets">
          <li>2023.07–2024.01, [Company], [City].</li>
        </ul>
      </div>

      <div class="card" id="contact">
        <h2>📬 Contact</h2>
        <ul class="bullets">
          <li>Email: <a href="mailto:YOUR_EMAIL">YOUR_EMAIL</a></li>
          <li>GitHub: <a href="https://github.com/mincheolseong">mincheolseong</a></li>
          <li>Office: WEB 111, Texas A&amp;M University</li>
        </ul>
      </div>
    </main>
  </div>

  <footer>
    © <span id="y"></span> Mincheol Seong · Hosted on GitHub Pages
  </footer>
  <script>document.getElementById('y').textContent=new Date().getFullYear()</script>
</body>
</html>
