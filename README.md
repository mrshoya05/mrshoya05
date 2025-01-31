<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shoyab Khan's Profile</title>
  <!-- External Libraries for Styling -->
  <link href="https://fonts.googleapis.com/css2?family=Orbitron&family=Press+Start+2P&display=swap" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css" />

  <style>
    body {
      font-family: 'Orbitron', sans-serif;
      background-color: #1a1a1a;
      color: #00FF00;
      margin: 0;
      padding: 0;
      overflow-x: hidden;
    }

    h1, h3, p {
      text-align: center;
      text-shadow: 0 0 10px #00FF00, 0 0 20px #00FF00;
    }

    h1 {
      font-size: 3em;
      margin-top: 20px;
    }

    h3 {
      font-size: 2em;
      margin-top: 10px;
    }

    .typing {
      font-size: 1.5em;
      color: #00FFFF;
      animation: typing 3s steps(30) 1s forwards, blink .75s step-end infinite;
    }

    @keyframes typing {
      from {
        width: 0;
      }
      to {
        width: 100%;
      }
    }

    @keyframes blink {
      50% {
        border-color: transparent;
      }
    }

    /* Glowing Neon Effect for Buttons and Icons */
    .glow-on-hover {
      width: 200px;
      height: 50px;
      border-radius: 10px;
      background: black;
      border: 2px solid #00FF00;
      color: #00FF00;
      font-size: 20px;
      font-family: 'Press Start 2P', cursive;
      position: relative;
      cursor: pointer;
      overflow: hidden;
      box-shadow: 0 0 10px #00FF00, 0 0 20px #00FF00;
      transition: all 0.3s ease;
    }

    .glow-on-hover:hover {
      background-color: #00FF00;
      color: black;
      box-shadow: 0 0 20px #00FF00, 0 0 40px #00FF00;
    }

    .container {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      flex-direction: column;
    }

    .icon {
      font-size: 30px;
      margin: 10px;
      transition: transform 0.2s;
    }

    .icon:hover {
      transform: scale(1.2);
      color: #00FFFF;
    }

    /* Skill cards */
    .card {
      width: 200px;
      margin: 20px;
      padding: 20px;
      background: #2a2a2a;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 0 15px rgba(0, 255, 255, 0.6);
    }

    .card img {
      width: 50px;
      height: 50px;
      margin-bottom: 15px;
    }

    /* Footer */
    footer {
      position: absolute;
      bottom: 0;
      width: 100%;
      padding: 10px;
      text-align: center;
      background-color: #1a1a1a;
      color: #00FF00;
    }

  </style>
</head>
<body>
  <div class="container">
    <h1 class="animate__animated animate__fadeInDown">Hi, I'm Shoyab Khan</h1>
    <h3 class="typing">Fullstack Developer | JavaScript Enthusiast</h3>
    <p>I'm passionate about building cool projects with the latest tech!</p>

    <button class="glow-on-hover">Contact Me</button>

    <div class="skills">
      <h3>Skills</h3>
      <div class="card">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript">
        <p>JavaScript</p>
      </div>
      <div class="card">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React">
        <p>React</p>
      </div>
      <div class="card">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js">
        <p>Node.js</p>
      </div>
    </div>

    <footer>
      <p>&copy; 2025 Shoyab Khan | All Rights Reserved</p>
    </footer>
  </div>

  <!-- External Scripts -->
  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/particles.js"></script>
  
  <script>
    // Particles.js to create a cool background effect
    particlesJS("particles-js", {
      "particles": {
        "number": {
          "value": 50
        },
        "color": {
          "value": "#00FF00"
        },
        "shape": {
          "type": "circle"
        },
        "size": {
          "value": 3
        },
        "move": {
          "speed": 1,
          "direction": "none",
          "out_mode": "out"
        }
      }
    });
  </script>
</body>
</html>
