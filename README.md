<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>DJ Renzo Escobal</title>
  <link rel="stylesheet" href="estilos.css" />
</head>
<body>
  <header>
    <img src="logo.jpg" alt="Logo DJ Renzo" class="logo"/>
    <h1>🎧 DJ Renzo Escobal</h1>
    <p>DJ Open Format: Cachengue, electrónica, reggaetón, house, techno y más. ¡El ritmo que tu evento necesita!</p>
  </header>

 <section class="musica">
  <h2>
    <a href="https://soundcloud.com/djrenzoescobal/sets/setlive" target="_blank">
      🎶 Escuchá una muestra de mi energía
    </a>
  </h2>

  <iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay"
    src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/playlists/2047087026&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true">
  </iframe>

  <p>
    <a href="https://soundcloud.com/djrenzoescobal/sets/setlive" target="_blank" class="boton-soundcloud">
      🔊 Escuchá el set completo en SoundCloud
    </a>
  </p>
</section>




  <section class="galeria">
    <h2>Galería</h2>
    <div class="fotos">
      <img src="galeria1.jpg" alt="DJ Renzo tocando" />
      <img src="galeria2.jpg" alt="DJ Renzo tocando" />
    </div>
  </section>

<section class="contacto">
  <h2>Contacto</h2>
  <p>📩 renzoescobal9@gmail.com</p>
  <p>📱 <a href="https://wa.me/59891954045" target="_blank">WhatsApp</a></p>
  <p>📸 <a href="https://www.instagram.com/renzoescobal9/" target="_blank">Instagram</a> | 
     🎵 <a href="https://soundcloud.com/djrenzoescobal" target="_blank">SoundCloud</a> | 
     🔴 <a href="https://www.youtube.com/@DJRenzoEscobal" target="_blank">YouTube</a></p>
</section>


  <footer>
    <p>© 2025 DJ Renzo Escobal • Tacuarembó, Uruguay</p>
  </footer>

  <a href="https://wa.me/59891954045" class="whatsapp-float" target="_blank">💬</a>
</body>
</html>

{
	"folders": [
		{
			"path": "../Nueva carpeta"
		}
	],
	"settings": {}
}
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background-color: #0d0d0d;
  color: white;
  text-align: center;
}

header {
  padding: 1.5em;
  background: linear-gradient(145deg, #16114c, #ff0000);
}
.logo {
  width: 250px;
  margin-bottom: 1em;
  border-radius: 10%
}

section {
  padding: 2em;
}

.fotos {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 1em;
}

.fotos img {
  max-width: 350px;
  width: 100%;
  height: auto;
  object-fit: cover;
  border-radius: 10px;
  border: 2px solid #000000;
  
}

.boton-soundcloud {
  display: inline-block;
  margin-top: 1em;
  padding: 0.6em 1.2em;
  background-color: #ff5500;
  color: white;
  border-radius: 8px;
  font-weight: bold;
  text-decoration: none;
  transition: background-color 0.3s ease;
}

.boton-soundcloud:hover {
  background-color: #e64a00;
}


.boton-soundcloud:hover {
  background-color: #e64a00;
}


.img-especial {
  max-width: 300px;
  width: 100%;
  height: auto;
}


a {
  color: #00e676;
  text-decoration: none;
}
a:hover {
  text-decoration: underline;
}

footer {
  background-color: #000000;
  padding: 1em;
  font-size: 0.9em;
  margin-top: 2em;
}

.whatsapp-float {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background: #25d366;
  color: white;
  padding: 0.5em 0.8em;
  border-radius: 50%;
  font-size: 1.5em;
  text-decoration: none;
}

.musica iframe {
  margin: 20px auto; /* arriba y abajo 20px, centrado horizontal */
  display: block;    /* para que el margin auto funcione y se centre */
  max-width: 100%;   /* que no se pase del ancho del contenedor */
  border-radius: 10px; /* para que tenga bordes redondeados */
  box-shadow: 0 0 15px #ff5500aa; /* un poco de sombra */
}

.musica {
  padding: 2rem 1rem;
  max-width: 700px;
  margin: 0 auto 3rem auto;
  text-align: center;
}

.musica iframe {
  margin: 20px auto;
  display: block;
  max-width: 100%;
  border-radius: 10px;
  box-shadow: 0 0 15px #ff5500aa;
}

section {
  padding: 1.5rem 1rem;  /* reduce el padding vertical */
  margin-bottom: 1.5rem; /* reduce el espacio entre secciones */
}

.musica {
  padding-bottom: 1rem;  /* menos espacio abajo para que no quede tan separado */
  margin-bottom: 1rem;
}

.galeria {
  padding-top: 0.5rem;  /* menos espacio arriba */
  margin-top: 0;
}


