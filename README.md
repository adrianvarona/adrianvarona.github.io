<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>My Name</h1>
    <nav>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Short bio here...</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Project 1</h3>
      <p>Description...</p>
      <a href="#">View Project</a>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: myemail@example.com</p>
  </section>

  <footer>
    <p>© 2025 My Name</p>
  </footer>
</body>
</html>

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 0;
}

header {
  background-color: #333;
  color: white;
  padding: 1rem;
  text-align: center;
}

header nav a {
  color: white;
  margin: 0 1rem;
  text-decoration: none;
}

section {
  padding: 2rem;
}

.project {
  border: 1px solid #ddd;
  padding: 1rem;
  margin: 1rem 0;
}
