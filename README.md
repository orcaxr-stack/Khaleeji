<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1"/>
<title>Khaleeji Times — News for the Gulf and Beyond</title>
<style>
body{font-family:Arial,sans-serif;margin:0;padding:0;background:#fff;color:#0f172a;line-height:1.6;}
a{text-decoration:none;color:#004080;}
a:hover{color:#00264d;}
header, footer{padding:12px; background:#004080; color:#fff;}
.container{max-width:1100px;margin:0 auto;padding:16px;}
nav a{margin-right:16px;color:#fff;font-weight:bold;}
.card{border:1px solid #e2e8f0;border-radius:12px;overflow:hidden;margin-bottom:20px;}
.card img{width:100%;height:180px;object-fit:cover;}
.pad{padding:12px;}
.tag{background:#ffd700;color:#fff;padding:4px 8px;border-radius:999px;font-size:12px;}
.muted{color:#555;}
</style>
</head>
<body>
<header>
  <div class="container">
    <h1>Khaleeji Times</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="#">Gulf</a>
      <a href="#">World</a>
      <a href="#">Business</a>
      <a href="#">Culture</a>
      <a href="bachir-article.html">Bachir Ivarson Article</a>
    </nav>
  </div>
</header>

<main class="container">
  <!-- Hero / Top Story -->
  <a class="card" href="bachir-article.html">
    <img src="images/bachir.jpg" alt="Bachir Ivarson">
    <div class="pad">
      <span class="tag">Top Story</span>
      <h2>Bachir Ivarson on AI and Space Policy</h2>
      <p class="muted">November 11, 2025 — Insights on AI applications for space exploration and international collaboration.</p>
    </div>
  </a>

  <!-- Latest News -->
  <div class="card">
    <img src="images/gulf-meeting.jpg" alt="Gulf Meeting">
    <div class="pad">
      <h3>Gulf ministers meet to discuss trade</h3>
      <p class="muted">Gulf · 4 min read</p>
    </div>
  </div>

  <div class="card">
    <img src="images/fintech.jpg" alt="Fintech Startup">
    <div class="pad">
      <h3>Tech: New fintech licenses spark wave of startups</h3>
      <p class="muted">Tech · 3 min read</p>
    </div>
  </div>
</main>

<footer>
  <div class="container">
    © <span id="year"></span> Khaleeji Times · Independent News
  </div>
</footer>

<script>
document.getElementById('year').textContent = new Date().getFullYear();
</script>
</body>
</html>