<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Aroma de Pizza Lounge 2025 - Vídeos e Reservas VIP</title>
<style>
  body {
    font-family: Arial, sans-serif;
    background: #fef8f2;
    color: #333;
    margin: 0; padding: 0;
  }
  header {
    background-color: #8B0000;
    color: white;
    padding: 20px;
    text-align: center;
  }
  main {
    max-width: 600px;
    margin: auto;
    padding: 20px;
  }
  .carousel {
    position: relative;
    width: 100%;
    height: 450px;
    overflow: hidden;
    margin-bottom: 20px;
  }
  .slides {
    display: flex;
    width: 300%;
    transition: transform 0.5s ease;
  }
  .slide {
    width: 100%;
    flex-shrink: 0;
    display: flex;
    justify-content: center;
  }
  iframe {
    border: none;
    width: 100%;
    max-width: 500px;
    height: 450px;
  }
  .buttons {
    text-align: center;
  }
  button {
    background-color: #8B0000;
    color: white;
    border: none;
    padding: 12px 20px;
    margin: 0 10px;
    border-radius: 5px;
    font-size: 18px;
    cursor: pointer;
  }
  button:hover {
    background-color: #a70000;
  }
  .contact-buttons {
    margin-top: 30px;
    display: flex;
    justify-content: center;
    gap: 20px;
  }
  .contact-buttons a {
    background-color: #8B0000;
    color: white;
    padding: 15px 25px;
    border-radius: 5px;
    text-decoration: none;
    font-weight: bold;
  }
  .contact-buttons a:hover {
    background-color: #a70000;
  }
</style>
</head>
<body>
<header>
  <h1>Aroma de Pizza Lounge 24h</h1>
  <p>04, 05 e 06 de Julho - São Pedro de Caém 2025</p>
</header>

<main>
  <h2>Confira os melhores momentos da edição passada</h2>

  <div class="carousel" aria-label="Vídeos do Aroma de Pizza Lounge">
    <div class="slides" id="slides">
      <div class="slide">
        <iframe src="https://www.instagram.com/reel/C8h0YKJPlJr/embed" allowfullscreen></iframe>
      </div>
      <div class="slide">
        <iframe src="https://www.instagram.com/reel/C8w7vAEO8mN/embed" allowfullscreen></iframe>
      </div>
      <div class="slide">
        <iframe src="https://www.instagram.com/reel/C9CXTAYuFu2/embed" allowfullscreen></iframe>
      </div>
    </div>
  </div>

  <div class="buttons">
    <button onclick="prevSlide()">◀️ Anterior</button>
    <button onclick="nextSlide()">Próximo ▶️</button>
  </div>

  <div class="contact-buttons">
    <a href="https://wa.me/5571992686345" target="_blank" rel="noopener noreferrer">📱 WhatsApp (71) 99268-6345</a>
    <a href="mailto:aromadepizzalounge@gmail.com">📧 aromadepizzalounge@gmail.com</a>
  </div>
</main>

<script>
  const slides = document.getElementById('slides');
  let currentIndex = 0;

  function showSlide(index) {
    if (index < 0) index = 2;
    if (index > 2) index = 0;
    currentIndex = index;
    slides.style.transform = 'translateX(' + (-index * 100) + '%)';
  }

  function nextSlide() {
    showSlide(currentIndex + 1);
  }

  function prevSlide() {
    showSlide(currentIndex - 1);
  }
</script>

</body>
</html>
