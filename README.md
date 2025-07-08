<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Jerard Avila | Developer & Creator</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body { margin:0; padding:0; font-family: Arial, sans-serif; background: #eaf2fb; color: #333; }
    .container { max-width: 1000px; margin: auto; padding: 40px 20px; }
    header { text-align: center; padding: 60px 0; }
    header h1 { margin:0; font-size: 3rem; color:#1e1e1e; }
    header p { font-size:1.2rem; color:#555; }
    nav a { margin:0 15px; color:#00aa77; text-decoration:none; font-weight:bold; }
    .portfolio { margin-top:60px; }
    .portfolio h2 { text-align:center; font-size:2rem; color:#1e1e1e; margin-bottom:30px; }
    .grid { display:grid; grid-template-columns: repeat(auto-fit, minmax(280px,1fr)); gap:20px; }
    .card { background:#fff; border-radius:8px; box-shadow:0 2px 8px rgba(0,0,0,0.1); overflow:hidden;}
    .card img { width:100%; height:180px; object-fit:cover; }
    .card-content { padding:15px; }
    .card-content h3 { margin:0 0 10px; font-size:1.2rem; }
    .card-content p { margin:0 0 15px; color:#666; font-size:0.95rem; }
    .card-content a { color:#00aa77; font-weight:bold; text-decoration:none; }
    footer { text-align:center; padding:50px 0 20px; color:#888; font-size:0.85rem; }
    @media(max-width:600px){ header h1{font-size:2.2rem;} }
  </style>
</head>
<body>

  <div class="container">

    <header>
      <h1>Jerard Avila</h1>
      <p>Full‑Stack Developer &amp; Digital Creator</p>
      <nav>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <section id="portfolio" class="portfolio">
      <h2>My Work</h2>
      <div class="grid">

        <div class="card">
          <img src="https://via.placeholder.com/400x180?text=Project+1" alt="Project 1">
          <div class="card-content">
            <h3>Project One</h3>
            <p>A responsive web app built with React and Node.js for managing tasks efficiently.</p>
            <a href="#">View details →</a>
          </div>
        </div>

        <div class="card">
          <img src="https://via.placeholder.com/400x180?text=Project+2" alt="Project 2">
          <div class="card-content">
            <h3>My Portfolio Site</h3>
            <p>A personal site with dynamic content, showcasing skills and past projects, built with HTML, CSS &amp; JavaScript.</p>
            <a href="#">View details →</a>
          </div>
        </div>

        <div class="card">
          <img src="https://via.placeholder.com/400x180?text=Project+3" alt="Project 3">
          <div class="card-content">
            <h3>Budget Planner App</h3>
            <p>An Android app that helps track income and expenses, built using Java.</p>
            <a href="#">View details →</a>
          </div>
        </div>

        <!-- Add more project cards as needed -->

      </div>
    </section>

    <section id="contact" style="margin-top:60px; text-align:center;">
      <h2>Get In Touch</h2>
      <p>I'm always open to exciting projects and collaborations—</p>
      <p><a href="mailto:your-email@example.com" style="color:#00aa77; font-weight:bold;">your-email@example.com</a></p>
    </section>

    <footer>
      &copy; 2025 Jerard Avila. Powered by passion and code.
    </footer>

  </div>

</body>
</html>
