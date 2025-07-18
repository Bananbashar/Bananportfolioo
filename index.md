<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Banan Al-Jarrah</title>
  <link rel="stylesheet" href="assets/css/style.css">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', sans-serif;
      background: url('assets/images/6.jpg') no-repeat center center fixed;
      background-size: cover;
      height: 100vh;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      position: relative;
      overflow: hidden;
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
      animation: fadeIn 1.5s ease-in;
    }

    h1 {
      font-size: 2.8rem;
      margin-bottom: 2rem;
      text-shadow: 1px 1px 5px rgba(0,0,0,0.5);
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

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(10px); }
      to   { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <div class="overlay"></div>
  <div class="content">
    <h1>Welcome! Let’s Explore Together</h1>
    <div class="buttons">
      <a href="about.html">About Me</a>
      <a href="work.html">Work</a>
      <a href="projects.html">Projects</a>
      <a href="contact.html">Contact Me</a>
    </div>
  </div>
</body>
</html>
