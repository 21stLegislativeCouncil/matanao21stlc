<html lang="ceb">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Matanao 21st Legislative Council</title>
  <link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@400;700&family=Roboto&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      color: #333;
      background: linear-gradient(to bottom, #e0f7fa, #e8f5e9);
      animation: gradientShift 30s ease infinite;
    }

    @keyframes gradientShift {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    header {
      background: linear-gradient(to right, #2196f3, #43a047);
      color: white;
      padding: 4rem 1rem;
      text-align: center;
      font-family: 'Merriweather', serif;
      box-shadow: 0 4px 15px rgba(0,0,0,0.5);
    }

    header h1 {
      margin: 0;
      font-size: 3rem;
      animation: slideIn 1.2s ease-out;
    }

    header p {
      font-style: italic;
      font-size: 1.4rem;
      animation: fadeIn 2s ease-in;
    }

    nav {
      display: flex;
      justify-content: center;
      background-color: #00796b;
      flex-wrap: wrap;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    }

    nav a {
      color: white;
      padding: 1rem 2rem;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1rem;
      transition: background 0.3s, transform 0.2s;
    }

    nav a:hover {
      background-color: orange;
      transform: scale(1.05);
    }

    section {
      padding: 3rem 2rem;
      max-width: 1000px;
      margin: auto;
    }

    section h2 {
      text-align: center;
      font-size: 2rem;
      margin-bottom: 2rem;
      color: #00796b;
    }

    .card {
      background-color: #ffffff;
      border-left: 10px solid orange;
      padding: 1.5rem 2rem;
      margin-bottom: 2rem;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      border-radius: 10px;
      transition: transform 0.3s, background-color 0.3s;
    }

    .card:hover {
      transform: scale(1.02);
      background-color: #f1f8e9;
    }

    .card h3 {
      margin-top: 0;
      color: #1b5e20;
    }

    .button {
      background-color: orange;
      color: white;
      border: none;
      padding: 0.7rem 1.4rem;
      font-size: 1rem;
      font-weight: bold;
      cursor: pointer;
      border-radius: 30px;
      text-decoration: none;
      display: inline-block;
      margin-top: 1rem;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
      transition: background 0.3s, transform 0.2s;
    }

    .button:hover {
      background-color: #00796b;
      transform: scale(1.05);
    }

    footer {
      background-color: #00796b;
      color: white;
      text-align: center;
      padding: 1.5rem;
      font-size: 0.95rem;
      margin-top: 3rem;
    }

    @keyframes slideIn {
      from { transform: translateY(-50px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
  </style>
</head>
<body>
  <header>
    <h1>Matanao 21st Legislative Council</h1>
    <p>Pag-alagad sa Katawhan, Pagpanalipod sa Kalibotan</p>
  </header>

  <nav>
    <a href="#balita">📰 Balita</a>
    <a href="#ordinansa">📜 Mga Ordinansa</a>
    <a href="#resolusyon">📄 Mga Resolusyon</a>
  </nav>

  <section id="balita">
    <h2>📰 Balita</h2>
    <div class="card">
      <h3>Celebrasyon sa Kalikupan</h3>
      <p>Gipasiugdahan sa konseho ang aktibidad nga nagpanalipod sa suba ug kalasangan sa Matanao.</p>
      <a href="news/eco-celebration.pdf" class="button" download>Basaha ang Balita</a>
    </div>
  </section>

  <section id="ordinansa">
    <h2>📜 Mga Ordinansa</h2>
    <div class="card">
      <h3>Ordinansa No. 2025-04</h3>
      <p>Pre-registration list alang sa Theoretical Driving Course (TDC) sa LGU Matanao.</p>
      <a href="ordinances/LGU-Matanao-Pre-reg-TDC.pdf" class="button" download>I-download Ordinansa</a>
    </div>
    <div class="card">
      <h3>Ordinansa No. 2025-02</h3>
      <p>Pagpanalipod sa mga tradisyonal nga teritoryo ug yutang kabilin sa mga lumad.</p>
      <a href="ordinances/2025-02.pdf" class="button" download>I-download Ordinansa</a>
    </div>
    <div class="card">
      <h3>Ordinansa No. 2025-03</h3>
      <p>Paghatag og subsidiya alang sa Indigenous People Education Program.</p>
      <a href="ordinances/2025-03.pdf" class="button" download>I-download Ordinansa</a>
    </div>
  </section>

  <section id="resolusyon">
    <h2>📄 Mga Resolusyon</h2>
    <div class="card">
      <h3>Resolusyon No. 2025-R07</h3>
      <p>Lista sa mga partisipante sa Pre-Registration sa TDC sa LGU Matanao.</p>
      <a href="resolutions/LGU-Matanao-Pre-reg-TDC.pdf" class="button" download>I-download Resolusyon</a>
    </div>
    <div class="card">
      <h3>Resolusyon No. 2025-R05</h3>
      <p>Pagduso sa pagsaulog sa Indigenous Peoples Month matag Oktubre.</p>
      <a href="resolutions/2025-R05.pdf" class="button" download>I-download Resolusyon</a>
    </div>
    <div class="card">
      <h3>Resolusyon No. 2025-R06</h3>
      <p>Pagdaug sa Matanao sa regional award sa cultural governance.</p>
      <a href="resolutions/2025-R06.pdf" class="button" download>I-download Resolusyon</a>
    </div>
  </section>

    <div style="margin-top: 1rem;">
      <p><strong>Kontak:</strong> 0912 345 6789</p>
      <a href="https://www.facebook.com/matanaolegislativecouncil" target="_blank" style="margin-right: 10px; color: white; text-decoration: underline;">Facebook</a>
      <a href="https://m.me/matanaolegislativecouncil" target="_blank" style="color: white; text-decoration: underline;">Messenger</a>
    </div>
  </footer>
</body>
</html>
