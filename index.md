
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Banan Al-Jarrah</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', sans-serif;
      background: url('A_website_homepage_of_Banan_Al-Jarrah,_a_Clinical_.png') no-repeat center center fixed;
      background-size: cover;
      height: 100vh;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .overlay {
      background-color: rgba(0, 0, 0, 0.6);
      position: absolute;
      width: 100%;
      height: 100%;
      z-index: 0;
    }

    .content {
      position: relative;
      z-index: 1;
      text-align: center;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 1.5rem;
    }

    .buttons {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      justify-content: center;
    }

    .buttons a {
      text-decoration: none;
      color: white;
      background-color: rgba(255, 255, 255, 0.2);
      border: 1px solid white;
      padding: 1rem 2rem;
      border-radius: 30px;
      font-weight: 500;
      transition: all 0.3s ease;
    }

    .buttons a:hover {
      background-color: white;
      color: #000;
    }
  </style>
</head>
<body>
  <div class="overlay"></div>
  <div class="content">
    <h1>Banan Al-Jarrah</h1>
    <div class="buttons">
      <a href="about.html">About Me</a>
      <a href="work.html">Work</a>
      <a href="projects.html">Projects</a>
      <a href="contact.html">Contact Me</a>
    </div>
  </div>
</body>
</html>
