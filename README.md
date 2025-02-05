<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dihya Developora</title>
  <style>
    /* General Styles */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #6a11cb, #2575fc);
      color: white;
      padding: 2rem 0;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
      animation: fadeIn 2s ease-in-out;
    }

    header p {
      font-size: 1.2rem;
      margin: 0.5rem 0 0;
    }

    nav {
      display: flex;
      justify-content: center;
      background: #333;
      padding: 0.5rem 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 1rem;
      font-size: 1rem;
    }

    nav a:hover {
      color: #2575fc;
    }

    section {
      padding: 2rem;
      max-width: 800px;
      margin: 0 auto;
    }

    h2 {
      color: #2575fc;
      border-bottom: 2px solid #2575fc;
      display: inline-block;
      margin-bottom: 1rem;
    }

    .project-card {
      background: white;
      padding: 1rem;
      margin: 1rem 0;
      border-radius: 8px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    .project-card h3 {
      margin: 0 0 0.5rem;
    }

    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 1rem 0;
      margin-top: 2rem;
    }

    footer a {
      color: #2575fc;
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }

    /* Animations */
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
  </style>
</head>
<body>

  <!-- Header Section -->
  <header>
    <h1>Dihya Developora</h1>
    <p>Bridging Code and Philosophy to Build a Better Future</p>
  </header>

  <!-- Navigation -->
  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#philosophy">Philosophy</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>
      Hello! I’m [Your Name], a developer inspired by the resilience and wisdom of Dihya (Kahina), the legendary Berber queen and strategist. I specialize in [your skills, e.g., web development, AI, or mobile apps], and I believe in creating technology that is both innovative and meaningful.
    </p>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h2>Projects</h2>
    <div class="project-card">
      <h3>EcoTracker App</h3>
      <p>A mobile app that helps users track their carbon footprint and suggests eco-friendly habits.</p>
      <p><strong>Tech Stack:</strong> React Native, Firebase, Node.js</p>
      <p><a href="#" target="_blank">Live Demo</a> | <a href="#" target="_blank">GitHub Repo</a></p>
    </div>
    <div class="project-card">
      <h3>Portfolio Website</h3>
      <p>A responsive and minimalist portfolio website to showcase my work and philosophy.</p>
      <p><strong>Tech Stack:</strong> HTML, CSS, JavaScript</p>
      <p><a href="#" target="_blank">Live Demo</a> | <a href="#" target="_blank">GitHub Repo</a></p>
    </div>
  </section>

  <!-- Philosophy Section -->
  <section id="philosophy">
    <h2>Philosophy</h2>
    <p>
      I believe that technology should serve humanity, not the other way around. Drawing inspiration from Dihya’s leadership and philosophical principles, I strive to create solutions that are ethical, inclusive, and impactful. As Aristotle said, <em>"The whole is greater than the sum of its parts,"</em> and I apply this idea to collaborative and systems thinking in my work.
    </p>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact</h2>
    <p>Let’s connect and build something amazing together!</p>
    <p>
      <strong>Email:</strong> <a href="mailto:your.email@example.com">your.email@example.com</a><br>
      <strong>LinkedIn:</strong> <a href="https://linkedin.com/in/yourprofile" target="_blank">linkedin.com/in/yourprofile</a><br>
      <strong>GitHub:</strong> <a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a>
    </p>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2023 Dihya Developora. All rights reserved.</p>
  </footer>

</body>
</html>
