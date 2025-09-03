# username.github.io<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">

  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background: #f4f6f9;
      color: #333;
      margin: 0;
      padding: 0;
    }

    /* Navigation */
    nav {
      background: #222;
      padding: 15px 20px;
      text-align: center;
      position: sticky;
      top: 0;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: 600;
    }
    nav a:hover {
      color: #4da6ff;
    }

    /* Header */
    header {
      background: #222;
      color: white;
      padding: 80px 20px;
      text-align: center;
    }
    header h1 {
      margin-bottom: 10px;
      font-size: 2.5rem;
    }

    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      text-align: center;
      margin-bottom: 30px;
      color: #222;
    }

    /* Projects Grid */
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }

    .card {
      background: white;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      padding: 20px;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }
    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 12px rgba(0,0,0,0.15);
    }
    .card img {
      border-radius: 10px;
      margin-bottom: 15px;
      width: 100%;
      height: auto;
    }
    .card h3 {
      margin: 10px 0;
    }
    .card a {
      display: inline-block;
      margin-right: 10px;
      color: #4da6ff;
      text-decoration: none;
      font-weight: 600;
    }
    .card a:hover {
      text-decoration: underline;
    }

    /* Footer */
    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
    footer a {
      color: #4da6ff;
      text-decoration: none;
    }
    footer a:hover {
      text-decoration: underline;
    }

    /* Mobile */
    @media (max-width: 600px) {
      header {
        padding: 50px 15px;
      }
      nav a {
        display: inline-block;
        margin: 10px;
      }
    }
  </style>
</head>
<body>

  <!-- Navigation -->
  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- Hero -->
  <header>
    <h1>Hi, I’m [Your Name]</h1>
    <p>Welcome to my portfolio! I’m a [Your Role/Profession]</p>
  </header>

  <!-- About -->
  <section id="about">
    <h2>About Me</h2>
    <p>
      I am a [Your Profession] passionate about [your interests/skills]. 
      This portfolio highlights some of my work and projects.
    </p>
  </section>

  <!-- Projects -->
  <section id="projects">
    <h2>Featured Projects</h2>
    <div class="projects">
      <div class="card">
        <img src="images/project1.png" alt="Project 1 screenshot">
        <h3>Weather App</h3>
        <p>A web app that shows live weather updates using an API.</p>
        <a href="https://github.com/username/weather-app" target="_blank">GitHub</a>
        <a href="https://username.github.io/weather-app" target="_blank">Live Demo</a>
      </div>

      <div class="card">
        <img src="images/project2.png" alt="Project 2 screenshot">
        <h3>Portfolio Website</h3>
        <p>My responsive portfolio built with HTML & CSS, hosted on GitHub Pages.</p>
        <a href="https://github.com/username/portfolio" target="_blank">GitHub</a>
        <a href="https://username.github.io/portfolio" target="_blank">Live Demo</a>
      </div>

      <div class="card">
        <img src="images/project3.png" alt="Project 3 screenshot">
        <h3>Task Manager</h3>
        <p>A task management tool with local storage to save tasks.</p>
        <a href="https://github.com/username/task-manager" target="_blank">GitHub</a>
        <a href="https://username.github.io/task-manager" target="_blank">Live Demo</a>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:your@email.com">your@email.com</a></p>
    <p>LinkedIn: <a href="https://linkedin.com/in/yourprofile" target="_blank">linkedin.com/in/yourprofile</a></p>
    <p>GitHub: <a href="https://github.com/username" target="_blank">github.com/username</a></p>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 [Your Name]. Built with ❤️ using GitHub Pages.</p>
  </footer>

</body>
</html>
