<!DOCTYPE html>
<html lang="ceb">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Matanao 21st Legislative Council</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Roboto', sans-serif;
      background: linear-gradient(135deg, #1e3c72, #2a5298);
      color: #fff;
      animation: fadeIn 2s ease-in;
    }
    header {
      background: linear-gradient(135deg, #ff6f00, #f57c00);
      padding: 3rem 1rem;
      text-align: center;
      box-shadow: 0 0 20px rgba(0,0,0,0.4);
    }
    header h1 {
      font-size: 2.8rem;
      margin-bottom: 0.5rem;
    }
    header p {
      font-size: 1.2rem;
    }
    nav {
      background: #0d47a1;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      padding: 1rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0.5rem 1rem;
      font-weight: bold;
      transition: transform 0.2s, background-color 0.3s;
      padding: 0.5rem 1rem;
      border-radius: 5px;
    }
    nav a:hover {
      background-color: #ff7043;
      transform: scale(1.1);
    }
    section {
      max-width: 960px;
      margin: auto;
      padding: 2rem 1rem;
    }
    section h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
      border-bottom: 2px solid #ffcc80;
      padding-bottom: 0.5rem;
    }
    .card {
      background: #ffffff10;
      border: 1px solid #ffffff33;
      border-left: 5px solid orange;
      padding: 1.5rem;
      margin-bottom: 1.5rem;
      border-radius: 10px;
      transition: transform 0.3s;
    }
    .card:hover {
      transform: translateY(-5px);
    }
    .card h3 {
      color: #fff;
      margin-bottom: 0.5rem;
    }
    .card p {
      color: #e0e0e0;
    }
    .button {
      display: inline-block;
      background-color: #ff9800;
      color: #fff;
      padding: 0.5rem 1.2rem;
      text-decoration: none;
      font-weight: bold;
      border-radius: 30px;
      margin-top: 1rem;
      transition: background 0.3s;
    }
    .button:hover {
      background-color: #f57c00;
    }
    footer {
      background: #0d47a1;
      text-align: center;
      padding: 2rem 1rem;
      margin-top: 3rem;
    }
    footer a {
      color: #ffcc80;
      text-decoration: none;
      margin: 0 0.5rem;
    }
    footer p {
      margin-top: 1rem;
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
    <p>Transparency • Legislation • Service</p>
  </header>

  <nav>
    <a href="#balita">📰 News</a>
    <a href="#ordinansa">📜 Ordinances</a>
    <a href="#resolusyon">📄 Resolutions</a>
    <a href="#trivia">❓ Trivia</a>
    <a href="#info">📢 Info & Announcements</a>
  
  <div style="text-align: center; margin: 2rem;">
    <button onclick="toggleOrdinanceReso()" style="background-color:#ff9800;color:white;padding:0.8rem 2rem;font-size:1rem;border:none;border-radius:30px;cursor:pointer;">📂 Show Ordinances & Resolutions</button>
  </div>

  <section id="balita">
    <h2>📰 Latest News</h2>
    <div class="card">
      <h3>Green Governance Initiative Launched</h3>
      <p>The council launched an environmental sustainability plan including green zoning ordinances.</p>
      <a href="#" class="button">Read More</a>
    </div>
  </section>

  <div id="ordinanceReso" style="display: none;">

</div>

  <section id="trivia">
    <h2>❓ Did You Know?</h2>
    <div class="card">
      <h3>Matanao Name Origin</h3>
      <p>“Matanao” came from the word “tan-aw,” meaning “to look or view” — given by native Bagobos who watched from the hills.</p>
    </div>
  </section>

  <section id="info">
    <h2>📢 Information & Announcements</h2>
    <div class="card">
      <h3>Public Hearing – August 15, 2025</h3>
      <p>All stakeholders are invited to join the discussion on the upcoming zoning code revision at the municipal hall.</p>
    </div>
  </section>

  <footer>
    <div>
      <a href="https://www.facebook.com/matanaolegislativecouncil" target="_blank">Facebook</a>
      <a href="https://m.me/matanaolegislativecouncil" target="_blank">Messenger</a>
    </div>
    <p><strong>Contact:</strong> 0912 345 6789</p>
    <p>&copy; 2025 Matanao 21st Legislative Council. All Rights Reserved.</p>
  </footer>
<script>
function toggleOrdinanceReso() {
  const section = document.getElementById('ordinanceReso');
  section.style.display = section.style.display === 'none' ? 'block' : 'none';
}
</script>

</html>
