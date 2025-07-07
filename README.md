<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Bhaargavan Nilayam</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Orbitron', sans-serif;
      background: linear-gradient(135deg, #0a0a0a 0%, #1a1a1a 100%);
      color: #ffffff;
      overflow-x: hidden;
    }

    .hero {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      background: radial-gradient(circle, #0d0d0d 0%, #090909 100%);
      text-align: center;
      padding: 0 20px;
    }

    .hero h1 {
      font-size: 4rem;
      color: #00bfff;
      text-shadow: 0 0 20px #00bfff;
    }

    .hero p {
      font-size: 1.5rem;
      margin-top: 10px;
      color: #ff4444;
      text-shadow: 0 0 10px #ff4444;
    }

    .buttons {
      margin-top: 40px;
    }

    .btn {
      text-decoration: none;
      color: white;
      font-weight: bold;
      font-size: 1rem;
      margin: 10px;
      padding: 15px 30px;
      border-radius: 50px;
      background: linear-gradient(135deg, #ff0000, #0000ff);
      box-shadow: 0 0 20px rgba(255, 0, 0, 0.6), 0 0 20px rgba(0, 0, 255, 0.6);
      transition: transform 0.3s ease;
    }

    .btn:hover {
      transform: scale(1.1);
    }

    .section {
      padding: 80px 20px;
      text-align: center;
      background: #111;
      border-top: 1px solid #222;
    }

    .section h2 {
      font-size: 2.5rem;
      color: #00bfff;
      text-shadow: 0 0 15px #00bfff;
      margin-bottom: 20px;
    }

    .section p {
      font-size: 1.2rem;
      color: #ccc;
    }

    .coming-soon {
      color: #ff5555;
      font-size: 1.5rem;
      margin-top: 15px;
      text-shadow: 0 0 10px #ff4444;
    }

    footer {
      padding: 30px;
      font-size: 0.9rem;
      background: #080808;
      color: #666;
      border-top: 1px solid #222;
    }

    @media screen and (max-width: 768px) {
      .hero h1 {
        font-size: 2.8rem;
      }

      .hero p {
        font-size: 1.2rem;
      }

      .btn {
        font-size: 0.9rem;
        padding: 12px 24px;
      }
    }
  </style>
</head>
<body>

  <div class="hero">
    <h1>BHAARGAVAN NILAYAM</h1>
    <p>The Home of Legends. A Community. A Legacy.</p>
    <div class="buttons">
      <a href="https://youtube.com/@bhaargavan_ahnee?si=qAwxbg3UZx8vlN7r" target="_blank" class="btn">📺 YouTube</a>
      <a href="https://discord.gg/ENy3Z3Rb" target="_blank" class="btn">💬 Discord</a>
    </div>
  </div>

  <div class="section">
    <h2>🛡️ Nilayam SMP</h2>
    <p>Our official Minecraft survival multiplayer server is coming soon.</p>
    <p class="coming-soon">🌐 IP & Port – Coming Soon</p>
  </div>

  <div class="section">
    <h2>🔥 About Bhaargavan</h2>
    <p>Bhaargavan is not just a creator — he’s a movement. With insane storytelling, unfiltered content, and deep community vibes, Nilayam is where it all comes together.</p>
  </div>

  <footer>
    © 2025 Bhaargavan Nilayam. Built for the community.
  </footer>

</body>
</html>
