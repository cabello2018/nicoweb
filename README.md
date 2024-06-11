# nicoweb<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nicolás Cabello - Consultor en Higiene y Seguridad</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #333;
        }
        header {
            background-color: #002f6c;
            color: white;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            margin: 5px 0 0;
            font-size: 1.2em;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #0056b3;
            padding: 15px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            transition: color 0.3s ease;
        }
        nav a:hover {
            color: #ffc107;
        }
        section {
            padding: 40px 20px;
            margin: 20px auto;
            width: 80%;
            max-width: 1200px;
            background-color: white;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #002f6c;
            margin-bottom: 20px;
        }
        footer {
            background-color: #002f6c;
            color: white;
            text-align: center;
            padding: 20px 0;
            box-shadow: 0 -2px 4px rgba(0, 0, 0, 0.1);
            position: relative;
            bottom: 0;
            width: 100%;
        }
        footer p {
            margin: 0;
        }
        img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 20px 0;
            border-radius: 8px;
        }
        .content {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .content img {
            width: 48%;
            margin: 10px 0;
        }
        @media (max-width: 768px) {
            section {
                width: 90%;
            }
            .content img {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Nicolás Cabello</h1>
        <p>Consultor y Asesor en Higiene y Seguridad</p>
    </header>
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#sobre-mi">Sobre Mí</a>
        <a href="#proyectos">Proyectos</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <section id="inicio">
        <h2>Inicio</h2>
        <div class="content">
            <img src="https://via.placeholder.com/800x400?text=Industria" alt="Imagen de Industria">
            <p>Bienvenido a mi página personal. Aquí podrás conocer más sobre mi trabajo como consultor y asesor en higiene y seguridad laboral.</p>
        </div>
    </section>
    <section id="sobre-mi">
        <h2>Sobre Mí</h2>
        <div class="content">
            <img src="https://via.placeholder.com/800x400?text=Consultoría" alt="Imagen de Consultoría">
            <p>Hola, soy Nicolás Cabello, licenciado en higiene y seguridad laboral, residente de Tucumán, Argentina. Me especializo en brindar consultoría y asesoría en higiene y seguridad para diversas empresas. Mi objetivo es garantizar entornos laborales seguros y cumplir con las normativas vigentes. Puedes conocer más sobre mi perfil profesional en <a href="https://www.linkedin.com/in/nicolas-cabello-535384298/" target="_blank">LinkedIn</a>.</p>
        </div>
    </section>
    <section id="proyectos">
        <h2>Proyectos</h2>
        <div class="content">
            <img src="https://via.placeholder.com/800x400?text=Proyectos+Industriales" alt="Imagen de Proyectos Industriales">
            <p>Aquí podrás ver algunos de los proyectos en los que he trabajado a lo largo de mi carrera, implementando soluciones de higiene y seguridad efectivas.</p>
        </div>
    </section>
    <section id="contacto">
        <h2>Contacto</h2>
        <div class="content">
            <img src="https://via.placeholder.com/800x400?text=Contacto" alt="Imagen de Contacto">
            <p>Para consultas profesionales, puedes contactarme a través de mi correo electrónico: <a href="mailto:nicolas.cabello@example.com">nicolas.cabello@example.com</a>.</p>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 Nicolás Cabello. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
