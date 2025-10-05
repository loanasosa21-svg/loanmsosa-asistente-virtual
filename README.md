<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LoanMsosa | Asistente Virtual</title>

    <!-- Meta tag de Google AdSense -->
    <meta name="google-adsense-account" content="ca-pub-6975819935922747">

    <!-- Script de Google AdSense para anuncios automáticos -->
    <script data-ad-client="ca-pub-6975819935922747" async
        src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>

    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* Reset y tipografía */
        * { margin:0; padding:0; box-sizing:border-box; font-family: 'Roboto', sans-serif; }
        body { line-height:1.6; color:#333; background:#fdfdfd; }

        /* Contenedor general */
        .container { width:90%; max-width:1100px; margin:auto; padding:20px; }

        /* Header */
        header { display:flex; justify-content:space-between; align-items:center; padding:20px 0; }
        header h1 { color:#222; }
        nav a { margin-left:20px; text-decoration:none; color:#333; font-weight:500; }
        nav a:hover { color:#007BFF; }

        /* Secciones */
        section { padding:60px 0; }
        h2 { color:#222; margin-bottom:20px; font-size:2em; }

        /* Inicio */
        .hero { text-align:center; padding:100px 20px; background:#f5f5f5; }
        .hero h1 { font-size:2.5em; margin-bottom:20px; }
        .hero p { font-size:1.2em; margin-bottom:30px; }

        /* Botón */
        .btn { background:#007BFF; color:#fff; padding:12px 25px; border:none; border-radius:5px; cursor:pointer; text-decoration:none; }
        .btn:hover { background:#0056b3; }

        /* Servicios */
        .services { display:grid; grid-template-columns:repeat(auto-fit,minmax(250px,1fr)); gap:20px; }
        .service-box { background:#fff; padding:20px; border-radius:8px; box-shadow:0 2px 5px rgba(0,0,0,0.1); text-align:center; }
        .service-box h3 { margin-bottom:10px; color:#007BFF; }

        /* Sobre mí */
        .about { display:flex; flex-wrap:wrap; align-items:center; gap:20px; }
        .about img { flex:1 1 300px; max-width:300px; border-radius:50%; }
        .about .text { flex:2 1 400px; }

        /* Testimonios */
        .testimonials { display:grid; grid-template-columns:repeat(auto-fit,minmax(250px,1fr)); gap:20px; }
        .testimonial-box { background:#f5f5f5; padding:20px; border-radius:8px; font-style:italic; }

        /* Contacto */
        form { display:flex; flex-direction:column; gap:15px; max-width:500px; margin:auto; }
        input, textarea { padding:10px; border:1px solid #ccc; border-radius:5px; }
        input:focus, textarea:focus { outline:none; border-color:#007BFF; }

        /* Footer */
        footer { text-align:center; padding:30px 0; background:#f5f5f5; margin-top:40px; color:#555; }
    </style>
</head>
<body>

    <!-- Header -->
    <header class="container">
        <h1>LoanMsosa</h1>
        <nav>
            <a href="#inicio">Inicio</a>
            <a href="#servicios">Servicios</a>
            <a href="#sobre-mi">Sobre mí</a>
            <a href="#testimonios">Testimonios</a>
            <a href="#contacto">Contacto</a>
        </nav>
    </header>

    <!-- Inicio -->
    <section id="inicio" class="hero">
        <h1>Tu Asistente Virtual Profesional</h1>
        <p>Ayudo a emprendedores y empresas a gestionar tareas administrativas y digitales para ahorrar tiempo y aumentar productividad.</p>
        <a href="#contacto" class="btn">Contratame</a>
    </section>

    <!-- Servicios -->
    <section id="servicios" class="container">
        <h2>Servicios</h2>
        <div class="services">
            <div class="service-box">
                <h3>Gestión de emails</h3>
                <p>Organizo y respondo tus correos electrónicos eficientemente, manteniendo todo bajo control.</p>
            </div>
            <div class="service-box">
                <h3>Redes Sociales</h3>
                <p>Creo contenido y gestiono tus redes sociales para mantener presencia online profesional.</p>
            </div>
            <div class="service-box">
                <h3>Asistencia administrativa</h3>
                <p>Manejo agendas, facturación y tareas administrativas para que puedas enfocarte en lo importante.</p>
            </div>
        </div>
    </section>

    <!-- Sobre mí -->
    <section id="sobre-mi" class="container about">
        <img src="https://via.placeholder.com/300" alt="Foto de Loana Sosa">
        <div class="text">
            <h2>Sobre mí</h2>
            <p>Soy Loana Sosa, asistente virtual apasionada por la organización y la productividad. Me especializo en ayudar a emprendedores y pequeñas empresas a ahorrar tiempo y mejorar su eficiencia mediante la gestión digital y administrativa.</p>
        </div>
    </section>

    <!-- Testimonios -->
    <section id="testimonios" class="container">
        <h2>Testimonios</h2>
        <div class="testimonials">
            <div class="testimonial-box">
                "Loana es increíble, me ayudó a organizar todo mi negocio online. ¡Super recomendable!" - Cliente A
            </div>
            <div class="testimonial-box">
                "Gracias a Loana, pude enfocarme en crecer mi empresa mientras ella manejaba las tareas diarias." - Cliente B
            </div>
        </div>
    </section>

    <!-- Contacto -->
    <section id="contacto" class="container">
        <h2>Contacto</h2>
        <form action="mailto:Loanasosa21@gmail.com" method="post" enctype="text/plain">
            <input type="text" name="nombre" placeholder="Tu nombre" required>
            <input type="email" name="email" placeholder="Tu email" required>
            <textarea name="mensaje" rows="5" placeholder="Tu mensaje" required></textarea>
            <input type="submit" value="Enviar" class="btn">
        </form>
    </section>

    <!-- Footer -->
    <footer>
        &copy; 2025 LoanMsosa | Asistente Virtual | Email: Loanasosa21@gmail.com
    </footer>

</body>
</html>
