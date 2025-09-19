# World-Championships
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Champion(ne) de Golf - Site Officiel</title>
  <style>
    /* 🌿 Style global */
    body {
      margin: 0;
      font-family: "Segoe UI", Arial, sans-serif;
      background: #f8f8f8;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(to right, #0a3d0a, #145214);
      color: white;
      text-align: center;
      padding: 5rem 2rem;
      position: relative;
    }
    header h1 {
      font-size: 3.5rem;
      margin: 0;
      animation: fadeInDown 1.5s ease;
    }
    header p {
      font-size: 1.3rem;
      margin-top: 10px;
      animation: fadeInUp 1.5s ease;
    }
    .cta-btn {
      margin-top: 20px;
      padding: 12px 25px;
      font-size: 1.1rem;
      background: #ffd700;
      color: #0a3d0a;
      border: none;
      border-radius: 30px;
      cursor: pointer;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .cta-btn:hover {
      transform: scale(1.1);
      box-shadow: 0 6px 15px rgba(0,0,0,0.2);
    }

    nav {
      background: #145214;
      display: flex;
      justify-content: center;
      padding: 1rem;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav a {
      color: white;
      margin: 0 20px;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ffd700;
    }

    section {
      padding: 4rem 2rem;
      max-width: 1100px;
      margin: auto;
    }
    h2 {
      color: #0a3d0a;
      border-left: 5px solid #ffd700;
      padding-left: 12px;
      margin-bottom: 20px;
    }

    .card {
      background: white;
      padding: 2rem;
      border-radius: 15px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      margin-bottom: 2rem;
      transition: transform 0.3s;
    }
    .card:hover {
      transform: translateY(-5px);
    }

    .gallery {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .gallery img {
      width: 300px;
      border-radius: 15px;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .gallery img:hover {
      transform: scale(1.05);
      box-shadow: 0 8px 15px rgba(0,0,0,0.3);
    }

    .video {
      text-align: center;
    }
    .video iframe {
      width: 100%;
      max-width: 700px;
      height: 400px;
      border-radius: 15px;
      border: none;
      box-shadow: 0 5px 20px rgba(0,0,0,0.3);
    }

    footer {
      background: #0a3d0a;
      color: white;
      text-align: center;
      padding: 2rem;
      margin-top: 3rem;
    }

    /* ✨ Animations */
    @keyframes fadeInDown {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    /* 📱 Responsive */
    @media (max-width: 768px) {
      header h1 { font-size: 2.2rem; }
      .gallery img { width: 100%; }
      .video iframe { height: 220px; }
    }
  </style>
</head>
<body>

  <!-- 🌟 En-tête -->
  <header>
    <h1>🏌️ Champion(ne) de Golf</h1>
    <p>Passion • Performance • Excellence</p>
    <button class="cta-btn" onclick="document.getElementById('contact').scrollIntoView({behavior:'smooth'})">
      Me Contacter
    </button>
  </header>
