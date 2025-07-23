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
      background: url('https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=1920&q=80') no-repeat center center fixed;
      background-size: cover;
      color: #fff;
    }

    header {
      background-color: rgba(0, 100, 0, 0.8);
      color: white;
      padding: 20px;
      text-align: center;
      backdrop-filter: blur(4px);
    }

    nav {
      display: flex;
      justify-content: center;
      background-color: rgba(34, 139, 34, 0.8);
      padding: 10px;
      gap: 20px;
      backdrop-filter: blur(4px);
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      padding: 8px 16px;
      border-radius: 20px;
      background-color: rgba(0, 128, 0, 0.9);
      transition: background 0.3s;
    }

    nav a:hover {
      background-color: rgba(0, 100, 0, 0.9);
    }

    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
      background-color: rgba(0, 0, 0, 0.5);
      border-radius: 15px;
      margin-top: 30px;
      opacity: 0;
      transform: translateY(20px);
      animation: fadeInUp 1s forwards;
      color: #f0f0f0;
    }

    @keyframes fadeInUp {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    h2 {
      margin-bottom: 20px;
      color: #90ee90;
    }

    .file-btn {
      display: inline-block;
      margin: 10px 10px 0 0;
      padding: 10px 20px;
      background-color: rgba(60, 179, 113, 0.9);
      color: white;
      border: none;
      border-radius: 20px;
      text-decoration: none;
      transition: background 0.3s;
    }

    .file-btn:hover {
      background-color: rgba(46, 139, 87, 0.9);
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
    <p>- July 22, 2025:Visitors from Zamboanga del Sur Visits the Municipality of Matanao for Their 3 day benchmarking!.</p>
    <img src="images/" alt="Health Services" style="width: 100%; border-radius: 10px;">

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
