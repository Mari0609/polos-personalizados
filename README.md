<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emprendimiento de Polos Personalizados</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Poppins', sans-serif;
            background: #0f0f0f;
            color: #fff;
            overflow-x: hidden;
        }

        /* HERO ANIMADO */
        header {
            height: 100vh;
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('banner.jpg') center/cover no-repeat;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
            animation: fadeIn 2s ease-in-out;
        }

        header h1 {
            font-size: 4rem;
            font-weight: 700;
            letter-spacing: 2px;
            animation: slideDown 2s;
        }

        header p {
            font-size: 1.5rem;
            margin-top: 15px;
            animation: fadeInUp 2.3s;
        }

        /* SECCIONES ANIMADAS */
        section {
            padding: 70px 10%;
            margin: 40px auto;
            background: #1a1a1a;
            border-radius: 20px;
            box-shadow: 0 0 20px rgba(255,255,255,0.05);
            animation: fadeInUp 1.5s;
        }

        h2 {
            font-size: 2.5rem;
            margin-bottom: 25px;
            text-transform: uppercase;
            letter-spacing: 2px;
            color: #ffcc00;
            animation: glow 2s infinite alternate;
        }

        .about, .mision, .vision {
            font-size: 1.2rem;
            line-height: 1.8;
            color: #ddd;
        }

        .mision, .vision {
            background: #222;
            padding: 30px;
            border-left: 10px solid #ffcc00;
            border-radius: 15px;
            box-shadow: 0 0 10px rgba(255,255,0,0.2);
        }

        footer {
            text-align: center;
            padding: 30px;
            background: #000;
            color: #fff;
            font-size: 1rem;
            margin-top: 40px;
        }

        /* ANIMACIONES */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes slideDown {
            from { transform: translateY(-50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }

        @keyframes fadeInUp {
            from { transform: translateY(50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }

        @keyframes glow {
            from { text-shadow: 0 0 10px #ffcc00; }
            to { text-shadow: 0 0 20px #ffe066; }
        }

        /* EFECTO FLOTANTE */
        .float {
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }

        /* BOTÓN WHATSAPP */
        .whatsapp {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: #25D366;
            color: white;
            padding: 18px;
            border-radius: 50%;
            font-size: 28px;
            text-decoration: none;
            box-shadow: 0 0 20px rgba(37,211,102,0.5);
            animation: zoomIn 1s;
        }

        @keyframes zoomIn {
            from { transform: scale(0.5); opacity: 0; }
            to { transform: scale(1); opacity: 1; }
        }
    </style>
</head>
<body>

    <header>
        <h1 class="float">Polos Personalizados</h1>
        <p>Dos jóvenes emprendedores creando estilo, identidad y creatividad para ti.</p>
    </header>

    <section>
        <h2>Quiénes Somos</h2>
        <p class="about">Somos dos jóvenes apasionados por el diseño, la moda y el emprendimiento. Nuestro proyecto nació con el sueño de demostrar que la creatividad y la dedicación pueden convertirse en un verdadero camino hacia el éxito. A pesar de las dificultades, hemos construido un emprendimiento sólido basado en esfuerzo, pasión y compromiso.<br><br>
        Cada polo que personalizamos lleva un mensaje, una emoción y un toque único. No solo vendemos prendas, creamos piezas que cuentan historias. Creemos en los sueños, en la juventud y en el poder de empezar desde cero con determinación.
        </p>
    </section>

    <section>
        <h2>Misión</h2>
        <div class="mision">
            Nuestra misión es ofrecer polos personalizados que reflejen la identidad y el estilo de cada persona. Queremos brindar un servicio cercano, amable y de alta calidad, convirtiendo cada diseño en una experiencia especial. Buscamos innovar constantemente y transmitir confianza, creatividad y profesionalismo en cada trabajo.
        </div>
    </section>

    <section>
        <h2>Visión</h2>
        <div class="vision">
            Aspiramos a posicionarnos como uno de los emprendimientos juveniles más destacados en personalización textil. Nuestra visión es expandirnos a nivel nacional, implementar nuevas tecnologías de diseño y crear una marca reconocida por su autenticidad, calidad y compromiso con cada cliente. Queremos inspirar a otros jóvenes a luchar por sus sueños.
        </div>
    </section>

    <a href="https://wa.me/51947079224?text=Hola%21%20Me%20gustar%C3%ADa%20informaci%C3%B3n%20sobre%20polos%20personalizados%2C%20modelos%2C%20precios%20y%20tiempos%20de%20entrega." class="whatsapp" target="_blank">💬</a>

    <footer>
        © 2025 Emprendimiento de Polos Personalizados - Todos los derechos reservados
    </footer>

</body>
</html>
