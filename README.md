<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shoyab Khan's Profile</title>
  <style>
    body {
      font-family: 'Inter', sans-serif;
      background-color: #f4f7fc;
      color: #333;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .container {
      max-width: 1200px;
      width: 100%;
      padding: 20px;
      background-color: #ffffff;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      border-radius: 10px;
      overflow: hidden;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding-bottom: 20px;
      border-bottom: 2px solid #eaeaea;
    }
    header img {
      border-radius: 50%;
      width: 100px;
      height: 100px;
    }
    header .profile-info {
      flex-grow: 1;
      margin-left: 20px;
    }
    header .profile-info h1 {
      margin: 0;
      font-size: 2rem;
      color: #333;
    }
    header .profile-info p {
      font-size: 1rem;
      color: #666;
    }
    .about, .skills, .stats {
      margin-top: 30px;
    }
    .about h2, .skills h2, .stats h2 {
      font-size: 1.5rem;
      color: #0077b6;
    }
    .about p {
      font-size: 1.1rem;
      color: #444;
      line-height: 1.5;
    }
    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
    }
    .skills img {
      width: 50px;
      height: 50px;
      border-radius: 8px;
      transition: transform 0.3s ease;
    }
    .skills img:hover {
      transform: scale(1.1);
    }
    .card {
      background-color: #f9fafb;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
      margin-bottom: 20px;
    }
    .card h3 {
      margin-top: 0;
      color: #0077b6;
    }
    .github-stats img {
      max-width: 100%;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }
    .contact-btn {
      background-color: #0077b6;
      color: white;
      padding: 10px 20px;
      border-radius: 5px;
      text-decoration: none;
      display: inline-block;
      margin-top: 20px;
      transition: background-color 0.3s ease;
    }
    .contact-btn:hover {
      background-color: #005f8e;
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <img src="https://github.com/mrshoya05.png" alt="Shoyab Khan">
      <div class="profile-info">
        <h1>Shoyab Khan</h1>
        <p>Fullstack Developer | JavaScript Enthusiast | Problem Solver</p>
      </div>
    </header>

    <div class="about card">
      <h2>About Me</h2>
      <p>
        I'm a passionate Fullstack Developer with a focus on JavaScript and React. Currently diving deeper into Redux Toolkit and Advanced Node.js to level up my development skills. I love solving problems and building projects that make an impact. Feel free to ask me about JavaScript, React, Node.js, HTML, CSS, and more!
      </p>
    </div>

    <div class="skills card">
      <h2>Skills & Tools</h2>
      <div class="skills-icons">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="MongoDB">
      </div>
    </div>

    <div class="stats card">
      <h2>GitHub Stats</h2>
      <div class="github-stats">
        <img src="https://github-readme-stats.vercel.app/api?username=mrshoya05&show_icons=true&locale=en&theme=radical" alt="GitHub Stats">
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=mrshoya05&theme=radical" alt="GitHub Streak">
      </div>
    </div>

    <a href="mailto:shoyabkhan0508@gmail.com" class="contact-btn">Contact Me</a>
  </div>
</body>
</html>
