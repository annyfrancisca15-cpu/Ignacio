<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Dr. Ignacio Martínez Esteban — Clínica Dental</title>
  <meta name="description" content="Clínica dental del Dr. Ignacio Martínez Esteban — implantología, empastes, endodoncia, cirugías y estética dental. Reserva cita online." />
  <meta name="theme-color" content="#1E88E5" />
  <!-- SEO / Open Graph -->
  <meta property="og:title" content="Dr. Ignacio Martínez Esteban — Clínica Dental" />
  <meta property="og:description" content="Implantología, empastes, endodoncia y cirugías. Clínica moderna y trato cercano." />
  <meta property="og:image" content="<!-- URL imagen del doctor / logo -->" />
  <meta property="og:type" content="website" />

  <style>
    :root{
      --bg: #ffffff;
      --text: #1b2330;
      --muted: #6b7280;
      --blue-500: #1E88E5;    /* principal */
      --blue-700: #0f62a8;
      --accent: #7c4dff;      /* toque morado */
      --card: #f7fbff;
      --radius: 12px;
      --maxw: 1100px;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      background:var(--bg);
      color:var(--text);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.45;
    }

    /* Container */
    .wrap{max-width:var(--maxw); margin:0 auto; padding:24px;}

    /* Header / Nav */
    header.top {
      background: linear-gradient(180deg, rgba(30,136,229,0.06), transparent 40%);
      backdrop-filter: blur(4px);
      position:sticky; top:0; z-index:50;
      border-bottom: 1px solid rgba(28,50,75,0.04);
    }
    .nav {
      display:flex; align-items:center; justify-content:space-between;
      gap:16px; padding:14px 0;
    }
    .brand{display:flex; gap:12px; align-items:center; text-decoration:none; color:var(--text)}
    .logo{
      width:52px; height:52px; border-radius:10px;
      background:linear-gradient(135deg, var(--blue-500), var(--accent));
      display:flex; align-items:center; justify-content:center;
      color:white; font-weight:700; font-size:18px;
      box-shadow:0 6px 18px rgba(30,136,229,0.12);
    }
    .brand h1{font-size:16px;margin:0}
    nav.links{display:flex; gap:18px; align-items:center}
    nav.links a {text-decoration:none; color:var(--muted); font-weight:600; font-size:14px}
    .cta {background:var(--blue-500); color:white; padding:10px 14px; border-radius:10px; text-decoration:none; font-weight:700; display:inline-block}
    .cta.secondary {background:transparent; border:2px solid var(--blue-500); color:var(--blue-500)}

    /* Hero */
    .hero {
      display:grid; grid-template-columns: 1fr 420px; gap:30px; align-items:center;
      padding:36px 0 24px;
    }
    .hero .intro h2{margin:0 0 12px; font-size:30px}
    .lead {color:var(--muted); margin-bottom:18px}
    .hero .actions{display:flex; gap:12px; flex-wrap:wrap}
    .card-cta{
      background:linear-gradient(180deg, white, #f8fbff);
      border-radius:var(--radius);
      padding:18px; box-shadow:0 10px 30px rgba(15,38,70,0.06);
      border:1px solid rgba(15,38,70,0.03);
    }
    .doctor-photo {
      width:100%; height:100%; min-height:260px;
      border-radius:10px; background-size:cover; background-position:center;
      box-shadow:0 12px 30px rgba(7,37,90,0.06); border:1px solid rgba(7,37,90,0.04);
    }

    /* Services */
    .services {display:grid; grid-template-columns:repeat(3,1fr); gap:18px; margin:26px 0;}
    .service {
      background:var(--card); padding:18px; border-radius:12px; text-align:center;
      border:1px solid rgba(30,50,90,0.03);
    }
    .service svg{width:48px; height:48px; margin-bottom:12px}
    .service h3{margin:8px 0 6px; font-size:18px}
    .service p{color:var(--muted); font-size:14px}

    /* About */
    .about {display:flex; gap:22px; align-items:center; margin:28px 0}
    .about .text{flex:1}
    .badges {display:flex; gap:8px; margin-top:10px}
    .badge {background:#eef6ff; color:var(--blue-700); padding:8px 12px; border-radius:999px; font-weight:700; font-size:13px}

    /* Testimonials */
    .testimonials {display:grid; grid-template-columns:repeat(3,1fr); gap:14px; margin:22px 0}
    .testimonial {background:white; padding:16px; border-radius:12px; border:1px solid rgba(10,20,40,0.04)}
    .testimonial p{color:var(--muted); margin:8px 0 0}
    .testi-meta{display:flex; gap:10px; align-items:center; margin-top:12px}

    /* Gallery */
    .gallery {display:grid; grid-template-columns:repeat(4,1fr); gap:10px; margin:18px 0}
    .gallery img{width:100%; height:110px; object-fit:cover; border-radius:8px}

    /* Contact */
    .contact {
      display:grid; grid-template-columns: 1fr 420px; gap:20px; margin:30px 0 70px;
    }
    .contact .info {padding:20px; background:linear-gradient(180deg,#f8fbff,#ffffff); border-radius:12px; border:1px solid rgba(10,30,70,0.03)}
    .contact form {display:flex; flex-direction:column; gap:10px}
    input, textarea, select {
      padding:12px 14px; border-radius:10px; border:1px solid #e6eefb; font-size:14px;
    }
    button[type="submit"]{background:linear-gradient(90deg,var(--blue-500),var(--blue-700)); color:white; border:none; padding:12px 14px; border-radius:10px; font-weight:700}

    footer {text-align:center; padding:28px 0; color:var(--muted); border-top:1px solid rgba(15,30,50,0.04)}

    /* Floating CTA */
    .float-cta {
      position:fixed; right:18px; bottom:18px; z-index:80;
      display:flex; gap:10px; flex-direction:column;
    }
    .float-cta a {
      display:inline-flex; align-items:center; gap:10px; text-decoration:none; color:white;
      background:linear-gradient(90deg,var(--accent),var(--blue-500)); padding:12px 14px; border-radius:14px; box-shadow:0 8px 22px rgba(124,77,255,0.14);
      font-weight:800;
    }

    /* Responsive */
    @media (max-width:1000px){
      .hero, .contact {grid-template-columns: 1fr;}
      .services {grid-template-columns:repeat(2,1fr)}
      .testimonials {grid-template-columns:repeat(2,1fr)}
      .gallery {grid-template-columns:repeat(3,1fr)}
    }
    @media (max-width:640px){
      .services {grid-template-columns:1fr}
      .testimonials {grid-template-columns:1fr}
      .gallery {grid-template-columns:repeat(2,1fr)}
      .brand h1{font-size:15px}
    }

    /* Small helper */
    .muted{color:var(--muted)}
  </style>
</head>
<body>

  <!-- HEADER / NAV -->
  <header class="top">
    <div class="wrap nav">
      <a class="brand" href="#">
        <div class="logo" aria-hidden="true">IM</div>
        <div>
          <h1>Dr. Ignacio Martínez Esteban</h1>
          <div class="muted" style="font-size:13px">Clínica dental • Implantología & Estética</div>
        </div>
      </a>

      <nav class="links" aria-label="Menú principal">
        <a href="#servicios">Servicios</a>
        <a href="#sobre">Sobre mí</a>
        <a href="#testimonios">Testimonios</a>
        <a href="#contacto" class="cta">Reservar cita</a>
      </nav>
    </div>
  </header>

  <!-- HERO -->
  <main class="wrap">
    <section class="hero" aria-labelledby="hero-title">
      <div class="intro">
        <h2 id="hero-title">Tu salud dental en manos expertas — trato cercano y resultados</h2>
        <p class="lead">El Dr. Ignacio Martínez Esteban combina tecnología avanzada con atención personalizada: implantología, empastes, endodoncia, cirugías y estética dental.</p>
        <div class="hero-buttons">
          <div class="hero-actions">
            <a href="#contacto" class="cta">Reservar cita</a>
            <!-- WhatsApp direct link (CAMBIAR NÚMERO) -->
            <a class="cta secondary" href="https://wa.me/34XXXXXXXXX?text=Hola%20Dr.%20Ignacio%20,%20quiero%20pedir%20cita" target="_blank" rel="noopener">WhatsApp</a>
          </div>
        </div>

        <div style="margin-top:18px; max-width:680px;">
          <div class="card-cta" role="region" aria-label="Resumen de servicios">
            <strong>Servicios destacados:</strong>
            <div style="display:flex; gap:10px; margin-top:8px; flex-wrap:wrap;">
              <span class="badge">Implantología</span>
              <span class="badge">Endodoncia</span>
              <span class="badge">Empastes</span>
              <span class="badge">Cirugía oral</span>
              <span class="badge">Estética dental</span>
            </div>
          </div>
        </div>
      </div>

      <aside class="card-cta" aria-label="Foto del doctor">
        <div class="doctor-photo" style="background-image:url('<!-- URL FOTO DOCTOR / CAMBIAR -->');">
          <!-- Si no hay foto: mostrar iniciales -->
        </div>
      </aside>
    </section>

    <!-- SERVICES -->
    <section id="servicios">
      <div style="display:flex; justify-content:space-between; align-items:center;">
        <h2>Servicios</h2>
        <p class="muted">Tratamientos modernos y personalizados</p>
      </div>

      <div class="services" role="list">
        <article class="service" role="listitem">
          <!-- Implant SVG -->
          <svg viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M12 2v6" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/><path d="M7 18h10" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/><path d="M9 8h6v10H9z" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/></svg>
          <h3>Implantología</h3>
          <p>Implantes con tecnología 3D y planificación digital para resultados previsibles y duraderos.</p>
        </article>

        <article class="service" role="listitem">
          <svg viewBox="0 0 24 24" fill="none"><path d="M12 3v18" stroke="currentColor" stroke-width="1.6" stroke-linecap="round"/><path d="M3 12h18" stroke="currentColor" stroke-width="1.6" stroke-linecap="round"/></svg>
          <h3>Endodoncia</h3>
          <p>Tratamientos de conducto con microscopia y materiales de última generación.</p>
        </article>

        <article class="service" role="listitem">
          <svg viewBox="0 0 24 24" fill="none"><path d="M4 21v-6a8 8 0 0116 0v6" stroke="currentColor" stroke-width="1.6" stroke-linecap="round"/></svg>
          <h3>Cirugías orales</h3>
          <p>Cirugías mínimamente invasivas con anestesia local y sedación si es necesario.</p>
        </article>

        <article class="service" role="listitem">
          <svg viewBox="0 0 24 24" fill="none"><path d="M12 2l2 4 4 .5-3 2.8.7 4-3.7-2-3.7 2 .7-4L6 6.5 10 6l2-4z" stroke="currentColor" stroke-width="1.2"/></svg>
          <h3>Empastes & Restauraciones</h3>
          <p>Empastes estéticos y conservadores que recuperan función y forma.</p>
        </article>

        <article class="service" role="listitem">
          <svg viewBox="0 0 24 24" fill="none"><path d="M6 12h12" stroke="currentColor" stroke-width="1.6"/><path d="M12 6v12" stroke="currentColor" stroke-width="1.6"/></svg>
          <h3>Estética dental</h3>
          <p>Blanqueamiento, carillas y diseño de sonrisa para resultados naturales.</p>
        </article>

        <article class="service" role="listitem">
          <svg viewBox="0 0 24 24" fill="none"><path d="M3 12h4l3 8 4-16 3 8h4" stroke="currentColor" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round"/></svg>
          <h3>Urgencias dentales</h3>
          <p>Atención rápida para dolor, fracturas o problemas agudos.</p>
        </article>
      </div>
    </section>

    <!-- ABOUT -->
    <section id="sobre" class="about" aria-labelledby="sobre-title">
      <div class="text">
        <h2 id="sobre-title">Sobre el Dr. Ignacio Martínez Esteban</h2>
        <p class="muted">El Dr. Ignacio Martínez Esteban es especialista en implantología y cirugía oral con más de X años de experiencia. Su filosofía combina precisión clínica, tecnología digital (CBCT, escáner intraoral) y un trato humano y cercano para que cada paciente reciba el plan más adecuado.</p>
        <div class="badges" aria-hidden="true">
          <span class="badge">Formación avalada</span>
          <span class="badge">Tecnología 3D</span>
          <span class="badge">Trato personalizado</span>
        </div>
        <p style="margin-top:12px">Puedes incluir aquí la formación, asociaciones y un currículo breve. Ej: Licenciado en Odontología — Universidad X. Máster en Implantología — Universidad Y.</p>
      </div>

      <div style="min-width:260px">
        <div style="background:#fff; padding:14px; border-radius:12px; border:1px solid rgba(10,20,40,0.03)">
          <strong>Horarios</strong>
          <p class="muted" style="margin:6px 0 0">Lunes a Viernes — 9:00 a 19:00<br>Sábados — 9:00 a 13:00 (consultar)</p>
          <div style="margin-top:12px">
            <a class="cta" href="#contacto">Pedir cita</a>
          </div>
        </div>
      </div>
    </section>

    <!-- TESTIMONIALS -->
    <section id="testimonios">
      <h2>Testimonios</h2>
      <div class="testimonials">
        <article class="testimonial">
          <p>"Excelente trato y profesionalidad. Me pusieron un implante y el resultado fue perfecto." </p>
          <div class="testi-meta">
            <div style="width:44px; height:44px; border-radius:44px; background:linear-gradient(90deg,var(--blue-500),var(--accent)); color:white; display:flex; align-items:center; justify-content:center">A</div>
            <div>
              <strong>Ana M.</strong><br><span class="muted" style="font-size:13px">Paciente</span>
            </div>
          </div>
        </article>

        <article class="testimonial">
          <p>"Trato muy cercano y me explicaron todo. La endodoncia fue indolora y rápida."</p>
          <div class="testi-meta">
            <div style="width:44px; height:44px; border-radius:44px; background:#e9f3ff; display:flex; align-items:center; justify-content:center">S</div>
            <div><strong>Sergio L.</strong><br><span class="muted" style="font-size:13px">Paciente</span></div>
          </div>
        </article>

        <article class="testimonial">
          <p>"Clínica moderna y bien equipada. Volvería sin duda."</p>
          <div class="testi-meta">
            <div style="width:44px; height:44px; border-radius:44px; background:#f6eefb; display:flex; align-items:center; justify-content:center">M</div>
            <div><strong>Marta R.</strong><br><span class="muted" style="font-size:13px">Paciente</span></div>
          </div>
        </article>
      </div>
    </section>

    <!-- GALLERY -->
    <section aria-label="Galería">
      <h2>Galería</h2>
      <div class="gallery" role="list">
        <img src="<!-- IMG 1 URL -->" alt="Sala de espera" />
        <img src="<!-- IMG 2 URL -->" alt="Quirófano" />
        <img src="<!-- IMG 3 URL -->" alt="Equipo dental" />
        <img src="<!-- IMG 4 URL -->" alt="Sonrisa paciente" />
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contacto" class="contact" aria-labelledby="contacto-title">
      <div class="info">
        <h2 id="contacto-title">Contacto & Reserva</h2>
        <p class="muted">Rellena el formulario o llámanos / escríbenos por WhatsApp.</p>

        <p style="margin:14px 0"><strong>Dirección:</strong> Calle Ejemplo 123, Ciudad. <!-- CAMBIAR --> </p>
        <p style="margin:6px 0"><strong>Teléfono:</strong> <a href="tel:+34XXXXXXXXX">+34 XXXXXXXXX</a> <!-- CAMBIAR --></p>
        <p style="margin:6px 0"><strong>Correo:</strong> <a href="mailto:info@clinicaejemplo.com">info@clinicaejemplo.com</a> <!-- CAMBIAR --></p>

        <div style="margin-top:12px">
          <!-- Insertar iframe Google Maps real reemplazando la src por la de la clínica -->
          <div style="width:100%; height:180px; border-radius:10px; overflow:hidden; border:1px solid rgba(10,20,40,0.03)">
            <iframe src="<!-- URL EMBED GOOGLE MAPS AQUÍ -->" width="100%" height="180" style="border:0" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
          </div>
        </div>
      </div>

      <form id="bookingForm" onsubmit="submitForm(event)" aria-label="Formulario de reserva">
        <input type="text" id="name" name="name" placeholder="Nombre completo" required />
        <input type="tel" id="phone" name="phone" placeholder="Teléfono" required />
        <input type="email" id="email" name="email" placeholder="Correo electrónico" />
        <label for="service" class="muted">Tratamiento</label>
        <select id="service" name="service" required>
          <option value="">Selecciona un servicio</option>
          <option>Implantología</option>
          <option>Endodoncia</option>
          <option>Empaste / Restauración</option>
          <option>Cirugía oral</option>
          <option>Estética / Blanqueamiento</option>
          <option>Consulta general</option>
        </select>
        <textarea id="notes" name="notes" rows="3" placeholder="Comentario / Mejor franja horaria"></textarea>

        <!-- Nota: por defecto el formulario hace POST a Formspree (gratuito para pruebas).
             Cambia 'YOUR_FORMSPREE_ENDPOINT' por tu endpoint real o integra con tu CRM. -->
        <input type="hidden" name="_subject" value="Nueva reserva - Web Clínica"/>
        <button type="submit">Solicitar cita</button>
        <p id="formMsg" class="muted" style="font-size:14px; margin-top:8px; display:none"></p>
      </form>
    </section>

    <footer>
      © <span id="year"></span> Dr. Ignacio Martínez Esteban — Clínica dental. Todos los derechos reservados.
    </footer>
  </main>

  <!-- FLOATING CTA -->
  <div class="float-cta" aria-hidden="true">
    <a href="tel:+34XXXXXXXXX" title="Llamar">📞 Llamar</a>
    <a href="https://wa.me/34XXXXXXXXX?text=Hola%20Dr.%20Ignacio%20,%20quiero%20pedir%20cita" target="_blank">💬 WhatsApp</a>
  </div>

  <script>
    // Añadir año en footer
    document.getElementById('year').textContent = new Date().getFullYear();

    // Form submit: ejemplo usando fetch a Formspree (sustituir endpoint)
    async function submitForm(e){
      e.preventDefault();
      const form = document.getElementById('bookingForm');
      const msg = document.getElementById('formMsg');
      msg.style.display = 'none';
      const data = new FormData(form);

      // Reemplaza por tu endpoint (Formspree, Zapier webhook, tu API, etc.)
      const endpoint = 'https://formspree.io/f/YOUR_FORMSPREE_ENDPOINT'; // <-- CAMBIAR

      try {
        const res = await fetch(endpoint, {
          method: 'POST',
          body: data,
          headers: { 'Accept': 'application/json' }
        });
        if (res.ok) {
          msg.style.color = 'green';
          msg.textContent = '¡Gracias! Tu solicitud se ha enviado. Te contactaremos pronto.';
          msg.style.display = 'block';
          form.reset();
        } else {
          const json = await res.json();
          msg.style.color = 'crimson';
          msg.textContent = json.error || 'Error enviando el formulario. Intenta por WhatsApp o teléfono.';
          msg.style.display = 'block';
        }
      } catch (err) {
        msg.style.color = 'crimson';
        msg.textContent = 'Error de red. Intenta de nuevo o contacta por WhatsApp.';
        msg.style.display = 'block';
      }
    }
  </script>
</body>
</html>
