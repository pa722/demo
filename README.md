<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tanvi Patel | Developer Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=League+Spartan:wght@700&family=Montserrat:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        /* CSS STYLES */
        :root {
            --bg-color: #1A1A1A;
            --card-bg: #252525;
            --accent-color: #007BFF; /* Electric Blue */
            --text-main: #FFFFFF;
            --text-dim: #B0B0B0;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-main);
            font-family: 'Montserrat', sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        h1, h2, h3 { font-family: 'League Spartan', sans-serif; text-transform: uppercase; }

        .container { max-width: 1000px; margin: 0 auto; padding: 40px 20px; }

        /* HERO SECTION */
        header {
            text-align: center;
            padding: 100px 20px;
            background: linear-gradient(180deg, #1A1A1A 0%, #252525 100%);
        }

        header h1 { font-size: 4rem; margin: 0; letter-spacing: 2px; }
        header p { font-size: 1.2rem; color: var(--accent-color); font-weight: 600; margin-top: 10px; }
        .intro-text { max-width: 600px; margin: 20px auto; color: var(--text-dim); }

        .btn {
            background-color: var(--accent-color);
            color: white;
            padding: 12px 30px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            margin-top: 20px;
            transition: transform 0.3s;
        }
        .btn:hover { transform: translateY(-3px); }

        /* SKILLS SECTION */
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 50px;
        }

        .skill-card {
            background: var(--card-bg);
            padding: 25px;
            border-radius: 10px;
            border-left: 4px solid var(--accent-color);
        }

        /* PROJECTS SECTION */
        .project-card {
            background: var(--card-bg);
            margin-top: 30px;
            border-radius: 10px;
            overflow: hidden;
            display: flex;
            flex-wrap: wrap;
        }

        .project-info { padding: 30px; flex: 1; }
        .project-tag { color: var(--accent-color); font-size: 0.8rem; font-weight: bold; }

        /* CONTACT */
        footer { text-align: center; padding: 60px 20px; background: #111; border-top: 1px solid #333; }
        .contact-links a { color: var(--text-main); margin: 0 15px; text-decoration: none; border-bottom: 1px solid var(--accent-color); }

        /* MOBILE RESPONSIVE */
        @media (max-width: 768px) {
            header h1 { font-size: 2.5rem; }
        }
    </style>
</head>
<body>

    <header>
        <h1>TANVI PATEL</h1>
        <p>Full-Stack Developer In-Training | BCA Student</p>
        <div class="intro-text">
            I build functional, database-driven web applications with a focus on clean code and user experience.
        </div>
        <a href="mailto:pth77141@gmail.com" class="btn">Hire Me</a>
    </header>

    <div class="container">
        
        <section>
            <h2>Core Competencies</h2>
            <div class="skills-grid">
                <div class="skill-card">
                    <h3>Frontend</h3>
                    <p>HTML5, CSS3, JavaScript, jQuery</p>
                </div>
                <div class="skill-card">
                    <h3>Backend</h3>
                    <p>PHP, Basic Python</p>
                </div>
                <div class="skill-card">
                    <h3>Database</h3>
                    <p>SQL (MySQL)</p>
                </div>
            </div>
        </section>

        <section style="margin-top: 80px;">
            <h2>Featured Projects</h2>
            <div class="project-card">
                <div class="project-info">
                    <span class="project-tag">PHP • SQL • HTML/CSS</span>
                    <h3>Student Database Management System</h3>
                    <p>Developed a secure backend using PHP to manage student records with a MySQL database, focusing on CRUD operations and data validation.</p>
                    <a href="#" class="btn" style="padding: 8px 20px; font-size: 0.9rem;">View Code</a>
                </div>
            </div>
        </section>

    </div>

    <footer>
        <h2>Let's Connect</h2>
        <p>Currently looking for internship opportunities in Ahmedabad.</p>
        <p>📞 +91 70167 77141</p>
        <div class="contact-links">
            <a href="mailto:pth77141@gmail.com">Email Me</a>
            
        </div>
        <p style="font-size: 0.8rem; color: #555; margin-top: 40px;">© 2026 Tanvi Patel. C-17/202 Shreenath App., Ahmedabad.</p>
    </footer>

    <script>
        // Smooth scroll effect or interactive elements can go here
        console.log("Tanvi Patel's Portfolio Loaded Successfully");
    </script>
</body>
</html>
