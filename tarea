<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>Ey compa 😎</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: radial-gradient(circle, #d1f0ff, #81d4fa);
      font-family: 'Segoe UI', sans-serif;
      overflow: hidden;
    }

    .contenedor {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      text-align: center;
      color: #222;
    }

    .titulo {
      font-size: 2em;
      margin-bottom: 30px;
    }

    .boton {
      background: #2196f3;
      color: white;
      padding: 15px 30px;
      font-size: 1.2em;
      border: none;
      border-radius: 30px;
      cursor: pointer;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
      
      /* Empieza invisible, pequeño y desplazado lejos */
      opacity: 0;
      transform: translateY(200px) translateX(200px) scale(0.5);
      transition: 
        opacity 0.8s ease,
        transform 0.8s ease;
    }

    .boton.visible {
      opacity: 1;
      transform: translateY(0) scale(1);
    }

    .boton:hover {
      background: #1976d2;
    }

    .respuesta {
      display: none;
      margin-top: 40px;
      font-size: 1.5em;
      animation: aparecer 1s ease-out forwards;
    }

    @keyframes aparecer {
      0% { opacity: 0; transform: scale(0.8); }
      100% { opacity: 1; transform: scale(1); }
    }

    .emoji {
      font-size: 4em;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <div class="contenedor">
    <div class="titulo">Ey bro... 😏</div>
    <button class="boton" id="botonTarea" onclick="mostrarRespuesta()">Aquí mrd 😂</button>
    <div id="respuesta" class="respuesta">
      ¡Pasa la tarea OE! 😎<br>
      <div class="emoji">☕📚</div>
    </div>
  </div>

  <script>
    window.onload = () => {
      setTimeout(() => {
        document.getElementById('botonTarea').classList.add('visible');
      }, 1000); // Aparece después de 1 segundo
    };

    function mostrarRespuesta() {
      document.getElementById("respuesta").style.display = 'block';
    }
  </script>

</body>
</html>

