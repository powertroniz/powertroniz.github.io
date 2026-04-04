<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>POWERTRONIZ | Servicio Técnico</title>
    <style>
        /* --- ESTILOS GENERALES --- */
        :root {
            --primary-orange: #ff9900;
            --primary-yellow: #ffcc00;
            --background-dark: #121212;
            --text-light: #e0e0e0;
            --card-bg: #1e1e1e;
            --accent-green: #2ecc71;
            --hover-orange: #e68a00;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            background-color: var(--background-dark);
            color: var(--text-light);
            line-height: 1.6;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* --- CABECERA --- */
        header {
            background: linear-gradient(135deg, var(--primary-orange) 0%, #ff6600 100%);
            padding: 50px 0;
            text-align: center;
            border-bottom: 5px solid var(--primary-yellow);
        }

        .logo-container {
            width: 150px;
            height: 150px;
            margin: 0 auto;
            border-radius: 50%;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0,0,0,0.4);
            background-color: white;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .logo-img {
            max-width: 90%;
            height: auto;
        }

        header h1 {
            color: white;
            font-size: 3rem;
            margin-top: 20px;
            margin-bottom: 5px;
            text-transform: uppercase;
            letter-spacing: 3px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }

        header p {
            color: white;
            font-size: 1.2rem;
            margin: 0;
            opacity: 0.9;
        }

        /* --- SECCIÓN DESCRIPCIÓN --- */
        .description-section {
            padding: 60px 0;
            text-align: center;
        }

        .description-section h2 {
            font-size: 2.5rem;
            color: var(--primary-yellow);
            margin-bottom: 20px;
        }

        .description-text {
            font-size: 1.2rem;
            max-width: 800px;
            margin: 0 auto;
            margin-bottom: 40px;
        }

        /* --- SERVICIOS --- */
        .services-section {
            padding: 60px 0;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .service-card {
            background-color: var(--card-bg);
            border: 2px solid transparent;
            border-radius: 12px;
            padding: 30px;
            transition: all 0.3s ease;
        }

        .service-card:hover {
            border-color: var(--primary-yellow);
            transform: translateY(-5px);
        }

        .service-card h3 {
            color: var(--primary-orange);
            font-size: 1.5rem;
            margin-bottom: 15px;
        }

        .service-list {
            list-style: none;
            padding: 0;
        }

        .service-list li {
            margin-bottom: 12px;
            display: flex;
            align-items: center;
        }

        .check-icon {
            color: var(--accent-green);
            margin-right: 10px;
            font-weight: bold;
        }

        /* --- BOTÓN WHATSAPP FLOTANTE --- */
        .wa-float {
            position: fixed;
            width: 70px;
            height: 70px;
            bottom: 30px;
            right: 30px;
            background-color: #25d366;
            color: white;
            border-radius: 50px;
            text-align: center;
            font-size: 30px;
            box-shadow: 2px 5px 15px rgba(0,0,0,0.3);
            z-index: 10000;
            display: flex;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            transition: 0.3s;
        }

        .wa-float:hover {
            transform: scale(1.1);
            background-color: #128c7e;
        }

        footer {
            background-color: #000;
            padding: 30px 0;
            text-align: center;
            border-top: 3px solid var(--primary-orange);
        }
    </style>
</head>
<body>

<header>
    <div class="container">
        <div class="logo-container">
            <img src="logo.jpg" alt="Powertroniz Logo" class="logo-img">
        </div>
        <h1>POWERTRONIZ</h1>
        <p>Servicio Técnico de Televisores</p>
    </div>
</header>

<section class="description-section">
    <div class="container">
        <h2>Expertos en TV a Domicilio</h2>
        <p class="description-text">
            Reparaciones profesionales con garantía: LG, SAMSUNG y más. 
            Atención en **todo Villa El Salvador y Lima**.
        </p>
    </div>
</section>

<section class="services-section">
    <div class="container">
        <div class="services-grid">
            <div class="service-card">
                <h3>Solucionamos Cualquier Falla</h3>
                <ul class="service-list">
                    <li><span class="check-icon">&#10003;</span> IMÁGENES AZULES</li>
                    <li><span class="check-icon">&#10003;</span> PUNTOS BLANCOS</li>
                    <li><span class="check-icon">&#10003;</span> RAYAS EN PANTALLA</li>
                </ul>
            </div>
        </div>
    </div>
</section>

<a href="https://wa.me/51999999999?text=Hola%20Powertroniz" class="wa-float" target="_blank">
    <svg width="40" height="40" viewBox="0 0 24 24" fill="white">
        <path d="M12.031 6.172c-2.32 0-4.591.899-6.393 2.505-3.906 3.48-4.009 9.397-.233 13.003l-1.072 3.907 4.072-1.054c1.11.583 2.348.889 3.611.891h.005c4.605 0 8.323-3.713 8.325-8.318a8.31 8.31 0 0 0-8.315-8.334zm5.411 11.547c-.223.633-1.29 1.166-1.776 1.233-.487.067-.974.067-2.906-.699-2.28-.904-3.722-3.197-3.836-3.348-.114-.151-.93-1.227-.93-2.34s.583-1.661.79-1.89c.207-.229.451-.286.6-.286h.423c.135 0 .315-.051.488.35.188.437.633 1.542.688 1.654.055.113.09.245.015.396-.075.151-.113.245-.226.377-.113.131-.237.293-.338.396-.102.102-.207.214-.09.414.117.2 1.517 2.457 2.76 3.56 1.13 1.002 2.083 1.312 2.376 1.458.293.146.463.123.636-.075.173-.197.744-.863.944-1.157.202-.294.404-.245.674-.146.27.098 1.71.807 2.003.955.293.148.488.221.558.341.071.121.071.696-.152 1.329z"/>
    </svg>
</a>

<footer>
    <div class="container">
        <p>&copy; 2026 POWERTRONIZ. Todos los derechos reservados.</p>
    </div>
</footer>

</body>
</html>
