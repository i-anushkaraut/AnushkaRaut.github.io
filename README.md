# AnushkaRaut.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Anushka Raut — Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    body {
      margin: 0;
      font-family: "Poppins", sans-serif;
      background: linear-gradient(270deg, #ff6b6b, #f7b42c, #6a82fb, #00c6ff);
      background-size: 800% 800%;
      animation: bgShift 15s ease infinite;
      color: #fff;
      scroll-behavior: smooth;
    }
    @keyframes bgShift {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
    header {
      text-align: center;
      padding: 60px 20px;
    }
    header h1 {
      font-size: 3rem;
      margin: 10px 0;
      color: #fff;
      text-shadow: 2px 2px 10px rgba(0,0,0,0.5);
    }
    header p {
      margin: 5px 0;
      font-size: 1.2rem;
    }
    nav {
      margin-top: 20px;
    }
    nav a {
      margin: 0 10px;
      text-decoration: none;
      color: #fff;
      font-weight: 600;
      font-size: 1rem;
      transition: color 0.3s;
    }
    nav a:hover {
      color: yellow;
    }
    .hero {
      text-align: center;
      padding: 80px 20px;
      position: relative;
    }
    .hero img {
      max-width: 300px;
      border-radius: 20px;
      box-shadow: 0 8px 30px rgba(0,0,0,0.6);
    }
    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 14px 30px;
      border-radius: 30px;
      background: #fff;
      color: #000;
      font-weight: 700;
      text-decoration: none;
      transition: transform 0.3s, background 0.3s;
    }
    .btn:hover {
      transform: scale(1.1);
      background: #ffe600;
    }
    .section {
      max-width: 1100px;
      margin: 60px auto;
      padding: 0 20px;
      text-align: center;
    }
    .section h2 {
      font-size: 2.4rem;
      margin-bottom: 30px;
      text-shadow: 1px 1px 6px rgba(0,0,0,0.5);
    }
    .card {
      background: rgba(255,255,255,0.1);
      padding: 20px;
      border-radius: 15px;
      margin-bottom: 20px;
      text-align: left;
      transition: transform 0.4s, opacity 0.4s;
      opacity: 0;
    }
    .card.visible {
      opacity: 1;
      transform: translateY(0);
    }
    .card:hover {
      transform: scale(1.05);
      background: rgba(255,255,255,0.2);
    }
    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      background: rgba(0,0,0,0.3);
    }
    .gif {
      max-width: 150px;
      margin: 20px auto;
      display: block;
    }
  </style>
</head>
<body>
  <header>
    <h1>✨ Anushka Raut ✨</h1>
    <p><i class="fa-solid fa-envelope"></i> <a href="mailto:Anushka.Raut2026@bitsom.edu.in" style="color:#fff">Anushka.Raut2026@bitsom.edu.in</a></p>
    <p><i class="fa-brands fa-linkedin"></i> <a href="https://linkedin.com/in/anushka-raut-49255b1b4" target="_blank" style="color:#fff">LinkedIn</a></p>
    <p><i class="fa-solid fa-phone"></i> +91 9920891949</p>
    <nav>
      <a href="#education">Education</a>
      <a href="#experience">Experience</a>
      <a href="#responsibility">Positions</a>
      <a href="#certifications">Certifications</a>
      <a href="#extracurriculars">Extracurriculars</a>
    </nav>
  </header>

  <section class="hero">
    <img src="https://media.giphy.com/media/3oKIPwoeGErMmaI43C/giphy.gif" alt="Working GIF">
    <h2>Welcome to My World 🚀</h2>
    <p>MBA @ BITSoM | Ex-EY | Aspiring Product Leader</p>
    <a class="btn" href="Anushka_Raut_CV.pdf" download><i class="fa-solid fa-file-pdf"></i> Download CV</a>
  </section>

  <section id="education" class="section">
    <h2>🎓 Education</h2>
    <img src="https://media.giphy.com/media/26AHONQ79FdWZhAI0/giphy.gif" class="gif" alt="Book GIF">
    <div class="card">MBA — BITSoM, Mumbai (Class of 2026)</div>
    <div class="card">B.Com — R. A. Podar College of Commerce & Economics (CGPA 8.16, 2021)</div>
    <div class="card">HSC — D.A.V. International School (88%, 2018)</div>
    <div class="card">SSC — D.A.V. International School (CGPA 9.6, 2016)</div>
  </section>

  <section id="experience" class="section">
    <h2>💼 Experience</h2>
    <img src="https://media.giphy.com/media/xT9IglzY3lTjz8OhTi/giphy.gif" class="gif" alt="Work GIF">
    <div class="card"><strong>EY India — Summer Intern</strong><br>Evaluated Tier-2 cities for GCC setup, reduced process inefficiencies by ~25%.</div>
    <div class="card"><strong>EY India — Senior Associate</strong><br>Led hiring, onboarding 200+ hires, drove merger integration & employer branding.</div>
  </section>

  <section id="responsibility" class="section">
    <h2>📌 Positions of Responsibility</h2>
    <img src="https://media.giphy.com/media/26ufcYAkp8e66vanu/giphy.gif" class="gif" alt="Leadership GIF">
    <div class="card">Placement Committee — Senior Member</div>
    <div class="card">Shelf Indulgence Club — Promoted campus book culture</div>
    <div class="card">Industrial Interface Forum — Organized guest lectures & visits</div>
  </section>

  <section id="certifications" class="section">
    <h2>📜 Certifications</h2>
    <img src="https://media.giphy.com/media/l0HlNaQ6gWfllcjDO/giphy.gif" class="gif" alt="Certificate GIF">
    <div class="card">EY Strategy Bronze (2022)</div>
    <div class="card">EY Process Innovation Bronze (2023)</div>
    <div class="card">EY Marketing Bronze (2023)</div>
  </section>

  <section id="extracurriculars" class="section">
    <h2>🌟 Extracurriculars</h2>
    <img src="https://media.giphy.com/media/26AHONQ79FdWZhAI0/giphy.gif" class="gif" alt="Sports GIF">
    <div class="card">Colgate LEAP Forward — Innovation Masterclass</div>
    <div class="card">EY CSR — Mentored students & supported EY Ripples</div>
    <div class="card">Sports — 2nd place in Athletics & Relay</div>
  </section>

  <footer>
    © 2025 Anushka Raut — Built with ❤️ | <a href="https://github.com/yourusername" target="_blank">GitHub</a>
  </footer>

  <script>
    // Scroll fade-in animation
    const cards = document.querySelectorAll('.card');
    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('visible');
        }
      });
    }, { threshold: 0.2 });

    cards.forEach(card => observer.observe(card));
  </script>
</body>
</html>
