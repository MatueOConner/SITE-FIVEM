<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Matuê O'Conner Highlight</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap');

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Orbitron', sans-serif;
      min-height: 100vh;
      overflow: hidden;
      position: relative;
      background-color: #0f0f0f;
      background-image:
        url("data:image/svg+xml,%3Csvg width='40' height='40' viewBox='0 0 40 40' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M0 39.5 L40 0.5 M-1 20 L20 -1 M20 41 L41 20' stroke='%231a1a1a' stroke-width='0.5'/%3E%3C/svg%3E"),
        linear-gradient(135deg, #0f0f0f, #1a1a1a);
      background-blend-mode: overlay;
    }

    .bg-image {
      position: fixed;
      top: 0;
      left: 0;
      width: 100vw;
      height: 100vh;
      background-image: url('IMG/TROPA\ SPEED.jpg');
      background-size: cover;
      background-position: center;
      transform: translateY(-50x);
      opacity: 0.5;
      filter: blur(1px) brightness(0.9);
      z-index: -2;
      animation: pulse 5s infinite;

    }

    .overlay-gradient {
      position: fixed;
      top: 0;
      left: 0;
      width: 100vw;
      height: 100vh;
      background: linear-gradient(to bottom right, rgba(0, 247, 255, 0.05), rgba(0, 0, 0, 0.6));
      z-index: -1;
    }

    header {
      text-align: center;
      margin-bottom: 40px;
      animation: fadeInDown 1s ease-in-out;
      color: #ff0000;
      text-shadow: 0 0 02px #ff0909, 0 0 20px #ff0000;
    }

    header h1 {
      font-size: 3rem;
    }

    .neon-box {
      background: rgba(250, 0, 0, 0.089);
      border: 2px solid #ff0000;
      border-radius: 15px;
      padding: 30px;
      width: 90%;
      max-width: 500px;
      box-shadow: 0 0 15px #ff000033, 0 0 30px #ff000022;
      animation: pulse 5s infinite;
      color: #ff0000;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }

    .neon-box p {
      font-size: 2rem;
      line-height: 3;
    }

    @keyframes pulse {
      0%, 100% {
        box-shadow: 0 0 15px #ff000033, 0 0 30px #ff000022;
      }
      50% {
        box-shadow: 0 0 25px #ff000088, 0 0 50px #ff000055;
      }
    }

    @keyframes fadeInDown {
      from {
        opacity: 0;
        transform: translateY(-30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .social-buttons {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 15px;
  margin-top: 20px;
}

.social-buttons a {
  padding: 10px 20px;
  border: 2px solid #ff0000;
  border-radius: 8px;
  color: #ff0000;
  text-decoration: none;
  font-weight: bold;
  text-transform: uppercase;
  background-color: transparent;
  box-shadow: 0 0 10px #ff000044;
  transition: all 0.3s ease;
  animation: pulse 5s infinite;
}

.social-buttons a:hover {
  background-color: #ff0000;
  color: #0f0f0f;
  box-shadow: 0 0 20px #ff0000, 0 0 40px #ff000088;
}
    
  </style>
</head>
<body>
  <!-- Imagem de fundo com efeitos -->
  <div class="bg-image"></div>
  <div class="overlay-gradient"></div>

  <header>
    <h1>FiveM Highlights</h1>
  </header>

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; padding: 20px;">
  <a href="HL 1.html" class="neon-box"><p>Highlight 01</p></a>
  <a href="HL 2.html" class="neon-box"><p>Highlight 02</p></a>
  <a href="HL 3.html" class="neon-box"><p>Highlight 03</p></a>
  <a href="HL 4.html" class="neon-box"><p>Highlight 04</p></a>
  <a href="HL 5.html" class="neon-box"><p>Highlight 05</p></a>
  <a href="HL 6.html" class="neon-box"><p>Highlight 06</p></a>
  <a href="HL 7.html" class="neon-box"><p>Highlight 07</p></a>
  <a href="HL 8.html" class="neon-box"><p>Highlight 08</p></a>
  <a href="HL 9.html" class="neon-box"><p>Highlight 09</p></a>
  <a href="HL 10.html" class="neon-box"><p>Highlight 10</p></a>
  <a href="HL 11.html" class="neon-box"><p>Highlight 11</p></a>
  <a href="HL 12.html" class="neon-box"><p>Highlight 12</p></a>
</div>

<div class="social-buttons">
  <a href="https://www.instagram.com/kayke_stu/" target="_blank">Instagram
  <a href="https://www.youtube.com/@Kayke_Stuhlert/featured" target="_blank">YouTube
  <a href="https://kick.com/kaykestuhlert"  target="_blank">Kick</a>
  <a href="https://www.twitch.tv/kayke_stuhlert"  target="_blank">Twitch</a>
  <a href="https://www.tiktok.com/@kayke_stuhlert" target="_blank">TikTok
</div>
</body>

