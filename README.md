# AnushkaRaut.github.io
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Anushka Raut — Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: "Poppins", sans-serif;
      background: linear-gradient(135deg, #1a1a2e, #16213e, #0f3460);
      color: #f1f1f1;
      scroll-behavior: smooth;
      transition: background 0.5s, color 0.5s;
    }
    body.light {
      background: #f5f5f5;
      color: #222;
    }
    header {
      text-align: center;
      padding: 50px 20px;
    }
    header h1 {
      margin: 10px 0;
      font-size: 2.5rem;
      color: #e94560;
    }
    header p {
      margin: 5px 0;
    }
    nav {
      text-align: center;
      margin-top: 20px;
    }
    nav a {
      margin: 0 10px;
      text-decoration: none;
      color: #f1f1f1;
      font-weight: 600;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #e94560;
    }
    .section {
      max-width: 1000px;
      margin: 60px auto;
      padding: 0 20px;
    }
    .section h2 {
      text-align: center;
      margin-bottom: 30px;
      font-size: 2rem;
    }
    .card {
      background: rgba(255,255,255,0.05);
      padding: 20px;
      border-radius: 12px;
      margin-bottom: 20px;
      transition: transform 0.3s;
    }
    .card:hover {
      transform: translateY(-6px);
    }
    footer {
      text-align: center;
      padding: 20px;
      background: rgba(255,255,255,0.05);
      font-size: 0.9rem;
    }
    #themeToggle {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #e94560;
      color: white;
      border: none;
      padding: 12px 18px;
      border-radius: 50%;
      font-size: 1.2rem;
      cursor: pointer;
      box-shadow: 0 4px 15px rgba(0,0,0,0.4);
    }
    #themeToggle:hover {
      background: #ff4f72;
    }
    .typing {
      border-right: 3px solid #e94560;
      white-space: nowrap;
      overflow: hidden;
      display: inline-block;
      animation: blink 0.7s step-end infinite;
    }
    @keyframes blink {
      from, to { border-color: transparent }
      50% { border-color: #e94560 }
    }
  </style>
</head>
<body>
  <header>
    <h1>Anushka Raut</h1>
    <p><span class="typing" id="typing-text"></span></p>
    <p>Email: <a href="mailto:Anushka.Raut2026@bitsom.edu.in">Anushka.Raut2026@bitsom.edu.in</a></p>
    <p>LinkedIn: <a href="https://linkedin.com/in/anushka-raut-49255b1b4" target="_blank">linkedin.com/in/anushka-raut</a></p>
    <p>Phone: +91 9920891949</p>
    <nav>
      <a href="#education">Education</a>
      <a href="#experience">Experience</a>
      <a href="#responsibility">Positions</a>
      <a href="#certifications">Certifications</a>
      <a href="#extracurriculars">Extracurriculars</a>
    </nav>
  </header>

  <section id="education" class="section">
    <h2>Education</h2>
    <div class="card">MBA — BITSoM, Mumbai (Class of 2026)</div>
    <div class="card">B.Com — R. A. Podar College of Commerce & Economics (CGPA 8.16, 2021)</div>
    <div class="card">HSC — D.A.V. International School (88%, 2018)</div>
    <div class="card">SSC — D.A.V. International School (CGPA 9.6, 2016)</div>
  </section>

  <section id="experience" class="section">
    <h2>Professional Experience</h2>
    <div class="card">
      <strong>EY India — Summer Intern, Business Consulting (Apr’25 - May’25)</strong>
      <ul>
        <li>Evaluated 8+ Tier-2 cities for GCC setup, recommending top 3 for scalability.</li>
        <li>Conducted gap analysis across 15+ finance processes, reducing manual effort ~25%.</li>
        <li>Designed HR transition blueprint evaluating 40+ processes across functions.</li>
      </ul>
    </div>
    <div class="card">
      <strong>EY India — Senior Associate, Talent Acquisition (Jun’21 - May’24)</strong>
      <ul>
        <li>Awarded Business Extraordinaire (team of 300+).</li>
        <li>Led premier B-school hiring, onboarding 200+ hires & 100+ interns.</li>
        <li>Oversaw PI & Parthenon merger integration, achieving ~80% application share from top MBAs.</li>
        <li>Developed recruitment dashboards on Power BI & Tableau.</li>
        <li>Organized national case competitions with 9,000+ participants.</li>
      </ul>
    </div>
  </section>

  <section id="responsibility" class="section">
    <h2>Positions of Responsibility</h2>
    <div class="card">Placement Committee — Member (1/8), drove placement policy reforms.</div>
    <div class="card">Shelf Indulgence Club — Coordinated campus book buzz activities.</div>
    <div class="card">Student Secretary, Industrial Interface Forum — Organized visits & lectures.</div>
  </section>

  <section id="certifications" class="section">
    <h2>Certifications</h2>
    <div class="card">EY Strategy Bronze (2022)</div>
    <div class="card">EY Process Innovation Bronze (2023)</div>
    <div class="card">EY Marketing Bronze (2023)</div>
  </section>

  <section id="extracurriculars" class="section">
    <h2>Extracurricular Activities</h2>
    <div class="card">Colgate LEAP Forward — Innovation Masterclass (2024)</div>
    <div class="card">EY CSR — Mentored students & supported EY Ripples (2024)</div>
    <div class="card">Sports — Secured 2nd place in Athletics & Relay (2016)</div>
  </section>

  <footer>
    © 2025 Anushka Raut — Built with ❤️ | <a href="https://github.com/yourusername" target="_blank">GitHub</a>
  </footer>

  <button id="themeToggle">☀️</button>

  <script>
    // Theme toggle
    const toggleBtn = document.getElementById("themeToggle");
    toggleBtn.addEventListener("click", () => {
      document.body.classList.toggle("light");
      toggleBtn.textContent = document.body.classList.contains("light") ? "🌙" : "☀️";
    });

    // Typing effect
    const roles = ["MBA Student @ BITSoM", "Ex-EY Talent Acquisition", "Business Consulting Intern", "Aspiring Product Leader"];
    let roleIndex = 0, charIndex = 0;
    const typingText = document.getElementById("typing-text");

    function type() {
      if (charIndex < roles[roleIndex].length) {
        typingText.textContent += roles[roleIndex].charAt(charIndex);
        charIndex++;
        setTimeout(type, 120);
      } else {
        setTimeout(erase, 1500);
      }
    }

    function erase() {
      if (charIndex > 0) {
        typingText.textContent = roles[roleIndex].substring(0, charIndex - 1);
        charIndex--;
        setTimeout(erase, 80);
      } else {
        roleIndex = (roleIndex + 1) % roles.length;
        setTimeout(type, 200);
      }
    }

    document.addEventListener("DOMContentLoaded", () => {
      type();
    });
  </script>
</body>
</html>
