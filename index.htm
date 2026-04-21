<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Scott Priestley — AI Champion & Productivity NERD</title>
<link href="https://fonts.googleapis.com/css2?family=Instrument+Serif:ital@0;1&family=DM+Sans:ital,opsz,wght@0,9..40,300..700;1,9..40,300..700&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  *,*::before,*::after{margin:0;padding:0;box-sizing:border-box}

  :root {
    --bg: #0c0c0e;
    --bg-card: #141418;
    --bg-card-hover: #1a1a20;
    --text: #e8e6e3;
    --text-dim: #8a8a8e;
    --accent: #5ce1c5;
    --accent-glow: rgba(92,225,197,0.12);
    --accent2: #a78bfa;
    --border: rgba(255,255,255,0.06);
    --radius: 16px;
    --font-display: 'Instrument Serif', Georgia, serif;
    --font-body: 'DM Sans', system-ui, sans-serif;
    --font-mono: 'JetBrains Mono', monospace;
  }

  html { scroll-behavior: smooth; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: var(--font-body);
    line-height: 1.6;
    -webkit-font-smoothing: antialiased;
    overflow-x: hidden;
  }

  /* — Grain overlay — */
  body::after {
    content: '';
    position: fixed;
    inset: 0;
    pointer-events: none;
    opacity: 0.03;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)'/%3E%3C/svg%3E");
    z-index: 9999;
  }

  /* — Ambient glow — */
  .glow-orb {
    position: fixed;
    width: 600px;
    height: 600px;
    border-radius: 50%;
    filter: blur(120px);
    opacity: 0.07;
    pointer-events: none;
    z-index: 0;
  }
  .glow-orb--teal { background: var(--accent); top: -200px; right: -100px; }
  .glow-orb--purple { background: var(--accent2); bottom: -200px; left: -100px; }

  /* — Nav — */
  nav {
    position: fixed;
    top: 0; left: 0; right: 0;
    z-index: 100;
    padding: 20px 40px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    backdrop-filter: blur(20px);
    background: rgba(12,12,14,0.7);
    border-bottom: 1px solid var(--border);
  }
  .nav-logo {
    font-family: var(--font-mono);
    font-size: 14px;
    letter-spacing: 2px;
    text-transform: uppercase;
    color: var(--accent);
  }
  .nav-links { display: flex; gap: 32px; }
  .nav-links a {
    color: var(--text-dim);
    text-decoration: none;
    font-size: 14px;
    font-weight: 500;
    letter-spacing: 0.5px;
    transition: color 0.3s;
  }
  .nav-links a:hover { color: var(--accent); }

  /* — Layout — */
  .container { max-width: 1100px; margin: 0 auto; padding: 0 40px; }
  section { position: relative; z-index: 1; }

  /* — Hero — */
  .hero {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding-top: 80px;
  }
  .hero-eyebrow {
    font-family: var(--font-mono);
    font-size: 13px;
    color: var(--accent);
    letter-spacing: 3px;
    text-transform: uppercase;
    margin-bottom: 24px;
    opacity: 0;
    animation: fadeUp 0.8s 0.2s forwards;
  }
  .hero h1 {
    font-family: var(--font-display);
    font-size: clamp(48px, 7vw, 88px);
    line-height: 1.05;
    font-weight: 400;
    margin-bottom: 28px;
    opacity: 0;
    animation: fadeUp 0.8s 0.4s forwards;
  }
  .hero h1 em {
    font-style: italic;
    color: var(--accent);
  }
  .hero-sub {
    font-size: 18px;
    color: var(--text-dim);
    max-width: 520px;
    line-height: 1.7;
    opacity: 0;
    animation: fadeUp 0.8s 0.6s forwards;
  }
  .hero-tags {
    display: flex;
    gap: 12px;
    margin-top: 36px;
    flex-wrap: wrap;
    opacity: 0;
    animation: fadeUp 0.8s 0.8s forwards;
  }
  .tag {
    padding: 8px 18px;
    border-radius: 100px;
    font-size: 13px;
    font-weight: 500;
    border: 1px solid var(--border);
    background: var(--bg-card);
    color: var(--text-dim);
    transition: all 0.3s;
  }
  .tag:hover {
    border-color: var(--accent);
    color: var(--accent);
    background: var(--accent-glow);
  }
  .scroll-cue {
    position: absolute;
    bottom: 40px;
    left: 50%;
    transform: translateX(-50%);
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 8px;
    color: var(--text-dim);
    font-size: 12px;
    letter-spacing: 2px;
    text-transform: uppercase;
    opacity: 0;
    animation: fadeUp 0.8s 1s forwards;
  }
  .scroll-cue .arrow {
    width: 1px;
    height: 40px;
    background: linear-gradient(to bottom, var(--text-dim), transparent);
    animation: pulse 2s infinite;
  }

  /* — Section headers — */
  .section-label {
    font-family: var(--font-mono);
    font-size: 12px;
    color: var(--accent);
    letter-spacing: 3px;
    text-transform: uppercase;
    margin-bottom: 16px;
  }
  .section-title {
    font-family: var(--font-display);
    font-size: clamp(32px, 4vw, 48px);
    font-weight: 400;
    margin-bottom: 48px;
  }

  /* — Projects — */
  .projects { padding: 120px 0; }
  .project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
    gap: 24px;
  }
  .project-card {
    background: var(--bg-card);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 32px;
    transition: all 0.4s cubic-bezier(0.19,1,0.22,1);
    position: relative;
    overflow: hidden;
    text-decoration: none;
    color: inherit;
    display: block;
  }
  .project-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 2px;
    background: linear-gradient(90deg, var(--accent), var(--accent2));
    opacity: 0;
    transition: opacity 0.4s;
  }
  .project-card:hover {
    background: var(--bg-card-hover);
    border-color: rgba(255,255,255,0.1);
    transform: translateY(-4px);
  }
  .project-card:hover::before { opacity: 1; }
  .project-card .card-num {
    font-family: var(--font-mono);
    font-size: 12px;
    color: var(--text-dim);
    margin-bottom: 16px;
  }
  .project-card h3 {
    font-family: var(--font-display);
    font-size: 24px;
    font-weight: 400;
    margin-bottom: 12px;
  }
  .project-card p {
    font-size: 14px;
    color: var(--text-dim);
    line-height: 1.7;
    margin-bottom: 20px;
  }
  .card-tags {
    display: flex;
    gap: 8px;
    flex-wrap: wrap;
  }
  .card-tag {
    font-family: var(--font-mono);
    font-size: 11px;
    padding: 4px 10px;
    border-radius: 6px;
    background: rgba(92,225,197,0.08);
    color: var(--accent);
  }

  /* — About / Insights — */
  .about { padding: 120px 0; }
  .about-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 64px;
    align-items: start;
  }
  .about-text {
    font-size: 16px;
    color: var(--text-dim);
    line-height: 1.8;
  }
  .about-text p + p { margin-top: 20px; }
  .stats-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 24px;
  }
  .stat-card {
    background: var(--bg-card);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 28px;
    text-align: center;
    transition: border-color 0.3s;
  }
  .stat-card:hover { border-color: rgba(92,225,197,0.2); }
  .stat-num {
    font-family: var(--font-display);
    font-size: 36px;
    color: var(--accent);
    display: block;
    margin-bottom: 6px;
  }
  .stat-label {
    font-size: 13px;
    color: var(--text-dim);
  }

  /* — Blog / Posts — */
  .posts { padding: 120px 0; }
  .post-item {
    display: flex;
    align-items: baseline;
    justify-content: space-between;
    gap: 24px;
    padding: 28px 0;
    border-bottom: 1px solid var(--border);
    text-decoration: none;
    color: inherit;
    transition: all 0.3s;
  }
  .post-item:first-child { border-top: 1px solid var(--border); }
  .post-item:hover { padding-left: 16px; }
  .post-item:hover .post-title { color: var(--accent); }
  .post-title {
    font-family: var(--font-display);
    font-size: 22px;
    font-weight: 400;
    transition: color 0.3s;
  }
  .post-date {
    font-family: var(--font-mono);
    font-size: 12px;
    color: var(--text-dim);
    white-space: nowrap;
  }

  /* — Footer — */
  footer {
    padding: 60px 0;
    border-top: 1px solid var(--border);
    margin-top: 40px;
  }
  .footer-inner {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .footer-links { display: flex; gap: 24px; }
  .footer-links a {
    color: var(--text-dim);
    text-decoration: none;
    font-size: 14px;
    transition: color 0.3s;
  }
  .footer-links a:hover { color: var(--accent); }
  .footer-copy {
    font-size: 13px;
    color: var(--text-dim);
  }

  /* — Animations — */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(24px); }
    to { opacity: 1; transform: translateY(0); }
  }
  @keyframes pulse {
    0%, 100% { opacity: 0.3; }
    50% { opacity: 1; }
  }

  .reveal {
    opacity: 0;
    transform: translateY(32px);
    transition: all 0.8s cubic-bezier(0.19,1,0.22,1);
  }
  .reveal.visible {
    opacity: 1;
    transform: translateY(0);
  }

  /* — Responsive — */
  @media (max-width: 768px) {
    nav { padding: 16px 20px; }
    .nav-links { gap: 20px; }
    .container { padding: 0 20px; }
    .about-grid { grid-template-columns: 1fr; gap: 40px; }
    .project-grid { grid-template-columns: 1fr; }
    .post-item { flex-direction: column; gap: 6px; }
    .footer-inner { flex-direction: column; gap: 20px; text-align: center; }
  }
</style>
</head>
<body>

<div class="glow-orb glow-orb--teal"></div>
<div class="glow-orb glow-orb--purple"></div>

<nav>
  <div class="nav-logo">SP</div>
  <div class="nav-links">
    <a href="#projects">Projects</a>
    <a href="#about">About</a>
    <a href="#posts">Posts</a>
    <a href="https://github.com/yourusername" target="_blank">GitHub</a>
  </div>
</nav>

<section class="hero container">
  <div class="hero-eyebrow">AI Champion &amp; Productivity Nerd</div>
  <h1>Scott <em>Priestley</em></h1>
  <p class="hero-sub">Building at the intersection of AI adoption, productivity systems, and delivery excellence. Turning complex problems into elegant, shipped solutions.</p>
  <div class="hero-tags">
    <span class="tag">Productivity</span>
    <span class="tag">AI Adoption &amp; Enablement</span>
    <span class="tag">Delivery Governance &amp; Execution</span>
  </div>
  <div class="scroll-cue">
    <span>Scroll</span>
    <div class="arrow"></div>
  </div>
</section>

<section class="projects container" id="projects">
  <div class="reveal">
    <div class="section-label">Featured Work</div>
    <h2 class="section-title">Projects</h2>
  </div>
  <div class="project-grid">
    <a href="#" class="project-card reveal">
      <div class="card-num">01</div>
      <h3>AI Workflow Automator</h3>
      <p>An intelligent pipeline that streamlines repetitive tasks using LLM-powered agents, reducing manual effort by 60%.</p>
      <div class="card-tags">
        <span class="card-tag">Python</span>
        <span class="card-tag">LangChain</span>
        <span class="card-tag">FastAPI</span>
      </div>
    </a>
    <a href="#" class="project-card reveal">
      <div class="card-num">02</div>
      <h3>Delivery Dashboard</h3>
      <p>Real-time governance dashboard tracking project health, risk signals, and team velocity across multiple workstreams.</p>
      <div class="card-tags">
        <span class="card-tag">React</span>
        <span class="card-tag">D3.js</span>
        <span class="card-tag">Node</span>
      </div>
    </a>
    <a href="#" class="project-card reveal">
      <div class="card-num">03</div>
      <h3>Productivity Toolkit</h3>
      <p>A personal system of scripts, templates, and integrations that automate planning, tracking, and reflection cycles.</p>
      <div class="card-tags">
        <span class="card-tag">TypeScript</span>
        <span class="card-tag">Notion API</span>
        <span class="card-tag">CLI</span>
      </div>
    </a>
  </div>
</section>

<section class="about container" id="about">
  <div class="reveal">
    <div class="section-label">Background</div>
    <h2 class="section-title">About Me</h2>
  </div>
  <div class="about-grid">
    <div class="about-text reveal">
      <p>I'm an AI champion and productivity nerd who thrives on helping teams adopt emerging technology and deliver with clarity. My work sits at the crossroads of enablement, governance, and hands-on execution.</p>
      <p>Whether it's building internal tools, designing delivery frameworks, or evangelizing AI-powered workflows — I care deeply about making work work better.</p>
    </div>
    <div class="stats-grid reveal">
      <div class="stat-card">
        <span class="stat-num">3</span>
        <span class="stat-label">Focus Areas</span>
      </div>
      <div class="stat-card">
        <span class="stat-num">∞</span>
        <span class="stat-label">Curiosity</span>
      </div>
      <div class="stat-card">
        <span class="stat-num">AI</span>
        <span class="stat-label">Powered</span>
      </div>
      <div class="stat-card">
        <span class="stat-num">0→1</span>
        <span class="stat-label">Builder</span>
      </div>
    </div>
  </div>
</section>

<section class="posts container" id="posts">
  <div class="reveal">
    <div class="section-label">Recent</div>
    <h2 class="section-title">Posts</h2>
  </div>
  <div class="reveal">
    <a href="#" class="post-item">
      <span class="post-title">Welcome</span>
      <span class="post-date">2026</span>
    </a>
    <a href="#" class="post-item">
      <span class="post-title">Why Every Team Needs an AI Champion</span>
      <span class="post-date">Coming Soon</span>
    </a>
    <a href="#" class="post-item">
      <span class="post-title">My Productivity Stack, Explained</span>
      <span class="post-date">Coming Soon</span>
    </a>
  </div>
</section>

<footer>
  <div class="container footer-inner">
    <div class="footer-links">
      <a href="https://github.com/yourusername" target="_blank">GitHub</a>
      <a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
    </div>
    <div class="footer-copy">&copy; 2026 Scott Priestley</div>
  </div>
</footer>

<script>
  // Scroll reveal
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(e => {
      if (e.isIntersecting) {
        e.target.classList.add('visible');
        observer.unobserve(e.target);
      }
    });
  }, { threshold: 0.15 });

  document.querySelectorAll('.reveal').forEach(el => observer.observe(el));
</script>
</body>
</html>
