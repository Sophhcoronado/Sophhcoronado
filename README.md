<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nombre de la Empresa</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            display: flex;
        }
        header {
            background: linear-gradient(to right, #007BFF, #0056b3);
            color: white;
            padding: 2rem 0;
            text-align: center;
            width: 100%;
        }
        header h1 {
            font-size: 3rem;
            margin: 0;
        }
        header p {
            font-size: 1.2rem;
            margin-top: 10px;
        }
        nav {
            background-color: #0056b3;
            width: 250px;
            min-height: 100vh;
            padding-top: 20px;
        }
        nav a {
            color: white;
            text-decoration: none;
            display: block;
            padding: 10px 20px;
            font-size: 1.1rem;
            margin: 5px 0;
            transition: background-color 0.3s ease;
        }
        nav a:hover {
            background-color: #007BFF;
            border-radius: 5px;
        }
        main {
            flex-grow: 1;
            padding: 20px;
        }
        section {
            max-width: 1000px;
            margin: 30px auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        section h2 {
            font-size: 2rem;
            margin-bottom: 15px;
            color: #007BFF;
        }
        section p {
            font-size: 1.1rem;
            line-height: 1.6;
        }
        img {
            max-width: 100%;
            height: auto;
            margin: 20px 0;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #0056b3;
            color: white;
            text-align: center;
            padding: 15px 0;
        }
        footer p {
            margin: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Nombre de la Empresa</h1>
        <p>Bienvenidos a nuestra página web oficial</p>
    </header>

    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#mision">Misión</a>
        <a href="#vision">Visión</a>
        <a href="#servicios">Servicios</a>
        <a href="https://www.facebook.com" target="_blank">Facebook</a>
        <a href="https://www.twitter.com" target="_blank">Twitter</a>
        <a href="https://www.linkedin.com" target="_blank">LinkedIn</a>
        <a href="https://www.instagram.com" target="_blank">Instagram</a>
    </nav>

    <main>
        <section id="inicio">
            <h2>Inicio</h2>
            <p>En Nombre de la Empresa, estamos comprometidos con ofrecer soluciones innovadoras y de alta calidad que cumplan con las expectativas de nuestros clientes. Nuestra trayectoria de éxito se basa en el esfuerzo y la dedicación de nuestro equipo, siempre enfocados en la excelencia.</p>
            <img src="https://via.placeholder.com/900x300" alt="Imagen representativa del inicio">
        </section>

        <section id="mision">
            <h2>Misión</h2>
            <p>Nuestra misión es brindar servicios excepcionales que permitan a nuestros clientes alcanzar sus metas y superar sus desafíos. Trabajamos con pasión y dedicación para garantizar los más altos estándares de calidad.</p>
            <img src="https://via.placeholder.com/600x300" alt="Imagen representativa de la misión">
        </section>

        <section id="vision">
            <h2>Visión</h2>
            <p>Aspiramos a ser una empresa líder en nuestro sector, reconocida por nuestra innovación, ética profesional y compromiso con el crecimiento sostenible. Queremos marcar una diferencia en el mercado global con soluciones vanguardistas.</p>
            <img src="https://via.placeholder.com/600x300" alt="Imagen representativa de la visión">
        </section>

        <section id="servicios">
            <h2>Servicios</h2>
            <p>Ofrecemos una variedad de servicios diseñados para satisfacer las necesidades de nuestros clientes:</p>
            <ul>
                <li>Consultoría especializada en desarrollo de negocios</li>
                <li>Diseño y desarrollo de sitios web</li>
                <li>Marketing digital y gestión de redes sociales</li>
                <li>Optimización de procesos empresariales</li>
            </ul>
            <img src="https://via.placeholder.com/800x400" alt="Imagen representativa de los servicios">
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Nombre de la Empresa. Todos los derechos reservados.</p>
    </footer>

</body>
</html>
