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
      background: url('https://media.giphy.com/media/kHZ3O9obY2laI/giphy.gif') no-repeat center center fixed;
      background-size: cover;
      position: relative;
    }

    body::before {
      content: "";
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(255, 247, 240, 0.92);
      z-index: 0;
    }

    * {
      position: relative;
      z-index: 1;
    }

    header {
      background: url('https://media.giphy.com/media/xT9IgpVvxN0kTz3F3G/giphy.gif') no-repeat center center;
      background-size: cover;
      color: white;
      padding: 4rem 1rem;
      text-align: center;
      font-family: 'Merriweather', serif;
      box-shadow: 0 4px 15px rgba(0,0,0,0.5);
      border-bottom: 5px solid orange;
    }

    header h1 {
      margin: 0;
      font-size: 3.2rem;
      text-shadow: 2px 2px 6px #000;
    }

    header p {
      font-style: italic;
      font-size: 1.4rem;
      text-shadow: 1px 1px 4px #000;
    }

    nav {
      display: flex;
      justify-content: center;
      background-color: maroon;
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
      background-color: darkorange;
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
      color: maroon;
    }

    .card {
      background-color: #fff;
      border-left: 10px solid darkorange;
      padding: 1.5rem 2rem;
      margin-bottom: 2rem;
      box-shadow: 0 4px 12px rgba(0,0,0,0.15);
      border-radius: 10px;
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card h3 {
      margin-top: 0;
      color: maroon;
    }

    .button {
      background-color: darkorange;
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
      background-color: maroon;
      transform: scale(1.05);
    }

    footer {
      background-color: maroon;
      color: white;
      text-align: center;
      padding: 1.5rem;
      font-size: 0.95rem;
      margin-top: 3rem;
      border-top: 5px solid orange;
    }
  </style>
</head>
<body>
  <header>
    <h1>Matanao 21st Legislative Council</h1>
    <p>Pag-alagad sa Katawhan, Pagpanalipod sa Kultura</p>
  </header>

  <nav>
    <a href="#balita">📰 Balita</a>
    <a href="#ordinansa">📜 Mga Ordinansa</a>
    <a href="#resolusyon">📄 Mga Resolusyon</a>
  </nav>

  <section id="balita">
    <h2>📰 Balita</h2>
    <div class="card">
      <h3>Indigenous Celebration sa Matanao</h3>
      <p>Gisaulog sa konseho ang kultura sa mga lumad pinaagi sa usa ka makalingaw nga kalihokan nga gipahigayon sa town plaza.</p>
      <a href="news/celebration-july2025.pdf" class="button" download>Basaha ang Balita</a>
    </div>
  </section>

  
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

  
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

  <footer>
    &copy; 2025 Konseho Panlalawigan sa Matanao | Gitukod alang sa serbisyo ug kultura.
  </footer>
</body>
</html>
