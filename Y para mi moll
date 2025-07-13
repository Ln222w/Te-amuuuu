<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Te amo Pablo Simón</title>
  <style>
    body {
      background-color: #ffe6f0;
      color: #d10068;
      font-family: 'Comic Sans MS', cursive, sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding-top: 140px;
      overflow-x: hidden;
      margin: 0;
    }

    .mensaje {
      font-size: 2rem;
      margin: 10px;
      animation: flotar 3s ease-in-out infinite;
    }

    @keyframes flotar {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }

    .audio-container {
      position: fixed;
      top: 20px;
      left: 50%;
      transform: translateX(-50%);
      display: flex;
      flex-direction: column;
      align-items: center;
      z-index: 1000;
    }

    .boton {
      margin-top: 10px;
      padding: 10px 20px;
      background-color: #ff66a3;
      color: white;
      border: none;
      border-radius: 25px;
      font-size: 1rem;
      cursor: pointer;
      box-shadow: 0 4px 6px rgba(0,0,0,0.2);
      transition: background 0.3s;
    }

    .boton:hover {
      background-color: #e05592;
    }

    .dedicatoria {
      position: fixed;
      bottom: 20px;
      text-align: center;
      font-size: 1.2rem;
      color: #a6005a;
      background-color: #fff0f5;
      padding: 10px 20px;
      border-radius: 20px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    iframe {
      border-radius: 12px;
    }
  </style>
</head>
<body>
  <!-- Reproductor de música y botón -->
  <div class="audio-container">
    <iframe id="musica" width="300" height="80"
      src="https://www.youtube.com/embed/LlGx8oj9_Z4?autoplay=1&loop=1&playlist=LlGx8oj9_Z4"
      frameborder="0" allow="autoplay; encrypted-media" allowfullscreen>
    </iframe>
    <button class="boton" onclick="reproducirNuevamente()">Volvé a escuchar 🎵</button>
  </div>

  <!-- Muchos "Te amo Pablo Simón" -->
  <script>
    for (let i = 0; i < 100; i++) {
      const mensaje = document.createElement('div');
      mensaje.className = 'mensaje';
      mensaje.textContent = 'Te amo Pablo Simón 💖';
      document.body.appendChild(mensaje);
    }

    function reproducirNuevamente() {
      const iframe = document.getElementById("musica");
      const src = iframe.src;
      iframe.src = "";
      setTimeout(() => {
        iframe.src = src;
      }, 100);
    }
  </script>

  <!-- Dedicatoria -->
  <div class="dedicatoria">
    Por Lucía Castro, tu mexee 💌
  </div>
</body>
</html>
