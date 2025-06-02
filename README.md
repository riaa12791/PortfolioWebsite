# PortfolioWebsite
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>YourName - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">YourName</div>
            <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><button id="theme-toggle" aria-label="Toggle theme"><i class="fas fa-moon"></i></button></li>
            </ul>
        </nav>
    </header>

    <section id="hero">
        <div class="hero-content">
            <h1>Hi, I'm YourName</h1>
            <p>A passionate developer building projects to solve real-world problems.</p>
            <a href="#projects" class="btn">View My Work</a>
        </div>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>I'm a self-taught developer with a focus on Python and web development. I enjoy creating tools like finance trackers and to-do lists to make life easier. My goal is to build impactful projects and grow as a software engineer.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project-grid">
            <div class="project-card">
                <h3>Personal Finance Tracker</h3>
                <p>A Python CLI application to track income, expenses, and generate financial reports with JSON storage.</p>
                <a href="https://github.com/YourUsername/FinanceTracker" target="_blank" class="btn">View on GitHub</a>
            </div>
            <div class="project-card">
                <h3>To-Do List App</h3>
                <p>A simple task management app to organize daily activities, built with [Your Tech Stack].</p>
                <a href="https://github.com/YourUsername/ToDoList" target="_blank" class="btn">View on GitHub</a>
            </div>
        </div>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul class="skills-list">
            <li>Python</li>
            <li>HTML/CSS</li>
            <li>JavaScript</li>
            <li>Git/GitHub</li>
            <li>Problem-Solving</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Reach out to me via email or connect on LinkedIn!</p>
        <div class="contact-links">
            <a href="mailto:your.email@example.com" class="btn"><i class="fas fa-envelope"></i> Email</a>
            <a href="https://www.linkedin.com/in/yourprofile" target="_blank" class="btn"><i class="fab fa-linkedin"></i> LinkedIn</a>
            <a href="https://github.com/YourUsername" target="_blank" class="btn"><i class="fab fa-github"></i> GitHub</a>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 YourName. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
