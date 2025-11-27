<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Operación Kay La</title>
    <style>
        /* Reset and base styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #ffffff;
        }
        a {
            text-decoration: none;
            color: inherit;
        }
        ul {
            list-style: none;
        }

        /* Navbar */
        .navbar {
            position: fixed;
            top: 0;
            width: 100%;
            background-color: #007bff;
            color: white;
            padding: 1rem;
            z-index: 1000;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .navbar .container {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .navbar .logo {
            font-size: 1.5rem;
            font-weight: bold;
        }
        .navbar ul {
            display: flex;
        }
        .navbar li {
            margin-left: 2rem;
        }
        .navbar a {
            transition: color 0.3s;
        }
        .navbar a:hover {
            color: #cce7ff;
        }

        /* Sections */
        section {
            padding: 5rem 2rem 2rem; /* Adjusted for fixed navbar */
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            text-align: center;
        }
        h1, h2 {
            margin-bottom: 1rem;
            color: #007bff;
        }
        p {
            margin-bottom: 1rem;
            color: #666;
        }

        /* Home */
        #home {
            background-color: #e3f2fd; /* Light blue for more color */
        }
        #home h1 {
            font-size: 3rem;
        }
        #home .slogan {
            font-size: 1.5rem;
            color: #007bff;
        }

        /* About */
        #about {
            background-color: #ffffff;
        }
        .pillars {
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
            justify-content: center;
            margin-top: 2rem;
        }
        .pillar {
            background-color: #f1f8e9; /* Light green for variety */
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            flex: 1 1 300px;
            max-width: 350px;
        }
        .pillar h3 {
            color: #007bff;
            margin-bottom: 1rem;
        }

        /* Context */
        #context {
            background-color: #fff3e0; /* Light orange for more color */
        }
        #context .content {
            max-width: 800px;
            margin: 0 auto;
            text-align: left;
        }

        /* Partners */
        #partners {
            background-color: #ffffff;
        }
        .partners-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }
        .partner {
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            text-align: center;
            word-wrap: break-word; /* Ensure text fits */
        }
        .partner:nth-child(1) { background-color: #e8f5e8; } /* Light green */
        .partner:nth-child(2) { background-color: #e3f2fd; } /* Light blue */
        .partner:nth-child(3) { background-color: #fff3e0; } /* Light orange */
        .partner:nth-child(4) { background-color: #fce4ec; } /* Light pink */
        .partner h3 {
            color: #007bff;
            margin-bottom: 1rem;
        }
        .partner .logo {
            font-size: 2rem; /* Reduced from 2.5rem to make CARICOM fit better */
            color: #007bff;
            margin-bottom: 1rem;
        }

        /* Footer */
        footer {
            background-color: #007bff;
            color: white;
            text-align: center;
            padding: 1rem;
        }
        footer a {
            color: #cce7ff;
            text-decoration: underline;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .navbar .container {
                flex-direction: column;
            }
            .navbar ul {
                margin-top: 1rem;
            }
            .navbar li {
                margin-left: 1rem;
            }
            section {
                padding: 4rem 1rem 2rem;
            }
            #home h1 {
                font-size: 2rem;
            }
            .pillars, .partners-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <nav class="navbar">
        <div class="container">
            <div class="logo">Operación Kay La</div>
            <ul>
                <li><a href="#home">Inicio</a></li>
                <li><a href="#about">Acerca de</a></li>
                <li><a href="#context">Contexto</a></li>
                <li><a href="#partners">Socios</a></li>
            </ul>
        </div>
    </nav>

    <section id="home">
        <div class="container">
            <h1>Bienvenido a Operación Kay La</h1>
            <p class="slogan">Solidaridad, dignidad y esperanza para cada migrante.</p>
            <p>Operación Kay La es una iniciativa humanitaria propuesta por Haití para abordar los desafíos migratorios en las Américas a través de esfuerzos regionales coordinados.</p>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>Acerca de la Propuesta</h2>
            <p>La propuesta de Haití para Operación Kay La se centra en tres pilares principales para promover una migración segura, digna y sostenible en la región.</p>
            <div class="pillars">
                <div class="pillar">
                    <h3>Protocolos Fronterizos Humanitarios</h3>
                    <p>Estableciendo protocolos estandarizados en las fronteras para asegurar un trato humano, un procesamiento eficiente y el respeto a los derechos humanos durante los flujos migratorios.</p>
                </div>
                <div class="pillar">
                    <h3>Programas de Retorno Seguro y Reintegración</h3>
                    <p>Proporcionando apoyo para retornos voluntarios, incluyendo asesoramiento, transporte y asistencia de reintegración para ayudar a los migrantes a reconstruir sus vidas.</p>
                </div>
                <div class="pillar">
                    <h3>Fondo de Solidaridad Regional</h3>
                    <p>Un fondo que agrupa recursos de naciones socias para financiar ayuda humanitaria, infraestructura e iniciativas de fortalecimiento de capacidades en toda la región.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="context">
        <div class="container">
            <h2>Migración en las Américas</h2>
            <div class="content">
                <p>La migración en las Américas es un fenómeno complejo influenciado por disparidades económicas, inestabilidad política y factores ambientales. Este contexto resalta la necesidad de respuestas humanitarias coordinadas para asegurar la protección y la dignidad de los migrantes.</p>
            </div>
        </div>
    </section>

    <section id="partners">
        <div class="container">
            <h2>Nuestros Socios</h2>
            <p>Colaboramos con organizaciones internacionales líderes para avanzar en nuestros objetivos humanitarios.</p>
            <div class="partners-grid">
                <div class="partner">
                    <div class="logo">OEA</div>
                    <h3>Organización de los Estados Americanos</h3>
                    <p>Promoviendo la democracia y los derechos humanos en las Américas.</p>
                </div>
                <div class="partner">
                    <div class="logo">OIM</div>
                    <h3>Organización Internacional para las Migraciones</h3>
                    <p>Apoyando una migración segura y ordenada en todo el mundo.</p>
                </div>
                <div class="partner">
                    <div class="logo">ACNUR</div>
                    <h3>Alto Comisionado de las Naciones Unidas para los Refugiados</h3>
                    <p>Protegiendo a los refugiados y personas desplazadas a nivel global.</p>
                </div>
                <div class="partner">
                    <div class="logo">CARICOM</div>
                    <h3>Comunidad del Caribe</h3>
                    <p>Fomentando la integración económica y la cooperación en el Caribe.</p>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <p>Creado por Haití – MKMUN 2025 | <a href="https://github.com/tu-usuario/operacion-kay-la" target="_blank">Ver en GitHub</a></p>
    </footer>

    <script>
        // Smooth scrolling for navbar links
        document.querySelectorAll('.navbar a').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                target.scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Operación Kay La</title>
    <style>
        /* Reset and base styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #ffffff;
        }
        a {
            text-decoration: none;
            color: inherit;
        }
        ul {
            list-style: none;
        }

        /* Navbar */
        .navbar {
            position: fixed;
            top: 0;
            width: 100%;
            background-color: #007bff;
            color: white;
            padding: 1rem;
            z-index: 1000;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .navbar .container {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .navbar .logo {
            font-size: 1.5rem;
            font-weight: bold;
        }
        .navbar ul {
            display: flex;
        }
        .navbar li {
            margin-left: 2rem;
        }
        .navbar a {
            transition: color 0.3s;
        }
        .navbar a:hover {
            color: #cce7ff;
        }

        /* Sections */
        section {
            padding: 5rem 2rem 2rem; /* Adjusted for fixed navbar */
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            text-align: center;
        }
        h1, h2 {
            margin-bottom: 1rem;
            color: #007bff;
        }
        p {
            margin-bottom: 1rem;
            color: #666;
        }

        /* Home */
        #home {
            background-color: #e3f2fd; /* Light blue for more color */
        }
        #home h1 {
            font-size: 3rem;
        }
        #home .slogan {
            font-size: 1.5rem;
            color: #007bff;
        }

        /* About */
        #about {
            background-color: #ffffff;
        }
        .pillars {
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
            justify-content: center;
            margin-top: 2rem;
        }
        .pillar {
            background-color: #f1f8e9; /* Light green for variety */
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            flex: 1 1 300px;
            max-width: 350px;
        }
        .pillar h3 {
            color: #007bff;
            margin-bottom: 1rem;
        }

        /* Context */
        #context {
            background-color: #fff3e0; /* Light orange for more color */
        }
        #context .content {
            max-width: 800px;
            margin: 0 auto;
            text-align: left;
        }

        /* Partners */
        #partners {
            background-color: #ffffff;
        }
        .partners-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }
        .partner {
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            text-align: center;
            word-wrap: break-word; /* Ensure text fits */
        }
        .partner:nth-child(1) { background-color: #e8f5e8; } /* Light green */
        .partner:nth-child(2) { background-color: #e3f2fd; } /* Light blue */
        .partner:nth-child(3) { background-color: #fff3e0; } /* Light orange */
        .partner:nth-child(4) { background-color: #fce4ec; } /* Light pink */
        .partner h3 {
            color: #007bff;
            margin-bottom: 1rem;
        }
        .partner .logo {
            font-size: 2rem; /* Reduced from 2.5rem to make CARICOM fit better */
            color: #007bff;
            margin-bottom: 1rem;
        }

        /* Footer */
        footer {
            background-color: #007bff;
            color: white;
            text-align: center;
            padding: 1rem;
        }
        footer a {
            color: #cce7ff;
            text-decoration: underline;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .navbar .container {
                flex-direction: column;
            }
            .navbar ul {
                margin-top: 1rem;
            }
            .navbar li {
                margin-left: 1rem;
            }
            section {
                padding: 4rem 1rem 2rem;
            }
            #home h1 {
                font-size: 2rem;
            }
            .pillars, .partners-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <nav class="navbar">
        <div class="container">
            <div class="logo">Operación Kay La</div>
            <ul>
                <li><a href="#home">Inicio</a></li>
                <li><a href="#about">Acerca de</a></li>
                <li><a href="#context">Contexto</a></li>
                <li><a href="#partners">Socios</a></li>
            </ul>
        </div>
    </nav>

    <section id="home">
        <div class="container">
            <h1>Bienvenido a Operación Kay La</h1>
            <p class="slogan">Solidaridad, dignidad y esperanza para cada migrante.</p>
            <p>Operación Kay La es una iniciativa humanitaria propuesta por Haití para abordar los desafíos migratorios en las Américas a través de esfuerzos regionales coordinados.</p>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>Acerca de la Propuesta</h2>
            <p>La propuesta de Haití para Operación Kay La se centra en tres pilares principales para promover una migración segura, digna y sostenible en la región.</p>
            <div class="pillars">
                <div class="pillar">
                    <h3>Protocolos Fronterizos Humanitarios</h3>
                    <p>Estableciendo protocolos estandarizados en las fronteras para asegurar un trato humano, un procesamiento eficiente y el respeto a los derechos humanos durante los flujos migratorios.</p>
                </div>
                <div class="pillar">
                    <h3>Programas de Retorno Seguro y Reintegración</h3>
                    <p>Proporcionando apoyo para retornos voluntarios, incluyendo asesoramiento, transporte y asistencia de reintegración para ayudar a los migrantes a reconstruir sus vidas.</p>
                </div>
                <div class="pillar">
                    <h3>Fondo de Solidaridad Regional</h3>
                    <p>Un fondo que agrupa recursos de naciones socias para financiar ayuda humanitaria, infraestructura e iniciativas de fortalecimiento de capacidades en toda la región.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="context">
        <div class="container">
            <h2>Migración en las Américas</h2>
            <div class="content">
                <p>La migración en las Américas es un fenómeno complejo influenciado por disparidades económicas, inestabilidad política y factores ambientales. Este contexto resalta la necesidad de respuestas humanitarias coordinadas para asegurar la protección y la dignidad de los migrantes.</p>
            </div>
        </div>
    </section>

    <section id="partners">
        <div class="container">
            <h2>Nuestros Socios</h2>
            <p>Colaboramos con organizaciones internacionales líderes para avanzar en nuestros objetivos humanitarios.</p>
            <div class="partners-grid">
                <div class="partner">
                    <div class="logo">OEA</div>
                    <h3>Organización de los Estados Americanos</h3>
                    <p>Promoviendo la democracia y los derechos humanos en las Américas.</p>
                </div>
                <div class="partner">
                    <div class="logo">OIM</div>
                    <h3>Organización Internacional para las Migraciones</h3>
                    <p>Apoyando una migración segura y ordenada en todo el mundo.</p>
                </div>
                <div class="partner">
                    <div class="logo">ACNUR</div>
                    <h3>Alto Comisionado de las Naciones Unidas para los Refugiados</h3>
                    <p>Protegiendo a los refugiados y personas desplazadas a nivel global.</p>
                </div>
                <div class="partner">
                    <div class="logo">CARICOM</div>
                    <h3>Comunidad del Caribe</h3>
                    <p>Fomentando la integración económica y la cooperación en el Caribe.</p>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <p>Creado por Haití – MKMUN 2025 | <a href="https://github.com/tu-usuario/operacion-kay-la" target="_blank">Ver en GitHub</a></p>
    </footer>

    <script>
        // Smooth scrolling for navbar links
        document.querySelectorAll('.navbar a').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                target.scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
