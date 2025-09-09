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
      <div c
