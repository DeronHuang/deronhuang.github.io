<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your GitHub Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 2rem;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        header p {
            margin: 0.5rem 0;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 2rem 0;
        }
        .about, .projects {
            background: #fff;
            padding: 2rem;
            margin-bottom: 2rem;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .projects h2 {
            text-align: center;
        }
        .project-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
        }
        .project-card {
            background: #f9f9f9;
            padding: 1rem;
            border-radius: 5px;
            text-align: center;
        }
        .project-card h3 {
            margin: 0 0 0.5rem;
        }
        .project-card a {
            color: #333;
            text-decoration: none;
            font-weight: bold;
        }
        .project-card a:hover {
            color: #007bff;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        @media (max-width: 600px) {
            .container {
                width: 90%;
            }
            header h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Your Name</h1>
        <p>Developer | Creator | Problem Solver</p>
        <p><a href="https://github.com/yourusername" style="color: #fff;">GitHub Profile</a></p>
    </header>

    <div class="container">
        <section class="about">
            <h2>About Me</h2>
            <p>Hello! I'm a passionate developer with experience in building web applications and solving complex problems. I love contributing to open-source projects and learning new technologies.</p>
        </section>

        <section class="projects">
            <h2>My Projects</h2>
            <div class="project-grid">
                <div class="project-card">
                    <h3>Project One</h3>
                    <p>A cool web app built with HTML, CSS, and JavaScript.</p>
                    <p><a href="https://github.com/yourusername/project-one">View on GitHub</a></p>
                </div>
                <div class="project-card">
                    <h3>Project Two</h3>
                    <p>A Python script for automating tasks.</p>
                    <p><a href="https://github.com/yourusername/project-two">View on GitHub</a></p>
                </div>
                <div class="project-card">
                    <h3>Project Three</h3>
                    <p>A machine learning model for data analysis.</p>
                    <p><a href="https://github.com/yourusername/project-three">View on GitHub</a></p>
                </div>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Your Name. All Rights Reserved.</p>
        <p>Contact: <a href="mailto:your.email@example.com" style="color: #fff;">your.email@example.com</a></p>
    </footer>
</body>
</html>
