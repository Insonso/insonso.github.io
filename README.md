<!DOCTYPE html>
<html lang="pt">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Podcast Insonso</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap');

  body {
    background: #7f9cff; /* azul suave, mais escuro */
    font-family: 'Poppins', sans-serif;
    margin: 0;
    color: #ffffff; /* texto branco */
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 40px 20px;
    min-height: 100vh;
  }

  .logo-space {
    height: 120px;
    width: 120px;
    margin-bottom: 30px;
  }

  h1 {
    font-weight: 700;
    font-size: 3rem;
    letter-spacing: 5px;
    color: white;
    text-shadow: 1.5px 1.5px 5px rgba(0,0,0,0.3);
    margin: 0 0 10px 0;
  }

  p.subtitle {
    font-weight: 400;
    font-size: 1.2rem;
    margin-top: 0;
    color: #d3d9ff;
  }

  .follow-text {
    font-size: 1.3rem;
    margin: 30px 0 15px 0;
    color: #ffffff;
    display: flex;
    align-items: center;
    gap: 10px;
  }

  .links {
    display: flex;
    flex-direction: column;
    gap: 18px;
    width: 250px;
  }

  .link-button {
    background: white;
    color: #1e3a8a;
    font-weight: 700;
    font-size: 1.1rem;
    text-align: center;
    padding: 14px 0;
    border-radius: 10px;
    text-decoration: none;
    box-shadow: 0 4px 8px rgba(30,58,138,0.2);
    transition: background 0.3s ease, color 0.3s ease;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 12px;
  }

  .link-button:hover {
    background: #4661e6;
    color: white;
    box-shadow: 0 6px 12px rgba(70,97,230,0.7);
  }

  .link-button img {
    width: 24px;
    height: 24px;
  }
</style>
</head>
<body>

  <div class="logo-space" aria-label="Espaço reservado para o logo">
    <!-- Insere aqui o logo -->
  </div>

  <h1>🧂 INSONSO 🧂 </h1>

  <div class="follow-text">🎧 Segue-nos nas redes abaixo 👇🏻</div>
<br>
</br>
  <div class="links">
    <a href="https://youtube.com/teu_canal" target="_blank" rel="noopener" class="link-button">
      <img src="https://upload.wikimedia.org/wikipedia/commons/b/b8/YouTube_Logo_2017.svg" alt="YouTube" />
      YouTube
    </a>
    <a href="https://spotify.com/teu_podcast" target="_blank" rel="noopener" class="link-button">
      <img src="https://upload.wikimedia.org/wikipedia/commons/1/19/Spotify_logo_without_text.svg" alt="Spotify" />
      Spotify
    </a>
    <a href="https://tiktok.com/@teu_perfil" target="_blank" rel="noopener" class="link-button">
      <img src="https://upload.wikimedia.org/wikipedia/en/a/a9/TikTok_logo.svg" alt="TikTok" />
      TikTok
    </a>
    <a href="https://instagram.com/teu_perfil" target="_blank" rel="noopener" class="link-button">
      <img src="https://upload.wikimedia.org/wikipedia/commons/e/e7/Instagram_logo_2016.svg" alt="Instagram" />
      Instagram
    </a>
  </div>

</body>
</html>
