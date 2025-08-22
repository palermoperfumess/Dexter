<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>Fan Page - Dexter Morgan</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    /* --------- Base --------- */
    :root{
      --bg:#1c1c1c; --panel:#2a2a2a; --text:#eaeaea; --muted:#bdbdbd;
      --accent:#e63946; --accent-2:#c1121f; --footer:#111;
    }
    *{box-sizing:border-box}
    body{
      margin:0; background:var(--bg); color:var(--text);
      font-family: system-ui, -apple-system, "Segoe UI", Roboto, Arial, sans-serif;
      line-height:1.6;
    }
    h1,h2,h3{font-family: Georgia, "Times New Roman", serif; color:var(--accent); margin:0 0 .6rem}
    p, li{font-size:1.05rem}
    a{color:inherit}

    /* --------- Layout --------- */
    header{
      background:#000; padding:32px 16px; text-align:center; position:sticky; top:0; z-index:5;
      border-bottom:1px solid #333;
    }
    header h1{font-size:2.4rem}
    header p{margin:.25rem 0 0; color:var(--muted)}
    nav.quick{
      display:flex; gap:.5rem; justify-content:center; flex-wrap:wrap; margin-top:12px;
    }
    nav.quick a{
      text-decoration:none; background:var(--panel); padding:6px 10px; border-radius:999px; font-size:.95rem;
      border:1px solid #3a3a3a;
    }
    main{max-width:1000px; margin:auto; padding:24px 16px 80px}
    section{background:var(--panel); padding:24px; border-radius:14px; box-shadow:0 8px 20px rgba(0,0,0,.35); margin-bottom:22px}

    /* --------- Imágenes --------- */
    img{
      max-width:100%; height:auto; border-radius:12px; display:block;
      box-shadow:0 6px 16px rgba(0,0,0,.55); transition:transform .25s ease;
    }
    img:hover{transform:scale(1.02)}

    /* --------- Botón YouTube --------- */
    .youtube-btn{
      display:inline-flex; align-items:center; gap:10px; margin-top:12px;
      padding:12px 18px; background:#ff0000; color:#fff; border-radius:10px; text-decoration:none; font-weight:700;
      border:0; transition:filter .2s ease;
    }
    .youtube-btn:hover{filter:brightness(.9)}

    /* --------- Acordeones (temporadas) --------- */
    .seasons details{
      background:#242424; border:1px solid #3a3a3a; border-radius:12px; margin:10px 0; overflow:hidden;
    }
    .seasons summary{
      cursor:pointer; list-style:none; padding:16px 18px; font-weight:700; display:flex; align-items:center; gap:10px;
    }
    .seasons summary::before{
      content:"▸"; transition:transform .2s ease; font-size:1.1rem; color:var(--muted);
    }
    .seasons details[open] summary::before{transform:rotate(90deg)}
    .episodes{padding:0 18px 16px}
    .episodes ol{margin:0; padding-left:22px}
    .episodes li{padding:3px 0}
    .tag{display:inline-block; font-size:.85rem; color:#ddd; background:#333; padding:2px 8px; border-radius:999px; margin-left:6px}

    /* --------- Form --------- */
    form{display:grid; gap:10px; margin-top:8px}
    input, textarea{
      background:#1f1f1f; color:var(--text); border:1px solid #3a3a3a; border-radius:8px; padding:10px;
    }
    input[type="submit"]{
      background:var(--accent); border:none; cursor:pointer; font-weight:700;
    }
    input[type="submit"]:hover{background:var(--accent-2)}

    /* --------- Footer --------- */
    footer{background:var(--footer); color:#bbb; text-align:center; padding:18px}
  </style>
</head>
<body>
  <header>
    <h1>Dexter Morgan</h1>
    <p>Fan page del antihéroe forense de Miami</p>
    <nav class="quick" aria-label="Ir a">
      <a href="#quien">¿Quién es?</a>
      <a href="#personajes">Personajes</a>
      <a href="#episodios">Episodios</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <main>
    <section id="quien">
      <h2>¿Quién es Dexter?</h2>
      <p>Dexter Morgan es el protagonista de la serie “Dexter”. Trabaja como analista forense para la policía de Miami y también es un asesino serial que sigue su propio “código”.</p>
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSfTJjg0PboAT3IasKUfSFPllpSvJFBzMYPNw&s" alt="Dexter Morgan">
      <br>
      <a class="youtube-btn" href="https://www.youtube.com/watch?v=84o1Q6fB20k" target="_blank" rel="noopener">
        ▶ Ver video sobre Dexter en YouTube
      </a>
    </section>

    <section id="personajes">
      <h2>Personajes principales</h2>
      <ul>
        <li><strong>Debra Morgan</strong>: hermana adoptiva y detective.</li>
        <li><strong>Harry Morgan</strong>: padre adoptivo; le enseña el “código”.</li>
        <li><strong>Rita Bennett</strong>: pareja y luego esposa en etapas de la serie.</li>
        <li><strong>Ángel Batista</strong>: detective y amigo de Dexter.</li>
      </ul>
    </section>

    <section id="episodios" class="seasons">
      <h2>Episodios (T1–T8)</h2>

      <!-- T1 -->
      <details>
        <summary>Temporada 1 <span class="tag">2006 • 12 eps</span></summary>
        <div class="episodes">
          <ol>
            <li>1×01 — Dexter</li>
            <li>1×02 — Crocodile</li>
            <li>1×03 — Popping Cherry</li>
            <li>1×04 — Let’s Give the Boy a Hand</li>
            <li>1×05 — Love American Style</li>
            <li>1×06 — Return to Sender</li>
            <li>1×07 — Circle of Friends</li>
            <li>1×08 — Shrink Wrap</li>
            <li>1×09 — Father Knows Best</li>
            <li>1×10 — Seeing Red</li>
            <li>1×11 — Truth Be Told</li>
            <li>1×12 — Born Free</li>
          </ol>
        </div>
      </details>

      <!-- T2 -->
      <details>
        <summary>Temporada 2 <span class="tag">2007 • 12 eps</span></summary>
        <div class="episodes">
          <ol>
            <li>2×01 — It’s Alive!</li>
            <li>2×02 — Waiting to Exhale</li>
            <li>2×03 — An Inconvenient Lie</li>
            <li>2×04 — See-Through</li>
            <li>2×05 — The Dark Defender</li>
            <li>2×06 — Dex, Lies, and Videotape</li>
            <li>2×07 — That Night, a Forest Grew</li>
            <li>2×08 — Morning Comes</li>
            <li>2×09 — Resistance Is Futile</li>
            <li>2×10 — There’s Something About Harry</li>
            <li>2×11 — Left Turn Ahead</li>
            <li>2×12 — The British Invasion</li>
          </ol>
        </div>
      </details>

      <!-- T3 -->
      <details>
        <summary>Temporada 3 <span class="tag">2008 • 12 eps</span></summary>
        <div class="episodes">
          <ol>
            <li>3×01 — Our Father</li>
            <li>3×02 — Finding Freebo</li>
            <li>3×03 — The Lion Sleeps Tonight</li>
            <li>3×04 — All in the Family</li>
            <li>3×05 — Turning Biminese</li>
            <li>3×06 — Sí Se Puede</li>
            <li>3×07 — Easy as Pie</li>
            <li>3×08 — The Damage a Man Can Do</li>
            <li>3×09 — About Last Night</li>
            <li>3×10 — Go Your Own Way</li>
            <li>3×11 — I Had a Dream</li>
            <li>3×12 — Do You Take Dexter Morgan?</li>
          </ol>
        </div>
      </details>

      <!-- T4 -->
      <details>
        <summary>Temporada 4 <span class="tag">2009 • 12 eps</span></summary>
        <div class="episodes">
          <ol>
            <li>4×01 — Living the Dream</li>
            <li>4×02 — Remains to Be Seen</li>
            <li>4×03 — Blinded by the Light</li>
            <li>4×04 — Dex Takes a Holiday</li>
            <li>4×05 — Dirty Harry</li>
            <li>4×06 — If I Had a Hammer</li>
            <li>4×07 — Slack Tide</li>
            <li>4×08 — Road Kill</li>
            <li>4×09 — Hungry Man</li>
            <li>4×10 — Lost Boys</li>
            <li>4×11 — Hello, Dexter Morgan</li>
            <li>4×12 — The Getaway</li>
          </ol>
        </div>
      </details>

      <!-- T5 -->
      <details>
        <summary>Temporada 5 <span class="tag">2010 • 12 eps</span></summary>
        <div class="episodes">
          <ol>
            <li>5×01 — My Bad</li>
            <li>5×02 — Hello, Bandit</li>
            <li>5×03 — Practically Perfect</li>
            <li>5×04 — Beauty and the Beast</li>
            <li>5×05 — First Blood</li>
            <li>5×06 — Everything Is Illumenated</li>
            <li>5×07 — Circle Us</li>
            <li>5×08 — Take It!</li>
            <li>5×09 — Teenage Wasteland</li>
            <li>5×10 — In the Beginning</li>
            <li>5×11 — Hop a Freighter</li>
            <li>5×12 — The Big One</li>
          </ol>
        </div>
      </details>

      <!-- T6 -->
      <details>
        <summary>Temporada 6 <span class="tag">2011 • 12 eps</span></summary>
        <div class="episodes">
          <ol>
            <li>6×01 — Those Kinds of Things</li>
            <li>6×02 — Once Upon a Time...</li>
            <li>6×03 — Smokey and the Bandit</li>
            <li>6×04 — A Horse of a Different Color</li>
            <li>6×05 — The Angel of Death</li>
            <li>6×06 — Just Let Go</li>
            <li>6×07 — Nebraska</li>
            <li>6×08 — Sin of Omission</li>
            <li>6×09 — Get Gellar</li>
            <li>6×10 — Ricochet Rabbit</li>
            <li>6×11 — Talk to the Hand</li>
            <li>6×12 — This Is the Way the World Ends</li>
          </ol>
        </div>
      </details>

      <!-- T7 -->
      <details>
        <summary>Temporada 7 <span class="tag">2012 • 12 eps</span></summary>
        <div class="episodes">
          <ol>
            <li>7×01 — Are You...?</li>
            <li>7×02 — Sunshine and Frosty Swirl</li>
            <li>7×03 — Buck the System</li>
            <li>7×04 — Run</li>
            <li>7×05 — Swim Deep</li>
            <li>7×06 — Do the Wrong Thing</li>
            <li>7×07 — Chemistry</li>
            <li>7×08 — Argentina</li>
            <li>7×09 — Helter Skelter</li>
            <li>7×10 — The Dark... Whatever</li>
            <li>7×11 — Do You See What I See?</li>
            <li>7×12 — Surprise, Motherfucker!</li>
          </ol>
        </div>
      </details>

      <!-- T8 -->
      <details>
        <summary>Temporada 8 <span class="tag">2013 • 12 eps</span></summary>
        <div class="episodes">
          <ol>
            <li>8×01 — A Beautiful Day</li>
            <li>8×02 — Every Silver Lining...</li>
            <li>8×03 — What’s Eating Dexter Morgan?</li>
            <li>8×04 — Scar Tissue</li>
            <li>8×05 — This Little Piggy</li>
            <li>8×06 — A Little Reflection</li>
            <li>8×07 — Dress Code</li>
            <li>8×08 — Are We There Yet?</li>
            <li>8×09 — Make Your Own Kind of Music</li>
            <li>8×10 — Goodbye Miami</li>
            <li>8×11 — Monkey in a Box</li>
            <li>8×12 — Remember the Monsters?</li>
          </ol>
        </div>
      </details>
    </section>

    <section id="contacto">
      <h2>Contacto de fans</h2>
      <form>
        <label for="nombre">Nombre</label>
        <input id="nombre" name="nombre" type="text" required>
        <label for="email">Correo</label>
        <input id="email" name="email" type="email" required>
        <label for="comentarios">Comentarios</label>
        <textarea id="comentarios" name="comentarios" rows="4" placeholder="Decime tu episodio favorito…"></textarea>
        <input type="submit" value="Enviar">
      </form>
    </section>
  </main>

  <footer>
    © 2025 Fan Page Dexter • Hecho para práctica de HTML + CSS
  </footer>
</body>
</html>
