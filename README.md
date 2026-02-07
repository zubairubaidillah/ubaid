# ubaid
web
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Links</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: 'Inter', sans-serif;
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: #fff;
    }
    .card {
      width: 100%;
      max-width: 380px;
      padding: 32px 24px;
      background: rgba(255, 255, 255, 0.08);
      backdrop-filter: blur(12px);
      border-radius: 20px;
      text-align: center;
      box-shadow: 0 20px 40px rgba(0,0,0,0.3);
    }
    .avatar {
      width: 110px;
      height: 110px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid rgba(255,255,255,0.6);
      margin-bottom: 16px;
    }
    h1 {
      margin: 8px 0 4px;
      font-size: 1.5rem;
      font-weight: 700;
    }
    p {
      margin: 0 0 24px;
      font-size: 0.95rem;
      opacity: 0.85;
    }
    .links a {
      display: block;
      margin: 12px 0;
      padding: 14px 16px;
      border-radius: 14px;
      text-decoration: none;
      color: #fff;
      font-weight: 600;
      background: linear-gradient(135deg, #ff416c, #ff4b2b);
      transition: transform 0.15s ease, box-shadow 0.15s ease;
    }
    .links a:hover {
      transform: translateY(-2px);
      box-shadow: 0 10px 20px rgba(0,0,0,0.3);
    }
    footer {
      margin-top: 20px;
      font-size: 0.75rem;
      opacity: 0.6;
    }
  </style>
</head>
<body>
  <div class="card">
    <img src="https://via.placeholder.com/300" alt="Profile" class="avatar" />
    <h1>Nama Kamu</h1>
    <p>Web Developer · Creative Thinker</p>

    <div class="links">
      <a href="https://github.com/username" target="_blank">GitHub</a>
      <a href="https://instagram.com/username" target="_blank">Instagram</a>
      <a href="https://linkedin.com/in/username" target="_blank">LinkedIn</a>
      <a href="https://twitter.com/username" target="_blank">Twitter / X</a>
    </div>

    <footer>
      © 2026 · Built with ❤️
    </footer>
  </div>
</body>
</html>
