
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Junior Fall Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>
  <header class="header">
    <h1>Quantaeyah Berry</h1>
    <p>Thomas Edison CTE High School | Junior</p>
  </header>

  <section class="section">
    <h2>About Me</h2>
    <p>
      I am a junior at Thomas Edison CTE High School studying computer science.
      I am learning how to build websites using HTML and CSS and how to think
      like a programmer by solving problems and debugging code.
    </p>
  </section>

  <section class="section">
    <h2>Portfolio Purpose</h2>
    <p>
      This portfolio was created to showcase the projects I completed during
      my junior fall semester. It shows my progress as a programmer, what I
      learned from each project, and how my skills have improved over time.
    </p>
  </section>

  <nav class="nav">
    <a href="projects.html">View My Projects</a>
  </nav>

  <footer class="footer">
    <p>© 2026 Quantaeyah Berry</p>
  </footer>
</body>
</html> 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Projects</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>
  <header class="header">
    <h1>My Curated Projects</h1>
    <a href="index.html">← Back Home</a>
  </header>

  <!-- PROJECT 1 -->
  <section class="project">
    <div class="project-embed">
      <iframe src="https://editor.p5js.org/" title="Project One"></iframe>
    </div>

    <div class="project-reflection">
      <h2>Interactive Canvas Project</h2>
      <p>
        This project helped me learn how to create drawings using code.
        I learned how functions work and how small changes in code can
        affect the entire program. This project improved my confidence
        with debugging.
      </p>
    </div>
  </section>

  <!-- PROJECT 2 -->
  <section class="project">
    <div class="project-embed">
      <iframe src="https://editor.p5js.org/" title="Project Two"></iframe>
    </div>

    <div class="project-reflection">
      <h2>Website Design Project</h2>
      <p>
        In this project, I focused on using HTML and CSS together to create
        a structured webpage. I learned how to organize content, apply
        styling, and make layouts responsive so they work on different
        screen sizes.
      </p>
    </div>
  </section>

  <footer class="footer">
    <p>Junior Fall Portfolio</p>
  </footer>
</body>
</html>

 {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background-color: #f2f4f7;
  color: #333;
}

.header {
  background-color: #1f2933;
  color: white;
  padding: 25px;
  text-align: center;
}

.header a {
  color: #fbbf24;
  text-decoration: none;
}

.section {
  max-width: 900px;
  margin: 30px auto;
  padding: 20px;
  background: white;
  border-radius: 8px;
}

.nav {
  text-align: center;
  margin: 40px;
}

.nav a {
  padding: 12px 22px;
  background: #1f2933;
  color: white;
  text-decoration: none;
  border-radius: 6px;
}

.nav a:hover {
  background: #fbbf24;
  color: black;
}

.project {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  max-width: 1000px;
  margin: 40px auto;
  padding: 20px;
  background: white;
  border-radius: 8px;
}

.project-embed,
.project-reflection {
  flex: 1 1 400px;
}

.project-embed iframe {
  width: 100%;
  height: 300px;
  border: none;
}

.footer {
  text-align: center;
  padding: 20px;
  margin-top: 40px;
  background: #e5e7eb;
}
