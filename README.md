# AnushkaRaut.github.io
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anushka Raut - MBA | Business Consultant | Venture Capital</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            overflow-x: hidden;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            color: white;
            text-align: center;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><defs><pattern id="grain" width="100" height="100" patternUnits="userSpaceOnUse"><circle cx="20" cy="20" r="1" fill="white" opacity="0.1"/><circle cx="80" cy="40" r="1" fill="white" opacity="0.1"/><circle cx="40" cy="80" r="1" fill="white" opacity="0.1"/></pattern></defs><rect width="100" height="100" fill="url(%23grain)"/></svg>');
            opacity: 0.3;
        }

        .hero-content {
            z-index: 1;
            animation: fadeInUp 1s ease-out;
        }

        .profile-image {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            background: linear-gradient(45deg, #f0f0f0, #e0e0e0);
            margin: 0 auto 2rem;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 4rem;
            color: #667eea;
            border: 5px solid rgba(255,255,255,0.3);
            animation: pulse 2s infinite;
        }

        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 0.5rem;
            background: linear-gradient(45deg, #fff, #f0f0f0);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .hero-subtitle {
            font-size: 1.5rem;
            margin-bottom: 2rem;
            opacity: 0.9;
        }

        .cta-buttons {
            display: flex;
            gap: 1rem;
            justify-content: center;
            flex-wrap: wrap;
        }

        .btn {
            padding: 12px 30px;
            text-decoration: none;
            border-radius: 50px;
            font-weight: 600;
            transition: all 0.3s ease;
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
        }

        .btn-primary {
            background: rgba(255,255,255,0.2);
            color: white;
            border: 2px solid rgba(255,255,255,0.3);
            backdrop-filter: blur(10px);
        }

        .btn-primary:hover {
            background: white;
            color: #667eea;
            transform: translateY(-2px);
        }

        /* Navigation */
        .navbar {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(255,255,255,0.95);
            backdrop-filter: blur(10px);
            z-index: 1000;
            padding: 1rem 0;
            transform: translateY(-100%);
            transition: transform 0.3s ease;
        }

        .navbar.visible {
            transform: translateY(0);
        }

        .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: 700;
            color: #667eea;
        }

        .nav-links {
            display: flex;
            list-style: none;
            gap: 2rem;
        }

        .nav-links a {
            text-decoration: none;
            color: #333;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        .nav-links a:hover {
            color: #667eea;
        }

        /* Sections */
        .section {
            padding: 5rem 0;
            max-width: 1200px;
            margin: 0 auto;
            padding-left: 2rem;
            padding-right: 2rem;
        }

        .section h2 {
            font-size: 2.5rem;
            text-align: center;
            margin-bottom: 3rem;
            color: #333;
            position: relative;
        }

        .section h2::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 60px;
            height: 3px;
            background: linear-gradient(45deg, #667eea, #764ba2);
        }

        /* Experience Cards */
        .experience-grid {
            display: grid;
            gap: 2rem;
            margin-bottom: 3rem;
        }

        .experience-card {
            background: white;
            border-radius: 15px;
            padding: 2rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            border-left: 5px solid #667eea;
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .experience-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 3px;
            background: linear-gradient(90deg, #667eea, #764ba2);
        }

        .experience-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.15);
        }

        .experience-header {
            display: flex;
            align-items: center;
            gap: 1rem;
            margin-bottom: 1.5rem;
        }

        .company-icon {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            background: linear-gradient(45deg, #667eea, #764ba2);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 1.5rem;
        }

        .experience-title {
            flex: 1;
        }

        .experience-title h3 {
            color: #333;
            font-size: 1.3rem;
            margin-bottom: 0.3rem;
        }

        .experience-title .company {
            color: #667eea;
            font-weight: 600;
        }

        .experience-title .duration {
            color: #666;
            font-size: 0.9rem;
        }

        .achievement-list {
            list-style: none;
        }

        .achievement-list li {
            margin-bottom: 0.8rem;
            padding-left: 1.5rem;
            position: relative;
            color: #555;
        }

        .achievement-list li::before {
            content: '▶';
            position: absolute;
            left: 0;
            color: #667eea;
            font-size: 0.8rem;
        }

        /* Skills Section */
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }

        .skill-category {
            background: white;
            border-radius: 15px;
            padding: 2rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            text-align: center;
            transition: transform 0.3s ease;
        }

        .skill-category:hover {
            transform: translateY(-5px);
        }

        .skill-icon {
            width: 80px;
            height: 80px;
            margin: 0 auto 1rem;
            border-radius: 50%;
            background: linear-gradient(45deg, #667eea, #764ba2);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 2rem;
        }

        .skill-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            justify-content: center;
            margin-top: 1rem;
        }

        .skill-tag {
            background: rgba(102, 126, 234, 0.1);
            color: #667eea;
            padding: 0.3rem 0.8rem;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: 500;
        }

        /* Education Timeline */
        .education-timeline {
            position: relative;
            padding-left: 2rem;
        }

        .education-timeline::before {
            content: '';
            position: absolute;
            left: 1rem;
            top: 0;
            bottom: 0;
            width: 2px;
            background: linear-gradient(180deg, #667eea, #764ba2);
        }

        .education-item {
            position: relative;
            margin-bottom: 2rem;
            background: white;
            padding: 1.5rem;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            margin-left: 2rem;
        }

        .education-item::before {
            content: '';
            position: absolute;
            left: -2.5rem;
            top: 50%;
            transform: translateY(-50%);
            width: 15px;
            height: 15px;
            border-radius: 50%;
            background: #667eea;
            border: 3px solid white;
        }

        /* Contact Section */
        .contact-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            text-align: center;
        }

        .contact-item {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .contact-item:hover {
            transform: translateY(-5px);
        }

        .contact-icon {
            width: 60px;
            height: 60px;
            margin: 0 auto 1rem;
            border-radius: 50%;
            background: linear-gradient(45deg, #667eea, #764ba2);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 1.5rem;
        }

        /* Animations */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes pulse {
            0%, 100% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.05);
            }
        }

        .fade-in {
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.6s ease;
        }

        .fade-in.visible {
            opacity: 1;
            transform: translateY(0);
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2.5rem;
            }
            
            .hero-subtitle {
                font-size: 1.2rem;
            }
            
            .nav-links {
                display: none;
            }
            
            .section {
                padding: 3rem 1rem;
            }
            
            .cta-buttons {
                flex-direction: column;
                align-items: center;
            }
        }

        /* Background Animation */
        .floating-shapes {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: -1;
        }

        .shape {
            position: absolute;
            opacity: 0.1;
            animation: float 6s ease-in-out infinite;
        }

        .shape:nth-child(1) {
            top: 20%;
            left: 10%;
            animation-delay: 0s;
        }

        .shape:nth-child(2) {
            top: 60%;
            right: 10%;
            animation-delay: 2s;
        }

        .shape:nth-child(3) {
            bottom: 20%;
            left: 20%;
            animation-delay: 4s;
        }

        @keyframes float {
            0%, 100% {
                transform: translateY(0px) rotate(0deg);
            }
            50% {
                transform: translateY(-20px) rotate(180deg);
            }
        }
    </style>
</head>
<body>
    <!-- Floating Background Shapes -->
    <div class="floating-shapes">
        <i class="fas fa-chart-line shape" style="font-size: 3rem; color: #667eea;"></i>
        <i class="fas fa-lightbulb shape" style="font-size: 2.5rem; color: #764ba2;"></i>
        <i class="fas fa-rocket shape" style="font-size: 2rem; color: #667eea;"></i>
    </div>

    <!-- Navigation -->
    <nav class="navbar" id="navbar">
        <div class="nav-container">
            <div class="logo">AR</div>
            <ul class="nav-links">
                <li><a href="#home" onclick="scrollTo('#home')">Home</a></li>
                <li><a href="#experience" onclick="scrollTo('#experience')">Experience</a></li>
                <li><a href="#skills" onclick="scrollTo('#skills')">Skills</a></li>
                <li><a href="#education" onclick="scrollTo('#education')">Education</a></li>
                <li><a href="#contact" onclick="scrollTo('#contact')">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <div class="profile-image">
                <i class="fas fa-user-graduate"></i>
            </div>
            <h1>Anushka Raut</h1>
            <p class="hero-subtitle">MBA Student | Business Consultant | Venture Capital Analyst</p>
            <div class="cta-buttons">
                <a href="#experience" class="btn btn-primary" onclick="scrollTo('#experience')">
                    <i class="fas fa-briefcase"></i> View Experience
                </a>
                <a href="#contact" class="btn btn-primary" onclick="scrollTo('#contact')">
                    <i class="fas fa-envelope"></i> Get In Touch
                </a>
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="section fade-in">
        <h2><i class="fas fa-briefcase"></i> Professional Experience</h2>
        
        <div class="experience-grid">
            <!-- EY Consulting Experience -->
            <div class="experience-card">
                <div class="experience-header">
                    <div class="company-icon">
                        <i class="fas fa-chart-line"></i>
                    </div>
                    <div class="experience-title">
                        <h3>Summer Intern, Business Consulting</h3>
                        <div class="company">EY India</div>
                        <div class="duration">April 2025 - May 2025</div>
                    </div>
                </div>
                <ul class="achievement-list">
                    <li>Evaluated <strong>8+ Tier-2 Indian cities</strong> for tech client's GCC setup, assessing IT & consulting talent</li>
                    <li>Benchmarked <strong>~20-30% cost savings</strong> vs. Tier-1 hubs through comprehensive cost-benefit analysis</li>
                    <li>Conducted gap analysis of <strong>15+ finance processes</strong> for pharma client, identifying key inefficiencies</li>
                    <li>Designed standardized workflows projected to <strong>reduce manual effort by ~25%</strong></li>
                    <li>Authored <strong>3 SOPs and RACI matrix</strong> across 2 functions, strengthening compliance</li>
                </ul>
            </div>

            <!-- EY Talent Acquisition Experience -->
            <div class="experience-card">
                <div class="experience-header">
                    <div class="company-icon">
                        <i class="fas fa-users"></i>
                    </div>
                    <div class="experience-title">
                        <h3>Senior Associate, Talent Acquisition</h3>
                        <div class="company">EY India</div>
                        <div class="duration">June 2021 - May 2024</div>
                    </div>
                </div>
                <ul class="achievement-list">
                    <li>Awarded <strong>"Business Extraordinaire"</strong> for delivering high-quality work in 300+ member team</li>
                    <li>Launched EY India's <strong>first global campus recruitment</strong> campaign, boosting applications by <strong>30%</strong></li>
                    <li>Led premier B-school hiring, onboarding <strong>200+ hires and 100+ interns</strong></li>
                    <li>Increased annual new hires from 1,200 to 1,400 (<strong>~17% YoY growth</strong>)</li>
                    <li>Achieved <strong>~80%+ application share</strong> from top MBA batches post-merger</li>
                    <li>Organized case competitions for <strong>12 colleges</strong> attracting <strong>9000+ participants</strong></li>
                </ul>
            </div>

            <!-- Venture Capital Experience -->
            <div class="experience-card">
                <div class="experience-header">
                    <div class="company-icon">
                        <i class="fas fa-rocket"></i>
                    </div>
                    <div class="experience-title">
                        <h3>Investment Intern</h3>
                        <div class="company">UNLEASH Capital Partners</div>
                        <div class="duration">July 2025 - August 2025</div>
                    </div>
                </div>
                <ul class="achievement-list">
                    <li>Managed pipeline of <strong>20+ early-stage deals</strong> with data-backed outreach strategies</li>
                    <li>Organized <strong>10+ founder meetings</strong>, gaining exposure to fundraising and investor Q&A</li>
                    <li>Sourced & evaluated <strong>100+ fintech, NBFC, and infra-tech startups</strong> aligned with fund thesis</li>
                    <li>Reached out to <strong>20+ fintech & BFSI startups valued <$8M</strong></li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="section fade-in">
        <h2><i class="fas fa-cogs"></i> Core Competencies</h2>
        
        <div class="skills-grid">
            <div class="skill-category">
                <div class="skill-icon">
                    <i class="fas fa-chart-bar"></i>
                </div>
                <h3>Business Consulting</h3>
                <p>Strategic analysis, process optimization, and organizational transformation</p>
                <div class="skill-tags">
                    <span class="skill-tag">Gap Analysis</span>
                    <span class="skill-tag">Process Design</span>
                    <span class="skill-tag">Cost-Benefit Analysis</span>
                </div>
            </div>

            <div class="skill-category">
                <div class="skill-icon">
                    <i class="fas fa-handshake"></i>
                </div>
                <h3>Talent Management</h3>
                <p>Campus recruitment, employer branding, and workforce planning</p>
                <div class="skill-tags">
                    <span class="skill-tag">Campus Hiring</span>
                    <span class="skill-tag">Employer Branding</span>
                    <span class="skill-tag">Data Analytics</span>
                </div>
            </div>

            <div class="skill-category">
                <div class="skill-icon">
                    <i class="fas fa-seedling"></i>
                </div>
                <h3>Venture Capital</h3>
                <p>Startup evaluation, due diligence, and investment analysis</p>
                <div class="skill-tags">
                    <span class="skill-tag">Deal Sourcing</span>
                    <span class="skill-tag">Due Diligence</span>
                    <span class="skill-tag">Financial Analysis</span>
                </div>
            </div>

            <div class="skill-category">
                <div class="skill-icon">
                    <i class="fas fa-laptop-code"></i>
                </div>
                <h3>Technical Skills</h3>
                <p>Data visualization and HR technology platforms</p>
                <div class="skill-tags">
                    <span class="skill-tag">Power BI</span>
                    <span class="skill-tag">Tableau</span>
                    <span class="skill-tag">SuccessFactors</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Education Section -->
    <section id="education" class="section fade-in">
        <h2><i class="fas fa-graduation-cap"></i> Education</h2>
        
        <div class="education-timeline">
            <div class="education-item">
                <h3>MBA - BITS School of Management (BITSoM), Mumbai</h3>
                <p><strong>Expected:</strong> 2026</p>
                <p>Placement Committee Member | Book Club Member | Student Secretary</p>
            </div>

            <div class="education-item">
                <h3>B.Com - R. A. Podar College of Commerce & Economics</h3>
                <p><strong>CGPA:</strong> 8.16 | <strong>Year:</strong> 2021</p>
                <p>Strong foundation in commerce and economics</p>
            </div>

            <div class="education-item">
                <h3>Higher Secondary - D.A.V. International School</h3>
                <p><strong>Percentage:</strong> 88% | <strong>Year:</strong> 2018</p>
                <p>Excellence in academics with strong analytical foundation</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section fade-in">
        <h2><i class="fas fa-envelope"></i> Let's Connect</h2>
        
        <div class="contact-grid">
            <div class="contact-item">
                <div class="contact-icon">
                    <i class="fab fa-linkedin"></i>
                </div>
                <h3>LinkedIn</h3>
                <p>Professional networking and career updates</p>
            </div>

            <div class="contact-item">
                <div class="contact-icon">
                    <i class="fas fa-envelope"></i>
                </div>
                <h3>Email</h3>
                <p>For business inquiries and opportunities</p>
            </div>

            <div class="contact-item">
                <div class="contact-icon">
                    <i class="fab fa-github"></i>
                </div>
                <h3>GitHub</h3>
                <p>Projects and technical contributions</p>
            </div>

            <div class="contact-item">
                <div class="contact-icon">
                    <i class="fas fa-phone"></i>
                </div>
                <h3>Phone</h3>
                <p>Direct contact for urgent matters</p>
            </div>
        </div>
    </section>

    <script>
        // Smooth scrolling function
        function scrollTo(target) {
            document.querySelector(target).scrollIntoView({
                behavior: 'smooth'
            });
        }

        // Navbar visibility on scroll
        window.addEventListener('scroll', function() {
            const navbar = document.getElementById('navbar');
            if (window.scrollY > 100) {
                navbar.classList.add('visible');
            } else {
                navbar.classList.remove('visible');
            }
        });

        // Fade in animation on scroll
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver(function(entries) {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, observerOptions);

        // Observe all fade-in elements
        document.querySelectorAll('.fade-in').forEach(el => {
            observer.observe(el);
        });

        // Add hover effects to experience cards
        document.querySelectorAll('.experience-card').forEach(card => {
            card.addEventListener('mouseenter', function() {
                this.style.transform = 'translateY(-10px) scale(1.02)';
            });
            
            card.addEventListener('mouseleave', function() {
                this.style.transform = 'translateY(0) scale(1)';
            });
        });

        // Add click effects to buttons
        document.querySelectorAll('.btn').forEach(btn => {
            btn.addEventListener('click', function(e) {
                let ripple = document.createElement('span');
                ripple.style.position = 'absolute';
                ripple.style.borderRadius = '50%';
                ripple.style.background = 'rgba(255,255,255,0.6)';
                ripple.style.transform = 'scale(0)';
                ripple.style.animation = 'ripple 0.6s linear';
                ripple.style.left = (e.clientX - e.target.offsetLeft) + 'px';
                ripple.style.top = (e.clientY - e.target.offsetTop) + 'px';
                
                this.appendChild(ripple);
                
                setTimeout(() => {
                    ripple.remove();
                }, 600);
            });
        });

        // Add CSS for ripple effect
        const style = document.createElement('style');
        style.textContent = `
            @keyframes ripple {
                to {
                    transform: scale(4);
                    opacity: 0;
                }
            }
        `;
        document.head.appendChild(style);
    </script>
</body>
</html>
