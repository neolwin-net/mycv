<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lwin Ko Aung | Network Engineer</title>

  <style>
    :root {
      --bg: #0f172a;
      --card: #1e293b;
      --text: #e2e8f0;
      --accent: #38bdf8;
    }

    body.light {
      --bg: #f5f7fa;
      --card: #ffffff;
      --text: #1e293b;
    }

    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: var(--bg);
      color: var(--text);
      transition: 0.3s;
    }

    header {
      text-align: center;
      padding: 40px 20px;
    }

    button.toggle {
      position: fixed;
      top: 15px;
      right: 15px;
      padding: 8px 12px;
      border: none;
      cursor: pointer;
      border-radius: 8px;
    }

    section {
      max-width: 1000px;
      margin: 20px auto;
      background: var(--card);
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.2);
    }

    h2 {
      border-bottom: 2px solid var(--accent);
      padding-bottom: 5px;
    }

    ul { line-height: 1.8; }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
    }

    .card {
      background: rgba(255,255,255,0.05);
      padding: 15px;
      border-radius: 10px;
    }

    .bar {
      background: #334155;
      border-radius: 10px;
      overflow: hidden;
      margin: 5px 0 15px;
    }

    .bar div {
      height: 8px;
      background: var(--accent);
    }

    a { color: var(--accent); text-decoration: none; }
  </style>
</head>

<body>

<button class="toggle" onclick="toggleMode()">Toggle Mode</button>

<header>
  <h1>Lwin Ko Aung</h1>
  <p>IP/MPLS Service Provider Network Engineer</p>
  <a href="LKA_CV.pdf" download>Download CV</a>
</header>

<section>
  <h2>About Me</h2>
  <p>
    Specialized in ISP backbone, MPLS, BGP, and large-scale network infrastructure.
    Focused on building scalable, fault-tolerant service provider networks.
  </p>
</section>

<section>
  <h2>Skills</h2>
  <div>
    BGP
    <div class="bar"><div style="width:90%"></div></div>
    MPLS
    <div class="bar"><div style="width:85%"></div></div>
    OSPF
    <div class="bar"><div style="width:88%"></div></div>
    Cisco
    <div class="bar"><div style="width:92%"></div></div>
  </div>
</section>

<section>
  <h2>Projects / Labs</h2>
  <div class="grid">
    <div class="card">
      <h3>MPLS L3VPN Lab</h3>
      <p>Full MPLS core with PE/P routers using VRF segmentation.</p>
    </div>
    <div class="card">
      <h3>BGP Multi-AS</h3>
      <p>eBGP + iBGP design with route reflectors.</p>
    </div>
    <div class="card">
      <h3>OSPF Multi-Area</h3>
      <p>Area 0 backbone with summarization and virtual links.</p>
    </div>
  </div>
</section>

<section>
  <h2>Network Diagrams</h2>
  <div class="grid">
    <div class="card">Diagram 1 (Add image)</div>
    <div class="card">Diagram 2 (Add image)</div>
  </div>
</section>

<section>
  <h2>Blog</h2>
  <div class="card">
    <h3>Understanding MPLS Labels</h3>
    <p>Deep dive into label switching and forwarding behavior.</p>
  </div>
  <div class="card">
    <h3>BGP Path Selection</h3>
    <p>Step-by-step explanation of BGP best path algorithm.</p>
  </div>
</section>

<section>
  <h2>Contact</h2>
  <p>Phone: +95 9456110311</p>
  <p>Email: neolwin.net@gmail.com</p>
  <p><a href="https://neolwin-net.github.io/sp-dc-net/">Portfolio</a></p>
</section>

<script>
function toggleMode() {
  document.body.classList.toggle("light");
}
</script>

</body>
</html>
