---
layout: default
title: Scott Priestley — AI Champion & Productivity NERD
---

<section class="hero container">
  <div class="hero-eyebrow">AI Champion &amp; Productivity Nerd</div>
  <h1>Scott <em>Priestley</em></h1>
  <p class="hero-sub">Championing the intersection of AI adoption, productivity systems, and delivery excellence.</p>
  <div class="hero-tags">
    <span class="tag">Productivity</span>
    <span class="tag">AI Adoption &amp; Enablement</span>
    <span class="tag">Delivery Execellence &amp; Execution</span>
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
    {% assign project_num = 0 %}
    {% for project in site.projects %}
    {% assign project_num = project_num | plus: 1 %}
    <a href="{{ project.url | relative_url }}" class="project-card reveal">
      <div class="card-num">{{ project_num | prepend: '00' | slice: -2, 2 }}</div>
      <h3>{{ project.title }}</h3>
      <p>{{ project.description | default: project.excerpt | strip_html | truncate: 160 }}</p>
      {% if project.tags %}
      <div class="card-tags">
        {% for tag in project.tags %}
        <span class="card-tag">{{ tag }}</span>
        {% endfor %}
      </div>
      {% endif %}
    </a>
    {% endfor %}
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
        <span class="stat-num">{{ site.projects | size }}</span>
        <span class="stat-label">Projects</span>
      </div>
      <div class="stat-card">
        <span class="stat-num">{{ site.posts | size }}</span>
        <span class="stat-label">Posts</span>
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
    {% for post in site.posts limit:10 %}
    <a href="{{ post.url | relative_url }}" class="post-item">
      <span class="post-title">{{ post.title }}</span>
      <span class="post-date">{{ post.date | date: "%b %d, %Y" }}</span>
    </a>
    {% endfor %}
  </div>
</section>
