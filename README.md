<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Eliane Miuki</title>

<style>
  /* Fundo e animação suave */
  body {
    margin: 0;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background: radial-gradient(circle at top left, #ffd6e8, #fce4ec, #ffeaf2);
    overflow: hidden;
    animation: fadeIn 3s ease-in-out;
  }

  /* Nome central */
  h1 {
    font-family: "Poppins", sans-serif;
    font-size: 3em;
    color: #ffb7d5;
    text-shadow: 0 0 10px #fff0fa, 0 0 20px #ffd6e8, 0 0 30px #ffc1e3;
    animation: pulse 2.5s infinite ease-in-out;
    letter-spacing: 3px;
    opacity: 0;
    transform: translateX(-40px);
    animation: slideIn 1.5s forwards ease-out, pulse 2.5s infinite ease-in-out 1.8s;
  }

  /* Aura cintilante */
  .aura {
    position: absolute;
    width: 300px;
    height: 300px;
    border-radius: 50%;
    background: radial-gradient(circle, rgba(255,192,203,0.4) 0%, rgba(255,255,255,0.1) 70%);
    filter: blur(60px);
    animation: glow 6s infinite alternate ease-in-out;
  }

  /* Animações */
  @keyframes fadeIn {
    from {opacity: 0;}
    to {opacity: 1;}
  }

  @keyframes pulse {
    0%, 100% {text-shadow: 0 0 10px #fff0fa, 0 0 20px #ffd6e8, 0 0 30px #ffc1e3;}
    50% {text-shadow: 0 0 20px #ffe4f3, 0 0 40px #ffccdc, 0 0 60px #ffc1e3;}
  }

  @keyframes slideIn {
    0% {opacity: 0; transform: translateX(-40px);}
    100% {opacity: 1; transform: translateX(0);}
  }

  @keyframes glow {
    0% {transform: scale(1);}
    100% {transform: scale(1.2);}
  }

  /* Música (pré-configurada para quando adicionar o arquivo) */
  audio {
    position: absolute;
    bottom: 20px;
    width: 60%;
    opacity: 0.2;
  }
</style>
</head>
<body>

  <div class="aura"></div>
  <h1>Eliane Miuki</h1>

  <!-- Trilha etérea (adicione depois o arquivo mp3 na mesma pasta e renomeie para musica.mp3) -->
  <!-- <audio autoplay loop volume="0.1">
      <source src="musica.mp3" type="audio/mpeg">
  </audio> -->

</body>
</html>

