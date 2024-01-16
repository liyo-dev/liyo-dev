<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tus tarjetas</title>
  <style>
    body {
      text-align: center;
    }

    .profile-pic-container {
      width: 150px;
      height: 150px;
      overflow: hidden;
      border-radius: 50%;
      border: 5px solid white;
      margin: 0 auto;
    }

    .profile-pic {
      width: 100%;
      height: 100%;
      border-radius: 50%;
      object-fit: cover;
    }

    .last-works {
      display: flex;
      justify-content: space-between;
      margin-top: 20px;
    }

    .card {
      background-color: white;
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      width: 45%;
    }

    .card img {
      width: 100%;
      max-width: 400px;
      border-radius: 10px;
      background-color: white;
    }
  </style>
</head>
<body>
  <!-- Foto de perfil -->
  <div class="profile-pic-container">
    <img src="https://github.com/liyo-dev/assets/blob/main/profile-pic.png" alt="liyodev" class="profile-pic">
  </div>

  <h3>¡Hola 👋! Soy liyodev</h3>
  <p>Soy desarrollador de Software y en mi tiempo libre desarrollo videojuegos.<br>
    ¡Revisa mis juegos 👇!<br>
    <img src="https://github.com/liyo-dev/assets/raw/main/itch-io-icon-2048x2048-i6hzclad.png" alt="aquí" width="40">
  </p>

  <!-- Sección de Últimos trabajos realizados -->
  <div class="last-works">
    <!-- Tarjeta 1: Juego Alex´s Adventure -->
    <div class="card">
      <p>Juego: Alex´s Adventure</p>
      <a href="https://nonamegamesmlg.itch.io/alexs-adventure-the-curse-of-eternal-night" target="_blank">
        <img src="https://github.com/liyo-dev/assets/blob/main/logo_itch_banner.png" alt="Alex´s Adventure">
      </a>
    </div>

    <!-- Tarjeta 2: Web para NoNameGames -->
    <div class="card">
      <p>Web para NoNameGames</p>
      <a href="https://nonamegames.es/" target="_blank">
        <img src="https://github.com/liyo-dev/assets/blob/main/1500x500banner.jpeg" alt="web nonamegames">
      </a>
    </div>
  </div>
</body>
</html>
