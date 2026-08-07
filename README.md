# portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Karan Kumar - Portfolio</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
        body { background-color: #f8f9fa; color: #333; line-height: 1.6; }
        header { background: #1f2937; color: white; padding: 50px 20px; text-align: center; }
        header h1 { font-size: 2.5rem; margin-bottom: 10px; }
        header p { font-size: 1.1rem; color: #9ca3af; }
        .contact-links { margin-top: 15px; }
        .contact-links a { color: #38bdf8; text-decoration: none; margin: 0 10px; font-weight: bold; }
        .container { max-width: 900px; margin: 30px auto; padding: 0 20px; }
        section { background: white; padding: 25px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05); }
        h2 { color: #1f2937; border-bottom: 2px solid #38bdf8; padding-bottom: 5px; margin-bottom: 15px; }
        .skills-grid { display: flex; flex-wrap: wrap; gap: 10px; }
        .skill-tag { background: #e0f2fe; color: #0369a1; padding: 6px 12px; border-radius: 20px; font-weight: 500; font-size: 0.9rem; }
        .project-card { margin-bottom: 20px; border-left: 4px solid #38bdf8; padding-left: 15px; }
        .project-card h3 { color: #111827; }
        .tech-stack { font-size: 0.85rem; color: #6b7280; font-weight: bold; margin-bottom: 5px; }
        footer { text-align: center; padding: 20px; color: #6b7280; font-size: 0.9rem; }
    </style>
</head>
<body>

    <header>
        <h1>Karan Kumar</h1>
        <p>Aspiring Software Developer | Computer Science Student</p>
        <div class="contact-links">
            <a href="mailto:karansin1163@gmail.com">Email</a> |
            <a href="tel:+918534873918">Call</a> |
            <a href="http://www.linkedin.com/in/karan-kumar-a161112a6" target="_blank">LinkedIn</a>
        </div>
    </header>

    <div class="container">
        <section>
            <h2>About Me</h2>
            <p>Final-year B.Tech Computer Science student with strong foundations in Java, Python, C++, Data Structures, DBMS, and Computer Networks. Experienced in building academic projects and passionate about entry-level Software Developer opportunities.</p>
        </section>

        <section>
            <h2>Technical Skills</h2>
            <div class="skills-grid">
                <span class="skill-tag">Java</span>
                <span class="skill-tag">Python</span>
                <span class="skill-tag">C / C++</span>
                <span class="skill-tag">DSA</span>
                <span class="skill-tag">DBMS & MySQL</span>
                <span class="skill-tag">HTML5 & CSS3</span>
                <span class="skill-tag">Git & GitHub</span>
                <span class="skill-tag">Generative AI</span>
            </div>
        </section>

        <section>
            <h2>Featured Projects</h2>
            <div class="project-card">
                <h3>Student Management System</h3>
                <p class="tech-stack">Tech Stack: Java, MySQL, JDBC</p>
                <p>Designed a desktop application to manage student data, enrollments, and academic records efficiently with CRUD operations.</p>
            </div>
            <div class="project-card">
                <h3>AI Task Assistant</h3>
                <p class="tech-stack">Tech Stack: Python, Microsoft Generative AI, REST APIs</p>
                <p>Created an automated assistant tool capable of processing user queries and executing automated tasks.</p>
            </div>
        </section>

        <section>
            <h2>Certifications</h2>
            <ul>
                <li><strong>Microsoft:</strong> Generative AI & Agents</li>
                <li><strong>Grant Thornton:</strong> Cyber Security</li>
                <li><strong>NPTEL:</strong> Software Engineering</li>
                <li><strong>Coursera:</strong> Python Programming</li>
            </ul>
        </section>
    </div>

    <footer>
        <p>© Karan Kumar. All rights reserved.</p>
    </footer>

</body>
</html>
