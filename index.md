---
title: Home
layout: default
---

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Portfolio</title>
  <link rel="stylesheet" href="/assets/style.css">
  <style>
    body { font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif; margin: 0; }
    header { padding: 2rem 1rem; text-align: center; }
    main { max-width: 880px; margin: 0 auto; padding: 1rem; }
    .grid { display: grid; gap: 1rem; grid-template-columns: repeat(auto-fit,minmax(240px,1fr)); }
    .card { border: 1px solid #e6e6e6; border-radius: 12px; padding: 1rem; }
    .card a { text-decoration: none; }
    footer { text-align: center; padding: 2rem 1rem; color: #777; }
  </style>
</head>
<body>
  <header>
    <h1>Portfolio</h1>
    <nav>
      <a href="/projects/">Projects</a>
      <a href="/experience/">Experience</a>
    </nav>
  </header>

  <main>
    <section class="grid">
      <article class="card"><h3><a href="/projects/">Projects</a></h3><p>Case studies and live links</p></article>
      <article class="card"><h3><a href="/experience/">Professional Experience</a></h3><p>Transferable skills and roles</p></article>
    </section>
  </main>

  <footer>© <span id="y"></span></footer>
  <script>document.getElementById('y').textContent = new Date().getFullYear();</script>
</body>
</html> 