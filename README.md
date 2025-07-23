<html lang="ceb">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Matanao 21st Legislative Council</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  
    #ordinanceReso {
      max-height: 0;
      overflow: hidden;
      transition: all 0.5s ease;
      opacity: 0;
    }
    #ordinanceReso.show {
      max-height: 1000px;
      opacity: 1;
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
  if (section.style.display === 'none') {
    section.style.display = 'block';
    section.style.maxHeight = section.scrollHeight + 'px';
    section.style.opacity = 1;
  } else {
    section.style.maxHeight = '0';
    section.style.opacity = 0;
    setTimeout(() => section.style.display = 'none', 300);
  }
}
</script>

</html>

