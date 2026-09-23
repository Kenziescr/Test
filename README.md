<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Turtify — Documentation</title>
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:system-ui,sans-serif}
body{display:flex;background:#0f0f0f;color:#eee;min-height:100vh}
aside{width:260px;background:#0a0a0a;border-right:1px solid #1e1e1e;padding:24px;position:sticky;top:0;height:100vh}
aside b{font-size:18px;letter-spacing:-1px}
aside .muted{color:#555;font-size:12px;margin:8px 0 20px;display:block}
aside a{display:block;color:#888;text-decoration:none;padding:8px 10px;border-radius:8px;font-size:14px}
aside a.active,aside a:hover{background:#181818;color:#fff}
main{flex:1;padding:40px 6%;max-width:800px}
h1{font-size:48px;letter-spacing:-2px;margin-bottom:10px}
h2{margin:40px 0 12px;font-size:22px}
p,li{color:#999;line-height:1.7}
code{background:#1c1c1c;border:1px solid #2a2a2a;padding:2px 6px;border-radius:6px;font-size:13px;color:#fff}
pre{background:#121212;border:1px solid #222;padding:16px;border-radius:12px;overflow:auto;margin:14px 0}
.tag{border:1px solid #222;padding:3px 8px;border-radius:20px;font-size:11px;color:#666}
</style>
</head>
<body>
<aside>
  <b>TURTIFY</b>
  <span class="muted">v0.1.0 docs</span>
  <a class="active">Introduction</a>
  <a>Quickstart</a>
  <a>Installation</a>
  <a>API Reference</a>
  <a>Examples</a>
  <a style="margin-top:20px;color:#444">— Guides —</a>
  <a>Auth</a>
  <a>Deploy</a>
</aside>
<main>
  <span class="tag">DOCUMENTATION</span>
  <h1>Turtify</h1>
  <p>Lightweight toolkit to make your turtle scripts run 10x faster. Or whatever your project is — you edit this part.</p>

  <h2>Quickstart</h2>
  <pre><code>npm install turtify
import { turtify } from 'turtify'

turtify.init({
  apiKey: 'YOUR_KEY'
})</code></pre>

  <h2>Why Turtify?</h2>
  <ul>
    <li>⚡ Fast — no bloat</li>
    <li>🔧 Simple API</li>
    <li>📦 Works on GitHub Pages</li>
  </ul>

  <h2>Installation</h2>
  <p>Put your real install steps here. This is just the layout.</p>
  <pre><code>git clone https://github.com/Kenziescr/turtify</code></pre>
</main>
</body>
</html>