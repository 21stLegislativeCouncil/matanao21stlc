<!DOCTYPE html>
<html lang="ceb">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Matanao 21st Legislative Council</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background-color: #fff9f3;
      color: #333;
    }

    header {
      background-color: #8B0000;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      display: flex;
      justify-content: center;
      background-color: #FF8C00;
      padding: 10px;
      gap: 20px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      padding: 8px 16px;
      border-radius: 20px;
      background-color: #b33a00;
      transition: background 0.3s;
    }

    nav a:hover {
      background-color: #cc5500;
    }

    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
      opacity: 0;
      transform: translateY(20px);
      animation: fadeInUp 1s forwards;
    }

    section:nth-child(even) {
      background-color: #fff2e6;
    }

    @keyframes fadeInUp {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    h2 {
      margin-bottom: 20px;
      color: #8B0000;
    }

    .file-btn {
      display: inline-block;
      margin: 10px 10px 0 0;
      padding: 10px 20px;
      background-color: #FF8C00;
      color: white;
      border: none;
      border-radius: 20px;
      text-decoration: none;
      transition: background 0.3s;
    }

    .file-btn:hover {
      background-color: #cc5500;
    }
  </style>
</head>

<body>
  <header>
    <h1>Matanao 21st Legislative Council</h1>
    <p>Transparency | Governance | Development</p>
  </header>

  <nav>
    <a href="#news">News</a>
    <a href="#ordinances">Ordinances</a>
    <a href="#resolutions">Resolutions</a>
    <a href="#trivia">Trivia</a>
  </nav>

  <section id="news">
    <h2>📢 Latest News & Updates</h2>
    <p>- July 2025: New resolution passed to improve local health services.</p>
    <p>- June 2025: Matanao Council launched digital transparency portal.</p>
  </section>

  <section id="ordinances">
    <h2>📄 Ordinances</h2>
    <a class="file-btn" href="files/ordinance-001.pdf" target="_blank">Download Ordinance 001</a>
    <a class="file-btn" href="files/ordinance-002.pdf" target="_blank">Download Ordinance 002</a>
  </section>

  <section id="resolutions">
    <h2>📘 Resolutions</h2>
    <a class="file-btn" href="files/resolution-001.pdf" target="_blank">Download Resolution 001</a>
    <a class="file-btn" href="files/resolution-002.pdf" target="_blank">Download Resolution 002</a>
  </section>

  <section id="trivia">
    <h2>🎉 Trivia & Information</h2>
    <p>- Did you know? Matanao has passed over 100 ordinances since 2000!</p>
    <p>- The 21st Council was formed in 2022 with 12 active members.</p>
  </section>
</body>

</html>
