<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Raven's Interactive Page</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <header>
    <h1>Hi there, I'm Raven 👋</h1>
    <p>Learn, Code, Enjoy!</p>
  </header>

  <!-- MP4 Video Section -->
  <section id="video-section">
    <video id="promo-video" width="640" height="360" controls autoplay>
      <source src="https://media.tenor.com/WkuQC7dwNa8AAAPo/space-wallpaper-stars-background.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </section>

  <!-- Buttons for Actions -->
  <section id="buttons">
    <button onclick="startTicTacToe()">Start Tic-Tac-Toe</button>
    <button onclick="playSugaRush()">Play Suga Rush</button>
    <button onclick="showContact()">Contact Me</button>
  </section>

  <!-- Tic-Tac-Toe Game -->
  <section id="tic-tac-toe" style="display: none;">
    <h2>Tic-Tac-Toe</h2>
    <div id="board">
      <div class="cell" onclick="makeMove(0)"></div>
      <div class="cell" onclick="makeMove(1)"></div>
      <div class="cell" onclick="makeMove(2)"></div>
      <div class="cell" onclick="makeMove(3)"></div>
      <div class="cell" onclick="makeMove(4)"></div>
      <div class="cell" onclick="makeMove(5)"></div>
      <div class="cell" onclick="makeMove(6)"></div>
      <div class="cell" onclick="makeMove(7)"></div>
      <div class="cell" onclick="makeMove(8)"></div>
    </div>
    <p id="winner-message"></p>
    <button onclick="resetGame()">Reset Game</button>
  </section>

  <!-- GitHub Stats and Contact Info -->
  <section id="contact">
    <div>
      <h3>About Me</h3>
      <p>I'm learning **JavaScript**, **Python**, and **Web Development**.</p>
    </div>
    <div>
      <a href="https://wa.me/40736676893" target="_blank">
        <img src="https://img.shields.io/badge/WhatsApp-%230075E4.svg?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
      </a>
      <a href="https://github.com/YourUsername" target="_blank">
        <img src="https://img.shields.io/badge/GitHub-%2312100E.svg?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
      </a>
    </div>
    <div>
      <img src="https://github-readme-stats.vercel.app/api?username=YourUsername&show_icons=true&theme=radical" alt="GitHub Stats">
    </div>
  </section>

  <script src="script.js"></script>
</body>
</html>
