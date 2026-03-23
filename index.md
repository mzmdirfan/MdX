<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mohamed Irfan | Portfolio</title>

  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: #0f172a;
      color: #fff;
    }

    header {
      padding: 20px 10%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: #020617;
      position: sticky;
      top: 0;
    }

    header h1 {
      color: #38bdf8;
    }

    nav a {
      color: white;
      margin-left: 20px;
      text-decoration: none;
      transition: 0.3s;
    }

    nav a:hover {
      color: #38bdf8;
    }

    .hero {
      height: 90vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 0 10%;
    }

    .hero h2 {
      font-size: 2.5rem;
    }

    .hero span {
      color: #38bdf8;
    }

    section {
      padding: 60px 10%;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: #1e293b;
      padding: 20px;
      border-radius: 10px;
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-10px);
    }

    .btn {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 15px;
      background: #38bdf8;
      color: black;
      text-decoration: none;
      border-radius: 5px;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #020617;
    }
  </style>
</head>

<body>

<header>
  <h1>Irfan</h1>
  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero">
  <div>
    <h2>Hi, I'm <span>Mohamed Irfan</span></h2>
    <p>Engineer | Networking | Tech Enthusiast</p>
  </div>
</section>

<section id="about">
  <h2>About Me</h2>
  <p>
    I'm an engineer passionate about networking, servers, and technology.
    I enjoy building projects and learning new skills.
  </p>
</section>

<section id="projects">
  <h2>Projects</h2>
  <div class="projects">

    <div class="card">
      <h3>Networking Lab</h3>
      <p>Hands-on networking practice using FortiSwitch and VM servers.</p>
      <a href="#" class="btn">View</a>
    </div>

    <div class="card">
      <h3>RTL to GDSII</h3>
      <p>OpenLane PicoRV32a chip design project.</p>
      <a href="#" class="btn">View</a>
    </div>

    <div class="card">
      <h3>Blog Website</h3>
      <p>Personal blog project.</p>
      <a href="#" class="btn">View</a>
    </div>

  </div>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>Email: yourmail@example.com</p>
</section>

<footer>
  <p>© 2026 Mohamed Irfan</p>
</footer>

</body>
</html>
