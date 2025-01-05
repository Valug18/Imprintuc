<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Imprintuc - Servicios 3D</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
            margin: 0;
        }

        header {
            background: linear-gradient(135deg, #002a5c, #00509e);
            color: white;
            padding: 20px 10px;
            text-align: center;
        }

        header img {
            width: 150px;
            margin-bottom: 15px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
        }

        header h1 {
            font-size: 2.8rem;
            margin: 10px 0;
            font-weight: bold;
        }

        header p {
            font-size: 1.3rem;
            font-weight: 300;
        }

        .container {
            max-width: 1100px;
            margin: 40px auto;
            padding: 0 20px;
            text-align: center;
        }

        h2 {
            font-size: 2rem;
            color: #002a5c;
            margin-bottom: 20px;
        }

        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .service {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .service:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 15px rgba(0, 0, 0, 0.2);
        }

        .service h3 {
            margin-bottom: 15px;
            color: #00509e;
            font-size: 1.5rem;
        }

        .service p {
            font-size: 1rem;
            color: #555;
        }

        footer {
            background: #002a5c;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
        }

        footer p {
            font-size: 0.9rem;
        }

        footer a {
            color: #f39c12;
            text-decoration: none;
            font-weight: bold;
        }

        footer a:hover {
            text-decoration: underline;
        }

        .cta {
            margin-top: 30px;
        }

        .cta a {
            display: inline-block;
            background: #00509e;
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            border-radius: 5px;
            font-size: 1.2rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: background 0.3s, transform 0.3s;
        }

        .cta a:hover {
            background: #002a5c;
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <header>
        <img src="imprintuc.jpg" alt="Imprintuc Logo">
        <h1>Imprintuc</h1>
        <p>Transformamos tus ideas en realidad con impresión 3D</p>
    </header>

    <div class="container">
        <section>
            <h2>Nuestros Servicios</h2>
            <div class="services">
                <div class="service">
                    <h3>Diseño 3D Personalizado</h3>
                    <p>Creación de modelos 3D adaptados a tus necesidades y especificaciones.</p>
                </div>
                <div class="service">
                    <h3>Impresión 3D</h3>
                    <p>Producción de piezas de alta calidad utilizando tecnología avanzada de impresión 3D.</p>
                </div>
                <div class="service">
                    <h3>Asesoramiento Técnico</h3>
                    <p>Te ayudamos a llevar a cabo tus proyectos con soluciones innovadoras y prácticas.</p>
                </div>
            </div>
        </section>

        <div class="cta">
            <a href="#">Contáctanos</a>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 Imprintuc. Todos los derechos reservados. <a href="#">Contáctanos</a></p>
    </footer>
</body>
</html>
