<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Lugar Seguro de Mani — Rise Up</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: #f9f7fb;
      color: #3d2a4d;
      text-align: center;
    }
    header {
      background: linear-gradient(135deg, #c4a1e0, #9c7bb8);
      color: white;
      padding: 2rem;
      border-bottom-left-radius: 50px;
      border-bottom-right-radius: 50px;
    }
    h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    .audio, .quotes, .dedicatoria, .galeria, .capsula, .contacto {
      margin: 2rem auto;
      max-width: 600px;
      background: white;
      border-radius: 20px;
      padding: 1.5rem;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    .quotes p {
      font-style: italic;
      font-size: 1.2rem;
    }
    .galeria img {
      max-width: 100px;
      margin: 0.5rem;
      border-radius: 10px;
    }
    button {
      background: #9c7bb8;
      color: white;
      border: none;
      padding: 0.7rem 1.2rem;
      margin: 0.5rem;
      border-radius: 10px;
      cursor: pointer;
      font-size: 1rem;
    }
    button:hover {
      background: #7d5e97;
    }
    textarea {
      width: 100%;
      height: 100px;
      border-radius: 10px;
      border: 1px solid #ccc;
      padding: 0.5rem;
      font-size: 1rem;
    }
    .modo-suave {
      background: #ede7f6;
      color: #3d2a4d;
    }
  </style>
</head>
<body>
  <header>
    <h1>Tú rincón lavanda</h1>
    <p>Con la fuerza de <strong>Rise Up</strong></p>
  </header>

  <section class="audio">
    <h2>🎵 Nuestra canción</h2>
    <iframe src="https://open.spotify.com/embed/track/0tV8pOpiNsKqUys0ilUcXz" width="100%" height="352" frameborder="0" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" style="border-radius:12px" allowfullscreen=""></iframe>
  </section>

  <section class="quotes">
    <h2>✨ Frases</h2>
    <p id="frase">I'll rise up</p>
  </section>

  <section class="dedicatoria">
    <h2>💌 Dedicatoria</h2>
    <textarea id="mensaje" placeholder="Escribe tu dedicatoria para Mani..."></textarea>
    <br>
    <button onclick="guardarMensaje()">Guardar</button>
  </section>

  <section class="galeria">
    <h2>📸 Nosotras</h2>
    <input type="file" id="fileInput" accept="image/*" multiple>
    <div id="imagenes"></div>
  </section>

  <section class="capsula">
    <h2>🌷 Cápsula de ánimo</h2>
    <button onclick="mostrarAnimo()">Abrir mensaje sorpresa</button>
    <p id="animo"></p>
  </section>

  <section class="contacto">
    <h2>📱 Contacto directo</h2>
    <p>Cuando quieras contarme cómo te sientes, solo pulsa aquí:</p>
    <a href="https://wa.me/525568189201" target="_blank">
      <button>Enviar WhatsApp a Mahe</button>
    </a>
  </section>

  <section>
    <button onclick="toggleSuave()">🌙 Activar/Desactivar modo suave</button>
  </section>

  <script>
    const frases = [
      "I'll rise up",
      "In spite of the ache",
      "I'll rise a thousand times again",
      "All we need is hope",
      "And we'll rise up"
    ];
    let i = 0;
    setInterval(() => {
      document.getElementById("frase").innerText = frases[i];
      i = (i + 1) % frases.length;
    }, 4000);

    function guardarMensaje() {
      const msg = document.getElementById("mensaje").value;
      localStorage.setItem("dedicatoria", msg);
      alert("Dedicatoria guardada 💜");
    }
    window.onload = () => {
      const saved = localStorage.getItem("dedicatoria");
      if (saved) document.getElementById("mensaje").value = saved;

      // Cargar imágenes guardadas
      const savedImages = JSON.parse(localStorage.getItem("imagenes")) || [];
      const cont = document.getElementById("imagenes");
      savedImages.forEach(src => {
        const img = document.createElement("img");
        img.src = src;
        cont.appendChild(img);
      });
    }

    document.getElementById("fileInput").addEventListener("change", (e) => {
      const cont = document.getElementById("imagenes");
      cont.innerHTML = "";
      const imageArray = [];
      Array.from(e.target.files).forEach(file => {
        const reader = new FileReader();
        reader.onload = () => {
          const img = document.createElement("img");
          img.src = reader.result;
          cont.appendChild(img);
          imageArray.push(reader.result);
          localStorage.setItem("imagenes", JSON.stringify(imageArray));
        };
        reader.readAsDataURL(file);
      });
    });

    const mensajes = [
      "Eres más fuerte de lo que imaginas 💪",
      "Siempre te levantarás, aunque cueste 💜",
      "Estoy contigo, Mani 🌸",
      "Tu luz nunca se apaga ✨"
    ];
    function mostrarAnimo() {
      const m = mensajes[Math.floor(Math.random()*mensajes.length)];
      document.getElementById("animo").innerText = m;
    }

    function toggleSuave() {
      document.body.classList.toggle("modo-suave");
    }
  </script>
</body>
</html>
