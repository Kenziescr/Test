# Test

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kenzie — Build Faster</title>
<style>
  *{margin:0;padding:0;box-sizing:border-box;font-family:system-ui,sans-serif}
  body{background:#0a0a0a;color:#fff;line-height:1.6}
  nav{display:flex;justify-content:space-between;padding:20px 6%;align-items:center}
  nav b{font-size:20px;letter-spacing:-1px}
  nav a{color:#999;text-decoration:none;margin-left:20px;font-size:14px}
  .hero{padding:80px 6% 40px;max-width:900px}
  .hero h1{font-size:64px;line-height:0.95;letter-spacing:-3px;margin-bottom:20px}
  .hero h1 span{color:#555}
  .hero p{color:#888;font-size:18px;max-width:500px;margin-bottom:30px}
  .btn{background:#fff;color:#000;padding:14px 28px;border-radius:100px;text-decoration:none;font-weight:600;display:inline-block}
  .btn2{border:1px solid #222;padding:14px 28px;border-radius:100px;text-decoration:none;color:#fff;margin-left:10px}
  .grid{display:grid;grid-template-columns:1fr 1fr 1fr;gap:1px;background:#1a1a1a;margin:40px 6%;border:1px solid #1a1a1a;border-radius:16px;overflow:hidden}
  .card{background:#111;padding:30px}
  .card h3{margin-bottom:10px}
  .card p{color:#666;font-size:14px}
  @media(max-width:700px){.hero h1{font-size:42px}.grid{grid-template-columns:1fr}}
</style>
</head>
<body>
<nav>
  <b>KENZIE.</b>
  <div><a href="#">Work</a><a href="#">GitHub</a><a href="#">Contact</a></div>
</nav>
<div class="hero">
  <h1>We build <br><span>websites that</span><br> don't suck.</h1>
  <p>I'm Kenzie — developer from Indonesia. I build fast, clean websites with HTML, Python & more. This is hosted 100% on GitHub.</p>
  <a href="#" class="btn">View Projects</a>
  <a href="#" class="btn2">GitHub Profile</a>
</div>
<div class="grid">
  <div class="card"><h3>⚡ Fast</h3><p>No WordPress bloat. Just pure code, loads in <0.5s.</p></div>
  <div class="card"><h3>📱 Responsive</h3><p>Looks perfect on your phone, tablet, and that weird plane panel.</p></div>
  <div class="card"><h3>🔓 Open</h3><p>All code is open source on my GitHub.</p></div>
</div>
</body>
</html>