# portfolio-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Portfolio of Your Name - Frontend Developer building fast, responsive web experiences.">
  <title> Subham Bhumij | Frontend Developer</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&family=Sora:wght@600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="bg-glow" aria-hidden="true"></div>
  <!---logo image-->

  <header class="header" id="header">
    <nav class="nav container">
      <a href="#home" class="logo ">Game<span>su.</span></a>

      <button class="nav-toggle" id="navToggle" aria-label="Toggle navigation" aria-expanded="false">
        <span></span>
        <span></span>
        <span></span>
      </button>

      <ul class="nav-links" id="navLinks">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="home" class="hero">
      <div class="container hero-grid">
        <div class="hero-text">
          <p class="eyebrow reveal">Hello, I&rsquo;m</p>
          <h1 class="reveal">Subham Bhumij</h1>
          <h2 class="hero-role reveal">I build <span class="typed" id="typed"></span><span class="caret">|</span></h2>
          <p class="hero-desc reveal">
            A frontend developer focused on crafting fast, accessible and
            pixel-perfect interfaces that feel great on every screen.
          </p>

          <div class="hero-actions reveal">
            <a href="#projects" class="btn btn-primary">View My Work</a>
            <a href="#contact" class="btn btn-ghost">Let&rsquo;s Talk</a>
          </div>

          <div class="socials reveal">
            <a href="https://github.com/samon-wq/" target="_blank" rel="noopener" aria-label="GitHub">
              <svg viewBox="0 0 24 24" width="20" height="20" fill="currentColor" aria-hidden="true"><path d="M12 .5a12 12 0 0 0-3.8 23.4c.6.1.8-.3.8-.6v-2c-3.3.7-4-1.6-4-1.6-.6-1.4-1.4-1.8-1.4-1.8-1.1-.8.1-.8.1-.8 1.2.1 1.9 1.3 1.9 1.3 1.1 1.8 2.8 1.3 3.5 1 .1-.8.4-1.3.8-1.6-2.7-.3-5.5-1.3-5.5-5.9 0-1.3.5-2.4 1.2-3.2-.1-.3-.5-1.5.1-3.2 0 0 1-.3 3.3 1.2a11.5 11.5 0 0 1 6 0C17.3 3.4 18.3 3.7 18.3 3.7c.6 1.7.2 2.9.1 3.2.8.8 1.2 1.9 1.2 3.2 0 4.6-2.8 5.6-5.5 5.9.4.4.8 1.1.8 2.2v3.3c0 .3.2.7.8.6A12 12 0 0 0 12 .5Z"/></svg>
            </a>
            <a href="https://www.linkedin.com/in/subham-bhumij/" target="_blank" rel="noopener" aria-label="LinkedIn">
              <svg viewBox="0 0 24 24" width="20" height="20" fill="currentColor" aria-hidden="true"><path d="M4.98 3.5a2.5 2.5 0 1 1 0 5 2.5 2.5 0 0 1 0-5ZM3 9h4v12H3V9Zm6 0h3.8v1.7h.1c.5-1 1.8-2 3.7-2 4 0 4.7 2.5 4.7 5.8V21h-4v-5.7c0-1.4 0-3.2-2-3.2s-2.3 1.5-2.3 3.1V21H9V9Z"/></svg>
            </a>
            <a href="mailto:hello@example.com" aria-label="Email">
              <svg viewBox="0 0 24 24" width="20" height="20" fill="none" stroke="currentColor" stroke-width="1.8" aria-hidden="true"><rect x="3" y="5" width="18" height="14" rx="2"/><path d="m3 7 9 6 9-6"/></svg>
            </a>
          </div>
        </div>

        <div class="hero-visual reveal">
          <div class="avatar-ring-stable">
           <img src="c:\Users\Lenovo\Desktop\portfol\kypo.jpg.jpeg" alt="150px" height="150px">
          </div>
          <span class="float-chip chip-1">HTML</span>
          <span class="float-chip chip-2">CSS</span>
          <span class="float-chip chip-3">JavaScript</span>
        </div>
      </div>
    </section>

    <section id="about" class="section">
      <div class="container">
        <h2 class="section-title reveal">About <span>Me</span></h2>
        <div class="about-grid">
          <div class="about-text reveal">
            <p>
              I&rsquo;m a frontend developer who loves turning ideas into clean,
              interactive experiences. I care about performance, accessibility and
              the small details that make a product feel polished.
            </p>
            <p>
              When I&rsquo;m not coding, you&rsquo;ll find me exploring new design trends,
              contributing to open source, or tweaking side projects.
            </p>
          </div>
          <div class="about-stats reveal">
            <div class="stat">
              <strong>3+</strong>
              <span>Years Experience</span>
            </div>
            <div class="stat">
              <strong>25+</strong>
              <span>Projects Built</span>
            </div>
            <div class="stat">
              <strong>15+</strong>
              <span>Happy Clients</span>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="skills" class="section">
      <div class="container">
        <h2 class="section-title reveal">My <span>Skills</span></h2>
        <div class="skills-grid">
          <div class="skill-card reveal">
            <span class="skill-icon">&lt;/&gt;</span>
            <h3>HTML5</h3>
            <p>Semantic, accessible markup.</p>
          </div>
          <div class="skill-card reveal">
            <span class="skill-icon">#</span>
            <h3>CSS3</h3>
            <p>Flexbox, Grid, animations.</p>
          </div>
          <div class="skill-card reveal">
            <span class="skill-icon">JS</span>
            <h3>JavaScript</h3>
            <p>ES6+, DOM, async patterns.</p>
          </div>
          <div class="skill-card reveal">
            <span class="skill-icon">R</span>
            <h3>React</h3>
            <p>Components and hooks.</p>
          </div>
          <div class="skill-card reveal">
            <span class="skill-icon">N</span>
            <h3>Node.js</h3>
            <p>APIs and tooling.</p>
          </div>
          <div class="skill-card reveal">
            <span class="skill-icon">G</span>
            <h3>Git</h3>
            <p>Version control workflows.</p>
          </div>
          <div class="skill-card reveal">
            <span class="skill-icon">F</span>
            <h3>Figma</h3>
            <p>Design to code handoff.</p>
          </div>
          <div class="skill-card reveal">
            <span class="skill-icon">@</span>
            <h3>Responsive</h3>
            <p>Mobile-first layouts.</p>
          </div>
        </div>
      </div>
    </section>

    <section id="projects" class="section">
      <div class="container">
        <h2 class="section-title reveal">Featured <span>Projects</span></h2>
        <div class="projects-grid">
          <article class="project-card reveal">
            <div class="project-thumb thumb-1">
              <span>Task List App</span>
            </div>
            <div class="project-body">
              <h3>Task List App</h3>
              <p>A clean to-do app with add, complete and delete actions plus local persistence.</p>
              <div class="tags">
                <span>HTML</span><span>CSS</span><span>JS</span>
              </div>
              <a href="#" class="project-link">View Project &rarr;</a>
            </div>
          </article>

          <article class="project-card reveal">
            <div class="project-thumb thumb-2">
              <span>Weather Dashboard</span>
            </div>
            <div class="project-body">
              <h3>Weather Dashboard</h3>
              <p>Live weather data with search, geolocation and a responsive card layout.</p>
              <div class="tags">
                <span>JavaScript</span><span>API</span><span>CSS</span>
              </div>
              <a href="#" class="project-link">View Project &rarr;</a>
            </div>
          </article>

          <article class="project-card reveal">
            <div class="project-thumb thumb-3">
              <span>Landing Page</span>
            </div>
            <div class="project-body">
              <h3>Product Landing Page</h3>
              <p>A conversion-focused landing page with smooth scroll and micro-interactions.</p>
              <div class="tags">
                <span>HTML</span><span>CSS</span><span>Animation</span>
              </div>
              <a href="#" class="project-link">View Project &rarr;</a>
            </div>
          </article>
        </div>
      </div>
    </section>

    <section id="contact" class="section">
      <div class="container">
        <h2 class="section-title reveal">Get In <span>Touch</span></h2>
        <div class="contact-grid">
          <div class="contact-info reveal">
            <p>Have a project in mind or just want to say hi? My inbox is always open.</p>
            <ul class="contact-list">
              <li>
                <span class="contact-label">Email</span>
                <a href="mailto:hello@example.com">hello@example.com</a>
              </li>
              <li>
                <span class="contact-label">Location</span>
                <span>India</span>
              </li>
              <li>
                <span class="contact-label">Social</span>
                <span>@yourhandle</span>
              </li>
            </ul>
          </div>

          <form class="contact-form reveal" id="contactForm">
            <div class="field">
              <label for="name">Name</label>
              <input type="text" id="name" name="name" placeholder="Your name" required>
            </div>
            <div class="field">
              <label for="email">Email</label>
              <input type="email" id="email" name="email" placeholder="you@example.com" required>
            </div>
            <div class="field">
              <label for="message">Message</label>
              <textarea id="message" name="message" rows="4" placeholder="Tell me about your project..." required></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Send Message</button>
            <p class="form-status" id="formStatus" role="status"></p>
          </form>
        </div>
      </div>
    </section>
  </main>

  <footer class="footer">
    <div class="container footer-inner">
      <p>&copy; <span id="year"></span> Your Name. All rights reserved.</p>
      <a href="#home" class="back-top">Back to top &uarr;</a>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>

<css_style>

:root {
  --bg: #0b1020;
  --bg-soft: #101733;
  --card: rgba(255, 255, 255, 0.045);
  --card-border: rgba(255, 255, 255, 0.09);
  --text: #e9edf8;
  --muted: #9aa5bf;
  --accent: #6c7cff;
  --accent-2: #22d3ee;
  --gradient: linear-gradient(135deg, #6c7cff 0%, #22d3ee 100%);
  --radius: 16px;
  --shadow: 0 24px 60px rgba(3, 8, 28, 0.45);
  --container: 1100px;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
  scroll-padding-top: 90px;
}

body {
  font-family: "Inter", system-ui, -apple-system, "Segoe UI", sans-serif;
  background: var(--bg);
  color: var(--text);
  line-height: 1.65;
  overflow-x: hidden;
}

h1, h2, h3, .logo {
  font-family: "Sora", "Inter", sans-serif;
  line-height: 1.15;
}

a {
  color: inherit;
  text-decoration: none;
}

ul {
  list-style: none;
}

.container {
  width: 100%;
  max-width: var(--container);
  margin: 0 auto;
  padding: 0 24px;
}

.bg-glow {
  position: fixed;
  inset: 0;
  z-index: -1;
  background:
    radial-gradient(600px circle at 15% 10%, rgba(108, 124, 255, 0.18), transparent 55%),
    radial-gradient(700px circle at 85% 25%, rgba(34, 211, 238, 0.12), transparent 55%),
    radial-gradient(600px circle at 50% 100%, rgba(108, 124, 255, 0.1), transparent 55%);
  pointer-events: none;
}

.header {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  z-index: 100;
  transition: background 0.3s ease, box-shadow 0.3s ease, padding 0.3s ease;
}

.header.scrolled {
  background: rgba(11, 16, 32, 0.82);
  backdrop-filter: blur(14px);
  box-shadow: 0 10px 30px rgba(3, 8, 28, 0.35);
}

.nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 76px;
}

.logo {
  font-size: 1.5rem;
  font-weight: 700;
  letter-spacing: 0.5px;
}

.logo span {
  color: var(--accent-2);
}

.nav-links {
  display: flex;
  align-items: center;
  gap: 34px;
}

.nav-links a {
  font-size: 0.94rem;
  font-weight: 500;
  color: var(--muted);
  position: relative;
  transition: color 0.25s ease;
}

.nav-links a::after {
  content: "";
  position: absolute;
  left: 0;
  bottom: -6px;
  width: 0;
  height: 2px;
  border-radius: 2px;
  background: var(--gradient);
  transition: width 0.3s ease;
}

.nav-links a:hover,
.nav-links a.active {
  color: var(--text);
}

.nav-links a:hover::after,
.nav-links a.active::after {
  width: 100%;
}

.nav-toggle {
  display: none;
  flex-direction: column;
  gap: 5px;
  width: 42px;
  height: 42px;
  align-items: center;
  justify-content: center;
  background: var(--card);
  border: 1px solid var(--card-border);
  border-radius: 10px;
  cursor: pointer;
}

.nav-toggle span {
  display: block;
  width: 20px;
  height: 2px;
  border-radius: 2px;
  background: var(--text);
  transition: transform 0.3s ease, opacity 0.3s ease;
}

.nav-toggle.open span:nth-child(1) {
  transform: translateY(7px) rotate(45deg);
}

.nav-toggle.open span:nth-child(2) {
  opacity: 0;
}

.nav-toggle.open span:nth-child(3) {
  transform: translateY(-7px) rotate(-45deg);
}

.hero {
  min-height: 100vh;
  display: flex;
  align-items: center;
  padding: 120px 0 80px;
}

.hero-grid {
  display: grid;
  grid-template-columns: 1.15fr 0.85fr;
  gap: 60px;
  align-items: center;
}

.eyebrow {
  color: var(--accent-2);
  font-weight: 600;
  letter-spacing: 2px;
  text-transform: uppercase;
  font-size: 0.82rem;
  margin-bottom: 14px;
}

.hero h1 {
  font-size: clamp(2.6rem, 6vw, 4.4rem);
  letter-spacing: -1.5px;
  background: linear-gradient(180deg, #ffffff 0%, #b9c2e0 100%);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
}

.hero-role {
  font-size: clamp(1.15rem, 2.6vw, 1.6rem);
  font-weight: 600;
  color: var(--muted);
  margin-top: 10px;
  min-height: 1.6em;
}

.typed {
  color: var(--text);
}

.caret {
  color: var(--accent-2);
  font-weight: 400;
  animation: blink 1s step-end infinite;
}

.hero-desc {
  max-width: 520px;
  color: var(--muted);
  margin-top: 22px;
  font-size: 1.02rem;
}

.hero-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 14px;
  margin-top: 34px;
}

.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 13px 26px;
  border-radius: 10px;
  font-weight: 600;
  font-size: 0.95rem;
  border: 1px solid transparent;
  cursor: pointer;
  transition: transform 0.2s ease, box-shadow 0.25s ease, background 0.25s ease, border-color 0.25s ease;
}

.btn-primary {
  background: var(--gradient);
  color: #070b18;
  box-shadow: 0 12px 30px rgba(108, 124, 255, 0.3);
}

.btn-primary:hover {
  transform: translateY(-3px);
  box-shadow: 0 18px 40px rgba(108, 124, 255, 0.42);
}

.btn-ghost {
  background: transparent;
  border-color: var(--card-border);
  color: var(--text);
}

.btn-ghost:hover {
  transform: translateY(-3px);
  border-color: rgba(108, 124, 255, 0.6);
  background: rgba(108, 124, 255, 0.08);
}

.socials {
  display: flex;
  gap: 16px;
  margin-top: 34px;
}

.socials a {
  display: grid;
  place-items: center;
  width: 44px;
  height: 44px;
  border-radius: 12px;
  background: var(--card);
  border: 1px solid var(--card-border);
  color: var(--muted);
  transition: transform 0.25s ease, color 0.25s ease, border-color 0.25s ease, background 0.25s ease;
}

.socials a:hover {
  transform: translateY(-4px);
  color: var(--accent-2);
  border-color: rgba(34, 211, 238, 0.5);
  background: rgba(34, 211, 238, 0.08);
}

.hero-visual {
  position: relative;
  display: grid;
  place-items: center;
  min-height: 340px;
}

.avatar-ring {
  width: clamp(220px, 30vw, 300px);
  aspect-ratio: 1;
  padding: 3px;
  border-radius: 50%;
  background: conic-gradient(from 0deg, #6c7cff, #22d3ee, #6c7cff);
  animation: spin 12s linear infinite;
}

.avatar {
  width: 100%;
  height: 100%;
  border-radius: 50%;
  display: grid;
  place-items: center;
  background: var(--bg-soft);
  color: var(--text);
  font-family: "Sora", sans-serif;
  font-size: clamp(3rem, 7vw, 4.6rem);
  font-weight: 700;
  letter-spacing: 2px;
  animation: spin-reverse 12s linear infinite;
}

.float-chip {
  position: absolute;
  padding: 8px 16px;
  border-radius: 999px;
  font-size: 0.82rem;
  font-weight: 600;
  background: rgba(16, 23, 51, 0.9);
  border: 1px solid var(--card-border);
  box-shadow: var(--shadow);
  animation: float 5s ease-in-out infinite;
}

.chip-1 {
  top: 12%;
  left: 2%;
  color: #ff9f6c;
}

.chip-2 {
  top: 24%;
  right: 0;
  color: #6ca8ff;
  animation-delay: 1s;
}

.chip-3 {
  bottom: 12%;
  left: 8%;
  color: #ffd76c;
  animation-delay: 2s;
}

.section {
  padding: 100px 0;
}

.section-title {
  font-size: clamp(1.8rem, 4vw, 2.6rem);
  margin-bottom: 48px;
  letter-spacing: -0.5px;
}

.section-title::after {
  content: "";
  display: block;
  width: 64px;
  height: 4px;
  margin-top: 14px;
  border-radius: 4px;
  background: var(--gradient);
}

.section-title span {
  color: var(--accent-2);
}

.about-grid {
  display: grid;
  grid-template-columns: 1.3fr 1fr;
  gap: 48px;
  align-items: center;
}

.about-text p {
  color: var(--muted);
  margin-bottom: 18px;
}

.about-text p:last-child {
  margin-bottom: 0;
}

.about-stats {
  display: grid;
  gap: 16px;
}

.stat {
  display: flex;
  align-items: baseline;
  gap: 14px;
  padding: 18px 22px;
  background: var(--card);
  border: 1px solid var(--card-border);
  border-radius: var(--radius);
  transition: transform 0.25s ease, border-color 0.25s ease;
}

.stat:hover {
  transform: translateX(6px);
  border-color: rgba(108, 124, 255, 0.45);
}

.stat strong {
  font-family: "Sora", sans-serif;
  font-size: 1.7rem;
  background: var(--gradient);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
}

.stat span {
  color: var(--muted);
  font-size: 0.92rem;
}

.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 18px;
}

.skill-card {
  padding: 26px 22px;
  background: var(--card);
  border: 1px solid var(--card-border);
  border-radius: var(--radius);
  transition: transform 0.25s ease, border-color 0.25s ease, background 0.25s ease;
}

.skill-card:hover {
  transform: translateY(-6px);
  border-color: rgba(34, 211, 238, 0.45);
  background: rgba(34, 211, 238, 0.06);
}

.skill-icon {
  display: inline-grid;
  place-items: center;
  width: 46px;
  height: 46px;
  border-radius: 12px;
  margin-bottom: 16px;
  font-family: "Sora", sans-serif;
  font-weight: 700;
  font-size: 1rem;
  color: var(--accent-2);
  background: rgba(108, 124, 255, 0.12);
  border: 1px solid rgba(108, 124, 255, 0.28);
}

.skill-card h3 {
  font-size: 1.05rem;
  margin-bottom: 6px;
}

.skill-card p {
  color: var(--muted);
  font-size: 0.88rem;
}

.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(290px, 1fr));
  gap: 26px;
}

.project-card {
  background: var(--card);
  border: 1px solid var(--card-border);
  border-radius: var(--radius);
  overflow: hidden;
  transition: transform 0.3s ease, border-color 0.3s ease, box-shadow 0.3s ease;
}

.project-card:hover {
  transform: translateY(-8px);
  border-color: rgba(108, 124, 255, 0.45);
  box-shadow: var(--shadow);
}

.project-thumb {
  height: 170px;
  display: grid;
  place-items: center;
  font-family: "Sora", sans-serif;
  font-weight: 700;
  font-size: 1.1rem;
  color: rgba(255, 255, 255, 0.92);
  letter-spacing: 0.5px;
}

.thumb-1 {
  background: linear-gradient(135deg, #6c7cff 0%, #3b4bd8 100%);
}

.thumb-2 {
  background: linear-gradient(135deg, #22d3ee 0%, #0e7490 100%);
}

.thumb-3 {
  background: linear-gradient(135deg, #f472b6 0%, #a21caf 100%);
}

.project-body {
  padding: 22px;
}

.project-body h3 {
  font-size: 1.15rem;
  margin-bottom: 8px;
}

.project-body p {
  color: var(--muted);
  font-size: 0.9rem;
  margin-bottom: 16px;
}

.tags {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-bottom: 18px;
}

.tags span {
  font-size: 0.72rem;
  font-weight: 600;
  padding: 4px 10px;
  border-radius: 999px;
  color: var(--accent-2);
  background: rgba(34, 211, 238, 0.1);
  border: 1px solid rgba(34, 211, 238, 0.22);
}

.project-link {
  font-size: 0.9rem;
  font-weight: 600;
  color: var(--text);
  transition: color 0.25s ease, letter-spacing 0.25s ease;
}

.project-link:hover {
  color: var(--accent-2);
  letter-spacing: 0.4px;
}

.contact-grid {
  display: grid;
  grid-template-columns: 1fr 1.1fr;
  gap: 48px;
}

.contact-info p {
  color: var(--muted);
  margin-bottom: 26px;
}

.contact-list li {
  display: flex;
  flex-direction: column;
  gap: 2px;
  padding: 14px 0;
  border-bottom: 1px solid var(--card-border);
}

.contact-label {
  font-size: 0.76rem;
  text-transform: uppercase;
  letter-spacing: 1.4px;
  color: var(--muted);
}

.contact-list a {
  color: var(--text);
  transition: color 0.25s ease;
}

.contact-list a:hover {
  color: var(--accent-2);
}

.contact-form {
  display: grid;
  gap: 18px;
  padding: 30px;
  background: var(--card);
  border: 1px solid var(--card-border);
  border-radius: var(--radius);
}

.field {
  display: grid;
  gap: 7px;
}

.field label {
  font-size: 0.85rem;
  font-weight: 500;
  color: var(--muted);
}

.field input,
.field textarea {
  width: 100%;
  padding: 12px 14px;
  font-family: inherit;
  font-size: 0.95rem;
  color: var(--text);
  background: rgba(255, 255, 255, 0.03);
  border: 1px solid var(--card-border);
  border-radius: 10px;
  outline: none;
  resize: vertical;
  transition: border-color 0.25s ease, box-shadow 0.25s ease;
}

.field input::placeholder,
.field textarea::placeholder {
  color: rgba(154, 165, 191, 0.6);
}

.field input:focus,
.field textarea:focus {
  border-color: rgba(108, 124, 255, 0.7);
  box-shadow: 0 0 0 3px rgba(108, 124, 255, 0.16);
}

.form-status {
  min-height: 1.2em;
  font-size: 0.85rem;
  color: var(--accent-2);
}

.footer {
  border-top: 1px solid var(--card-border);
  padding: 28px 0;
}

.footer-inner {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 16px;
  flex-wrap: wrap;
  color: var(--muted);
  font-size: 0.88rem;
}

.back-top {
  transition: color 0.25s ease;
}

.back-top:hover {
  color: var(--accent-2);
}

.reveal {
  opacity: 0;
  transform: translateY(28px);
  transition: opacity 0.7s ease, transform 0.7s ease;
}

.reveal.visible {
  opacity: 1;
  transform: translateY(0);
}

@keyframes blink {
  50% { opacity: 0; }
}

@keyframes spin {
  to { transform: rotate(360deg); }
}

@keyframes spin-reverse {
  to { transform: rotate(-360deg); }
}

@keyframes float {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-14px); }
}

@media (prefers-reduced-motion: reduce) {
  html { scroll-behavior: auto; }
  *, *::before, *::after {
    animation-duration: 0.001ms !important;
    animation-iteration-count: 1 !important;
    transition-duration: 0.001ms !important;
  }
  .reveal { opacity: 1; transform: none; }
}

@media (max-width: 900px) {
  .hero-grid,
  .about-grid,
  .contact-grid {
    grid-template-columns: 1fr;
  }

  .hero {
    padding-top: 110px;
    text-align: center;
  }

  .hero-desc {
    margin-left: auto;
    margin-right: auto;
  }

  .hero-actions,
  .socials {
    justify-content: center;
  }

  .hero-visual {
    order: -1;
    min-height: 280px;
    margin-bottom: 20px;
  }

  .section-title::after {
    margin-left: auto;
    margin-right: auto;
  }

  .about-grid,
  .contact-grid {
    gap: 34px;
  }

  .section {
    padding: 80px 0;
  }
}

@media (max-width: 760px) {
  .nav-toggle {
    display: flex;
  }

  .nav-links {
    position: fixed;
    top: 76px;
    left: 16px;
    right: 16px;
    flex-direction: column;
    align-items: stretch;
    gap: 4px;
    padding: 14px;
    background: rgba(16, 23, 51, 0.98);
    border: 1px solid var(--card-border);
    border-radius: var(--radius);
    box-shadow: var(--shadow);
    opacity: 0;
    visibility: hidden;
    transform: translateY(-12px);
    transition: opacity 0.28s ease, transform 0.28s ease, visibility 0.28s ease;
  }

  .nav-links.open {
    opacity: 1;
    visibility: visible;
    transform: translateY(0);
  }

  .nav-links a {
    display: block;
    padding: 12px 14px;
    border-radius: 10px;
  }

  .nav-links a:hover {
    background: rgba(108, 124, 255, 0.1);
  }

  .nav-links a::after {
    display: none;
  }

  .contact-form {
    padding: 22px;
  }
}

@media (max-width: 420px) {
  .container {
    padding: 0 18px;
  }

  .btn {
    width: 100%;
  }

  .hero-actions {
    flex-direction: column;
  }

  .section {
    padding: 64px 0;
  }

  .stat {
    padding: 14px 18px;
  }
}

<JS_script>

const header = document.getElementById("header");
const navToggle = document.getElementById("navToggle");
const navLinks = document.getElementById("navLinks");
const typedEl = document.getElementById("typed");

window.addEventListener("scroll", () => {
  header.classList.toggle("scrolled", window.scrollY > 20);
}, { passive: true });

navToggle.addEventListener("click", () => {
  const open = navToggle.classList.toggle("open");
  navLinks.classList.toggle("open", open);
  navToggle.setAttribute("aria-expanded", String(open));
});

navLinks.querySelectorAll("a").forEach((link) => {
  link.addEventListener("click", () => {
    navToggle.classList.remove("open");
    navLinks.classList.remove("open");
    navToggle.setAttribute("aria-expanded", "false");
  });
});

const roles = ["responsive websites", "clean interfaces", "web applications"];
let roleIndex = 0;
let charIndex = 0;
let deleting = false;

const type = () => {
  const current = roles[roleIndex];
  typedEl.textContent = current.slice(0, charIndex);

  if (!deleting) {
    charIndex++;
    if (charIndex > current.length) {
      deleting = true;
      setTimeout(type, 1400);
      return;
    }
  } else {
    charIndex--;
    if (charIndex < 0) {
      deleting = false;
      roleIndex = (roleIndex + 1) % roles.length;
      charIndex = 0;
    }
  }

  setTimeout(type, deleting ? 45 : 95);
};

type();

const reveals = document.querySelectorAll(".reveal");
const revealObserver = new IntersectionObserver((entries) => {
  entries.forEach((entry) => {
    if (entry.isIntersecting) {
      entry.target.classList.add("visible");
      revealObserver.unobserve(entry.target);
    }
  });
}, { threshold: 0.15 });

reveals.forEach((el) => revealObserver.observe(el));

const sections = document.querySelectorAll("section[id]");
const links = navLinks.querySelectorAll("a");

const spy = new IntersectionObserver((entries) => {
  entries.forEach((entry) => {
    if (entry.isIntersecting) {
      links.forEach((link) => {
        link.classList.toggle("active", link.getAttribute("href") === `#${entry.target.id}`);
      });
    }
  });
}, { rootMargin: "-45% 0px -50% 0px" });

sections.forEach((section) => spy.observe(section));

document.getElementById("year").textContent = new Date().getFullYear();

const form = document.getElementById("contactForm");
const formStatus = document.getElementById("formStatus");

form.addEventListener("submit", (event) => {
  event.preventDefault();

  const name = form.name.value.trim();
  const email = form.email.value.trim();
  const message = form.message.value.trim();

  const subject = encodeURIComponent(`Portfolio enquiry from ${name}`);
  const body = encodeURIComponent(`${message}\n\nFrom: ${name} <${email}>`);

  formStatus.textContent = "Opening your email app...";
  window.location.href = `mailto:hello@example.com?subject=${subject}&body=${body}`;
});
