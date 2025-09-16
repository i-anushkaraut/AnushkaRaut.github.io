# AnushkaRaut.github.io
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Your Name — Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: "Poppins", sans-serif;
      background: linear-gradient(135deg, #1a1a2e, #16213e, #0f3460);
      color: #f1f1f1;
    }
    header {
      text-align: center;
      padding: 50px 20px;
    }
    header img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 4px solid #e94560;
    }
    header h1 {
      margin: 15px 0 5px;
      font-size: 2.2rem;
    }
    header p {
      margin: 0;
      font-size: 1rem;
      color: #ccc;
    }
    .hero {
      background: url("https://picsum.photos/1600/500?blur=2") no-repeat center/cover;
      padding: 120px 20px;
      text-align: center;
      color: white;
      position: relative;
    }
    .hero h2 {
      font-size: 2.5rem;
      margin: 0;
    }
    .hero p {
      font-size: 1.2rem;
      margin-top: 10px;
    }
    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 25px;
      border-radius: 25px;
      background: #e94560;
      color: white;
      font-weight: 600;
      text-decoration: none;
      transition: background 0.3s;
    }
    .btn:hover {
      background: #ff4f72;
    }
    .section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .section h3 {
      text-align: center;
      margin-bottom: 30px;
      font-size: 1.8rem;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }
    .card {
      background: rgba(255,255,255,0.05);
      border-radius: 15px;
      overflow: hidden;
      box-shadow: 0 4px 20px rgba(0,0,0,0.4);
      transition: transform 0.3s;
    }
    .card:hover {
      transform: translateY(-8px);
    }
    .card img {
      width: 100%;
      height: 160px;
      object-fit: cover;
    }
    .card .content {
      padding: 15px;
    }
    .card h4 {
      margin: 0 0 8px;
      font-size: 1.2rem;
    }
    .card p {
      font-size: 0.9rem;
      color: #ccc;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: rgba(255,255,255,0.05);
      margin-top: 40px;
      font-size: 0.9rem;
    }
    footer a {
      color: #e94560;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <img src="https://avatars.githubusercontent.com/u/583231?v=4" alt="Profile">
    <h1>Your Name</h1>
    <p>Developer • Open Source Enthusiast • MBA Student</p>
  </header>

  <div class="hero">
    <h2>Welcome to My Portfolio</h2>
    <p>Exploring ideas, building projects, and sharing knowledge</p>
    <a href="#projects" class="btn">View My Work</a>
  </div>

  <section id="projects" class="section">
    <h3>Projects</h3>
    <div class="projects">
      <div class="card">
        <img src="https://picsum.photos/400/200?random=1" alt="Project 1">
        <div class="content">
          <h4>Project One</h4>
          <p>A web app that helps students plan routines efficiently.</p>
        </div>
      </div>
      <div class="card">
        <img src="https://picsum.photos/400/200?random=2" alt="Project 2">
        <div class="content">
          <h4>Project Two</h4>
          <p>Data visualization dashboard using Python and Tableau.</p>
        </div>
      </div>
      <div class="card">
        <img src="https://picsum.photos/400/200?random=3" alt="Project 3">
        <div class="content">
          <h4>Project Three</h4>
          <p>Mobile-first app concept to track sustainable living habits.</p>
        </div>
      </div>
    </div>
  </section>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Your Name — Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: "Poppins", sans-serif;
      background: linear-gradient(135deg, #1a1a2e, #16213e, #0f3460);
      color: #f1f1f1;
      transition: background 0.5s, color 0.5s;
    }
    body.light {
      background: #f5f5f5;
      color: #222;
    }
    header {
      text-align: center;
      padding: 40px 20px;
    }
    header img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 4px solid #e94560;
    }
    header h1 {
      margin: 15px 0 5px;
      font-size: 2.2rem;
    }
    header p {
      margin: 0;
      font-size: 1rem;
      color: #ccc;
    }
    body.light header p {
      color: #555;
    }
    .hero {
      background: url("https://picsum.photos/1600/500?blur=2") no-repeat center/cover;
      padding: 120px 20px;
      text-align: center;
      color: white;
      position: relative;
    }
    .hero h2 {
      font-size: 2.5rem;
      margin: 0;
    }
    .hero p {
      font-size: 1.2rem;
      margin-top: 10px;
    }
    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 25px;
      border-radius: 25px;
      background: #e94560;
      color: white;
      font-weight: 600;
      text-decoration: none;
      transition: background 0.3s;
    }
    .btn:hover {
      background: #ff4f72;
    }
    .section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .section h3 {
      text-align: center;
      margin-bottom: 30px;
      font-size: 1.8rem;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }
    .card {
      background: rgba(255,255,255,0.05);
      border-radius: 15px;
      overflow: hidden;
      box-shadow: 0 4px 20px rgba(0,0,0,0.4);
      transition: transform 0.3s, box-shadow 0.3s;
      cursor: pointer;
    }
    .card:hover {
      transform: translateY(-8px) scale(1.02);
      box-shadow: 0 6px 25px rgba(0,0,0,0.6);
    }
    .card img {
      width: 100%;
      height: 160px;
      object-fit: cover;
    }
    .card .content {
      padding: 15px;
    }
    .card h4 {
      margin: 0 0 8px;
      font-size: 1.2rem;
    }
    .card p {
      font-size: 0.9rem;
      color: #ccc;
    }
    body.light .card {
      background: #fff;
      color: #222;
    }
    body.light .card p {
      color: #444;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: rgba(255,255,255,0.05);
      margin-top: 40px;
      font-size: 0.9rem;
    }
    footer a {
      color: #e94560;
      text-decoration: none;
    }
    /* Floating theme toggle button */
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
      transition: background 0.3s;
    }
    #themeToggle:hover {
      background: #ff4f72;
    }
    /* Typing animation */
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
    <img src="https://avatars.githubusercontent.com/u/583231?v=4" alt="Profile">
    <h1>Your Name</h1>
    <p><span class="typing" id="typing-text"></span></p>
  </header>

  <div class="hero">
    <h2>Welcome to My Portfolio</h2>
    <p>Exploring ideas, building projects, and sharing knowledge</p>
    <a href="#projects" class="btn">View My Work</a>
  </div>

  <section id="projects" class="section">
    <h3>Projects</h3>
    <div class="projects">
      <div class="card">
        <img src="https://picsum.photos/400/200?random=1" alt="Project 1">
        <div class="content">
          <h4>Project One</h4>
          <p>A web app that helps students plan routines efficiently.</p>
        </div>
      </div>
      <div class="card">
        <img src="https://picsum.photos/400/200?random=2" alt="Project 2">
        <div class="content">
          <h4>Project Two</h4>
          <p>Data visualization dashboard using Python and Tableau.</p>
        </div>
      </div>
      <div class="card">
        <img src="https://picsum.photos/400/200?random=3" alt="Project 3">
        <div class="content">
          <h4>Project Three</h4>
          <p>Mobile-first app concept to track sustainable living habits.</p>
        </div>
      </div>
    </div>
  </section>

  <footer>
    © 2025 Your Name — Built with ❤️ • <a href="https://github.com/yourusername">GitHub</a>
  </footer>

  <button id="themeToggle">☀️</button>

  <script>
    // Theme Toggle
    const toggleBtn = document.getElementById("themeToggle");
    toggleBtn.addEventListener("click", () => {
      document.body.classList.toggle("light");
      toggleBtn.textContent = document.body.classList.contains("light") ? "🌙" : "☀️";
    });

    // Typing effect
    const roles = ["Developer", "Open Source Contributor", "MBA Student", "Problem Solver"];
    let roleIndex = 0;
    let charIndex = 0;
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

    // Smooth scrolling for anchor links
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener("click", function(e) {
        e.preventDefault();
        document.querySelector(this.getAttribute("href")).scrollIntoView({
          behavior: "smooth"
        });
      });
    });
  </script>
</body>
    © 2025 Your Name — Built with ❤️ • <a href="https://github.com/yourusername">GitHub</a>
  </footer>
</body>
</html>
