# AnushkaRaut.github.io
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Anushka Raut - MBA | Business Consultant | Venture Capital</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    * {margin: 0; padding: 0; box-sizing: border-box;}
    body {font-family: 'Segoe UI', sans-serif; line-height: 1.6; color: #333; overflow-x: hidden; background: #f9f9f9;}

    /* Hero Section */
    .hero {
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      height: 100vh;
      display: flex; align-items: center; justify-content: center;
      position: relative; color: white; text-align: center;
      overflow: hidden;
    }
    .hero::before {
      content: ''; position: absolute; top: 0; left: 0; right: 0; bottom: 0;
      background: url('https://i.gifer.com/3HeT.gif') center/cover no-repeat;
      opacity: 0.2; z-index: 0;
    }
    .hero-content {z-index: 1; animation: fadeInUp 1s ease-out;}
    .profile-image {width: 200px; height: 200px; border-radius: 50%; overflow: hidden; margin: 0 auto 2rem; border: 5px solid rgba(255,255,255,0.3); box-shadow: 0 0 20px rgba(255,255,255,0.4);}
    .profile-image img {width: 100%; height: 100%; object-fit: cover;}
    .hero h1 {font-size: 3.5rem; margin-bottom: 0.5rem; background: linear-gradient(45deg, #fff, #f0f0f0); -webkit-background-clip: text; -webkit-text-fill-color: transparent;}
    .hero-subtitle {font-size: 1.5rem; margin-bottom: 2rem; opacity: 0.9;}
    .cta-buttons {display: flex; gap: 1rem; justify-content: center; flex-wrap: wrap;}
    .btn {padding: 12px 30px; text-decoration: none; border-radius: 50px; font-weight: 600; transition: all 0.3s ease; display: inline-flex; align-items: center; gap: 0.5rem; position: relative; overflow: hidden;}
    .btn-primary {background: rgba(255,255,255,0.2); color: white; border: 2px solid rgba(255,255,255,0.3); backdrop-filter: blur(10px);}
    .btn-primary:hover {background: white; color: #667eea; transform: translateY(-2px);}

    /* Floating Icons */
    .floating-icons i {
      position: absolute; font-size: 2rem; opacity: 0.15; animation: float 8s ease-in-out infinite;
    }
    .floating-icons i:nth-child(1) {top: 10%; left: 15%; color: #fff; animation-delay: 0s;}
    .floating-icons i:nth-child(2) {top: 40%; right: 20%; color: #ffd700; animation-delay: 2s;}
    .floating-icons i:nth-child(3) {bottom: 15%; left: 25%; color: #fff; animation-delay: 4s;}
    @keyframes float {0%,100%{transform: translateY(0);} 50%{transform: translateY(-20px);}}

    /* Section */
    .section {padding: 5rem 2rem; max-width: 1200px; margin: 0 auto;}
    .section h2 {font-size: 2.5rem; text-align: center; margin-bottom: 3rem; position: relative; color: #333;}
    .section h2::after {content: ''; position: absolute; bottom: -10px; left: 50%; transform: translateX(-50%); width: 60px; height: 3px; background: linear-gradient(45deg, #667eea, #764ba2);}

    /* Experience */
    .experience-card {background: white; border-radius: 15px; padding: 2rem; margin-bottom: 2rem; box-shadow: 0 10px 20px rgba(0,0,0,0.1); transition: all 0.3s ease; position: relative; overflow: hidden;}
    .experience-card:hover {transform: translateY(-8px) scale(1.02);}
    .experience-card::after {content: url('https://i.gifer.com/7efs.gif'); position: absolute; right: 10px; bottom: 10px; width: 50px; opacity: 0.2;}

    /* Skills */
    .skill-category {background: white; border-radius: 15px; padding: 2rem; text-align: center; box-shadow: 0 8px 20px rgba(0,0,0,0.1); transition: transform 0.3s ease;}
    .skill-category:hover {transform: translateY(-5px);}
    .skill-icon {width: 80px; height: 80px; margin: 0 auto 1rem; border-radius: 50%; background: linear-gradient(45deg, #667eea, #764ba2); display: flex; align-items: center; justify-content: center; color: white; font-size: 2rem;}

    /* Contact */
    .contact-item {background: white; padding: 2rem; border-radius: 15px; text-align: center; box-shadow: 0 10px 20px rgba(0,0,0,0.1); transition: transform 0.3s ease;}
    .contact-item:hover {transform: scale(1.05);}

    /* Animations */
    @keyframes fadeInUp {from {opacity: 0; transform: translateY(30px);} to {opacity: 1; transform: translateY(0);}}
  </style>
</head>
<body>
  <!-- Hero Section -->
  <section class="hero" id="home">
    <div class="floating-icons">
      <i class="fas fa-rocket"></i>
      <i class="fas fa-lightbulb"></i>
      <i class="fas fa-chart-line"></i>
    </div>
    <div class="hero-content">
      <div class="profile-image">
        <img src="https://i.imgur.com/0y8Ftya.png" alt="Anushka Raut">
      </div>
      <h1>Anushka Raut</h1>
      <p class="hero-subtitle">MBA Student | Business Consultant | Venture Capital Analyst</p>
      <div class="cta-buttons">
        <a href="#experience" class="btn btn-primary"><i class="fas fa-briefcase"></i> View Experience</a>
        <a href="#contact" class="btn btn-primary"><i class="fas fa-envelope"></i> Get In Touch</a>
      </div>
    </div>
  </section>

  <!-- Example Experience Section -->
  <section class="section" id="experience">
    <h2><i class="fas fa-briefcase"></i> Experience</h2>
    <div class="experience-card">
      <h3><i class="fas fa-chart-line"></i> EY India – Summer Intern</h3>
      <p>Evaluated 8+ Tier-2 cities for GCC setup, benchmarked 20–30% cost savings, authored SOPs & RACI Matrix.</p>
    </div>
    <div class="experience-card">
      <h3><i class="fas fa-users"></i> EY India – Senior Associate</h3>
      <p>Launched EY India’s first global campus recruitment campaign, onboarded 200+ hires and 100+ interns.</p>
    </div>
  </section>

  <!-- Example Skills Section -->
  <section class="section" id="skills">
    <h2><i class="fas fa-cogs"></i> Skills</h2>
    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px,1fr)); gap: 2rem;">
      <div class="skill-category"><div class="skill-icon"><i class="fas fa-chart-bar"></i></div><h3>Consulting</h3><p>Gap Analysis, Process Design, Cost-Benefit Analysis</p></div>
      <div class="skill-category"><div class="skill-icon"><i class="fas fa-seedling"></i></div><h3>Venture Capital</h3><p>Deal Sourcing, Due Diligence, Startup Evaluation</p></div>
    </div>
  </section>

  <!-- Contact Section -->
  <section class="section" id="contact">
    <h2><i class="fas fa-envelope"></i> Contact</h2>
    <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:2rem;">
      <div class="contact-item"><i class="fab fa-linkedin fa-2x" style="color:#667eea"></i><p>linkedin.com/in/anushkaraut</p></div>
      <div class="contact-item"><i class="fas fa-envelope fa-2x" style="color:#764ba2"></i><p>anushka.raut@email.com</p></div>
    </div>
  </section>
</body>
</html>
