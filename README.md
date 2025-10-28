<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile Template</title>
    <style>
        :root {
            --primary-color: #2d3748;
            --accent-color: #4299e1;
            --highlight-color: #68d391;
            --text-color: #4a5568;
            --bg-color: #f7fafc;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--bg-color);
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }
        
        .header {
            text-align: center;
            margin-bottom: 40px;
            padding-bottom: 20px;
            border-bottom: 2px solid var(--accent-color);
        }
        
        .name {
            color: var(--primary-color);
            margin-bottom: 5px;
        }
        
        .tagline {
            font-size: 1.2rem;
            color: var(--accent-color);
            margin-bottom: 15px;
        }
        
        .section {
            margin-bottom: 40px;
            background: white;
            padding: 25px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        
        .section-title {
            color: var(--primary-color);
            border-bottom: 1px solid #e2e8f0;
            padding-bottom: 10px;
            margin-top: 0;
        }
        
        .highlight {
            color: var(--highlight-color);
            font-weight: bold;
        }
        
        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 15px;
            margin-top: 15px;
        }
        
        .tech-item {
            background: #edf2f7;
            padding: 10px 15px;
            border-radius: 5px;
            text-align: center;
        }
        
        .project {
            margin-bottom: 25px;
            padding-bottom: 20px;
            border-bottom: 1px solid #e2e8f0;
        }
        
        .project:last-child {
            border-bottom: none;
        }
        
        .project-title {
            color: var(--primary-color);
            margin-bottom: 5px;
        }
        
        .project-description {
            margin-bottom: 10px;
        }
        
        .project-tech {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-bottom: 10px;
        }
        
        .tech-tag {
            background: var(--accent-color);
            color: white;
            padding: 3px 10px;
            border-radius: 20px;
            font-size: 0.8rem;
        }
        
        .contact-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
        
        .contact-link {
            color: var(--accent-color);
            text-decoration: none;
            font-weight: bold;
        }
        
        .contact-link:hover {
            text-decoration: underline;
        }
        
        .quote {
            font-style: italic;
            text-align: center;
            margin: 30px 0;
            padding: 15px;
            background: #e6fffa;
            border-left: 4px solid var(--highlight-color);
        }
    </style>
</head>
<body>
    <div class="header">
        <h1 class="name">Your Name</h1>
        <p class="tagline">ALX Back-end Developer | Full-Stack & Microservices Enthusiast</p>
        <p>Building automated solutions that solve real-world problems</p>
    </div>

    <div class="section">
        <h2 class="section-title">👋 About Me</h2>
        <p>I'm a passionate <span class="highlight">ALX Back-end Software Engineering</span> learner with a strong focus on building robust, scalable systems. My journey into software engineering began with a fascination for how technology can automate complex processes and create efficient solutions.</p>
        
        <p>I'm particularly drawn to <span class="highlight">full-stack development</span> and <span class="highlight">microservices architecture</span> because I believe in building comprehensive services that work seamlessly together. My goal is to develop systems that not only function well but also automate workflows to save time and resources.</p>
        
        <div class="quote">
            "I don't just write code; I build solutions that automate work and create value."
        </div>
    </div>

    <div class="section">
        <h2 class="section-title">🛠️ Technologies & Skills</h2>
        <div class="tech-grid">
            <div class="tech-item">Python</div>
            <div class="tech-item">JavaScript</div>
            <div class="tech-item">Node.js</div>
            <div class="tech-item">Express.js</div>
            <div class="tech-item">Flask</div>
            <div class="tech-item">Django</div>
            <div class="tech-item">RESTful APIs</div>
            <div class="tech-item">MySQL</div>
            <div class="tech-item">MongoDB</div>
            <div class="tech-item">Docker</div>
            <div class="tech-item">Git & GitHub</div>
            <div class="tech-item">Linux/Unix</div>
            <div class="tech-item">Microservices</div>
            <div class="tech-item">API Design</div>
            <div class="tech-item">System Architecture</div>
        </div>
    </div>

    <div class="section">
        <h2 class="section-title">🚀 Featured Projects</h2>
        
        <div class="project">
            <h3 class="project-title">Microservices E-commerce Platform</h3>
            <p class="project-description">A full-stack e-commerce solution built with microservices architecture. Features separate services for user authentication, product catalog, shopping cart, and order processing, all communicating through REST APIs.</p>
            <div class="project-tech">
                <span class="tech-tag">Python</span>
                <span class="tech-tag">Flask</span>
                <span class="tech-tag">Docker</span>
                <span class="tech-tag">MySQL</span>
                <span class="tech-tag">REST API</span>
            </div>
            <a href="#" class="contact-link">View on GitHub →</a>
        </div>
        
        <div class="project">
            <h3 class="project-title">Task Automation System</h3>
            <p class="project-description">A backend system that automates repetitive tasks across different platforms. Implements scheduling, web scraping, and API integrations to streamline workflows and increase productivity.</p>
            <div class="project-tech">
                <span class="tech-tag">Node.js</span>
                <span class="tech-tag">Express</span>
                <span class="tech-tag">MongoDB</span>
                <span class="tech-tag">Redis</span>
                <span class="tech-tag">Cron Jobs</span>
            </div>
            <a href="#" class="contact-link">View on GitHub →</a>
        </div>
        
        <div class="project">
            <h3 class="project-title">API Gateway & Service Mesh</h3>
            <p class="project-description">A custom API gateway that routes requests to appropriate microservices with load balancing, rate limiting, and authentication. Demonstrates advanced back-end architecture patterns.</p>
            <div class="project-tech">
                <span class="tech-tag">Python</span>
                <span class="tech-tag">FastAPI</span>
                <span class="tech-tag">Docker</span>
                <span class="tech-tag">JWT</span>
                <span class="tech-tag">OAuth2</span>
            </div>
            <a href="#" class="contact-link">View on GitHub →</a>
        </div>
    </div>

    <div class="section">
        <h2 class="section-title">📈 GitHub Stats & Activity</h2>
        <p>Here's a snapshot of my coding activity and contributions:</p>
        <!-- You can add your GitHub stats using services like https://github.com/anuraghazra/github-readme-stats -->
        <div style="text-align: center; margin: 20px 0;">
            <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=default" alt="GitHub Stats" />
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=default" alt="Top Languages" />
        </div>
    </div>

    <div class="section">
        <h2 class="section-title">📫 Let's Connect</h2>
        <p>I'm always interested in connecting with fellow developers, discussing new projects, or exploring collaboration opportunities. Feel free to reach out!</p>
        
        <div class="contact-links">
            <a href="https://linkedin.com/in/yourprofile" class="contact-link">LinkedIn</a>
            <a href="https://twitter.com/yourprofile" class="contact-link">Twitter</a>
            <a href="mailto:your.email@example.com" class="contact-link">Email</a>
            <a href="https://yourportfolio.com" class="contact-link">Portfolio</a>
        </div>
    </div>

    <div class="section">
        <h2 class="section-title">🎯 Current Focus</h2>
        <ul>
            <li>Deepening my knowledge of <span class="highlight">microservices patterns</span> and distributed systems</li>
            <li>Exploring <span class="highlight">containerization</span> and orchestration with Docker and Kubernetes</li>
            <li>Building <span class="highlight">RESTful APIs</span> with best practices in security and performance</li>
            <li>Contributing to <span class="highlight">open-source projects</span> related to automation</li>
        </ul>
    </div>
</body>
</html>
