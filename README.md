<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>JSR Constructora e Inmobiliaria</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
    body { margin: 0; font-family: 'Poppins', sans-serif; }
    header {
        height: 100vh;
        background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)), url('https://images.unsplash.com/photo-1501854140801-50d01698950b?auto=format&fit=crop&w=3840&q=80');
        background-size: cover;
        background-position: center;
        color: #fff;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: center;
        padding: 20px;
    }
    h1 { font-size: 60px; margin: 0; }
    h2 { font-size: 36px; text-align:center; margin-top:60px; }
    p.sub { font-size: 20px; max-width: 700px; }
    .btn-primary {
        background: #ff7f0e;
        padding: 15px 30px;
        border: none;
        color: #fff;
        border-radius: 8px;
        font-size: 20px;
        cursor:pointer;
        margin-top: 25px;
        text-decoration:none;
    }
    .section {
        width: 90%; max-width: 1200px; margin: 80px auto;
    }
    .grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
        gap: 25px;
    }
    .card {
        padding: 25px;
        border-radius: 12px;
        background: #fff;
        box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        text-align:center;
    }
    footer {
        padding: 40px;
        text-align:center;
        background: #111;
        color: #ddd;
        margin-top:80px;
    }
    .wsp-btn {
        position: fixed;
        bottom: 20px;
        right: 20px;
        background: #25D366;
        color: white;
        padding: 16px 20px;
        border-radius: 50px;
        font-size: 18px;
        text-decoration: none;
        box-shadow: 0 4px 10px rgba(0,0,0,0.3);
    }
</style>
</head>
<body>
<header>
    <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAYGBgYHBgcICAcKCwoLCg8ODAwODxYQERAREBYiFRkVFRkVIh4kHhweJB42KiYmKjY+" style="max-width:220px;margin-bottom:25px;border-radius:12px;" />
    <h1>JSR Constructora</h1>
    <p class="sub">Construcción moderna, proyectos industriales, obras civiles y servicios inmobiliarios con altos estándares de calidad.</p>
    <a class="btn-primary" href="#cotizacion">Solicitar Cotización</a>
</header>

<section class="section">
    <h2>Servicios Profesionales</h2>
    <div class="grid">
        <div class="card"><h3>Construcción de Viviendas</h3><p>Proyectos completos con diseño moderno y alta resistencia.</p></div>
        <div class="card"><h3>Obras Civiles</h3><p>Infraestructura, urbanización y ampliaciones industriales.</p></div>
        <div class="card"><h3>Proyectos Industriales</h3><p>Galpones, montajes, plantas industriales y más.</p></div>
        <div class="card"><h3>Servicios Inmobiliarios</h3><p>Gestión, compra, venta y asesoría de propiedades.</p></div>
    </div>
</section>

<section class="section" id="cotizacion">
    <h2>Solicitar Cotización</h2>
    <form action="mailto:jsr.constructoraymontaje@gmail.com" method="post" enctype="text/plain">
        <input type="text" name="Nombre" placeholder="Nombre completo" required style="width:100%;padding:15px;margin:10px 0;border-radius:8px;border:1px solid #ccc;">
        <input type="email" name="Correo" placeholder="Correo electrónico" required style="width:100%;padding:15px;margin:10px 0;border-radius:8px;border:1px solid #ccc;">
        <input type="text" name="Telefono" placeholder="Teléfono" required style="width:100%;padding:15px;margin:10px 0;border-radius:8px;border:1px solid #ccc;">
        <textarea name="Detalles" rows="6" placeholder="Describe tu proyecto" required style="width:100%;padding:15px;margin:10px 0;border-radius:8px;border:1px solid #ccc;"></textarea>
        <button type="submit" class="btn-primary">Enviar Cotización</button>
    </form>
</section>

<a class="wsp-btn" href="https://wa.me/56975658697" target="_blank">WhatsApp</a>

<footer>
    © 2025 JSR Constructora e Inmobiliaria • Calidad y Confianza
</footer>

<!-- Sello de calidad con logo -->


</body>
</html>
