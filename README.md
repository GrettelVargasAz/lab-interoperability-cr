<!DOCTYPE html>
<html lang="es">

<head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Lab Interoperability CR</title>

    <style>

        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
        }

        body{
            font-family: Arial, sans-serif;
            background:#f4f6f9;
            color:#1e293b;
        }

        header{
            background:#1f4e79;
            color:white;
            text-align:center;
            padding:50px 20px;
        }

        header h1{
            font-size:42px;
            margin-bottom:15px;
        }

        header p{
            font-size:18px;
            margin:8px 0;
        }

        .modules{
            display:grid;
            grid-template-columns:repeat(auto-fit, minmax(280px,1fr));
            gap:25px;
            padding:50px;
            max-width:1400px;
            margin:auto;
        }

        .card{
            background:white;
            border-radius:18px;
            padding:35px 25px;
            box-shadow:0 4px 12px rgba(0,0,0,0.08);
            transition:0.3s;
            border-top:6px solid #1f4e79;
        }

        .card:hover{
            transform:translateY(-5px);
        }

        .card h2{
            font-size:24px;
            margin-bottom:15px;
            color:#1f4e79;
        }

        .card p{
            font-size:16px;
            line-height:1.6;
            margin-bottom:20px;
            color:#475569;
        }

        .tools{
            font-size:14px;
            font-weight:bold;
            color:#0f172a;
            margin-bottom:20px;
        }

        .btn{
            display:inline-block;
            text-decoration:none;
            background:#1f4e79;
            color:white;
            padding:12px 20px;
            border-radius:10px;
            transition:0.3s;
            font-size:14px;
        }

        .btn:hover{
            background:#163a5c;
        }

        .info-section{
            background:white;
            margin:40px auto;
            max-width:1300px;
            padding:50px;
            border-radius:18px;
            box-shadow:0 4px 12px rgba(0,0,0,0.08);
        }

        .info-section h2{
            color:#1f4e79;
            margin-bottom:20px;
            font-size:32px;
        }

        .info-section p{
            font-size:18px;
            line-height:1.8;
            color:#475569;
        }

        footer{
            background:#1f4e79;
            color:white;
            text-align:center;
            padding:30px 20px;
            margin-top:50px;
        }

        footer p{
            margin:8px 0;
            font-size:15px;
        }

        @media(max-width:768px){

            header h1{
                font-size:32px;
            }

            .modules{
                padding:25px;
            }

            .info-section{
                margin:20px;
                padding:30px;
            }

        }

    </style>

</head>

<body>

    <header>

        <h1>Lab Interoperability CR</h1>

        <p>
            Herramientas abiertas para monitoreo, restauración y automatización geoespacial
        </p>

        <p>
            KoboToolbox • Herramientas SIG • Análisis en la nube • Dashboards y estadísticas
        </p>

        <p>
            Desarrollado por Grettel Vargas Azofeifa
        </p>

    </header>

    <section class="modules">

        <div class="card">

            <h2>Formularios Inteligentes</h2>

            <p>
                Captura de información de campo mediante formularios digitales y geoespaciales para monitoreo de ecosistemas.
            </p>

            <div class="tools">
                KoboToolbox
            </div>

            <a href="#" class="btn">
                Ver módulo
            </a>

        </div>

        <div class="card">

            <h2>Herramientas SIG</h2>

            <p>
                Gestión, análisis y visualización de datos espaciales utilizando plataformas SIG de escritorio.
            </p>

            <div class="tools">
                QGIS • ArcGIS Pro
            </div>

            <a href="#" class="btn">
                Ver módulo
            </a>

        </div>

        <div class="card">

            <h2>Análisis Geoespacial en la Nube</h2>

            <p>
                Procesamiento, automatización y análisis avanzado de información satelital y datos ambientales.
            </p>

            <div class="tools">
                Google Colab • Google Earth Engine
            </div>

            <a href="#" class="btn">
                Ver módulo
            </a>

        </div>

        <div class="card">

            <h2>Dashboards y Estadísticas</h2>

            <p>
                Visualización de indicadores, gráficos, mapas y reportes para apoyo a la toma de decisiones.
            </p>

            <div class="tools">
                WebGIS • Dashboards • Indicadores
            </div>

            <a href="#" class="btn">
                Ver módulo
            </a>

        </div>

    </section>

    <section class="info-section">

        <h2>Interoperabilidad Geoespacial</h2>

        <p>
            Este laboratorio integra herramientas abiertas y plataformas geoespaciales modernas para fortalecer procesos de monitoreo, restauración de ecosistemas y automatización de flujos de trabajo.
            El enfoque busca conectar formularios digitales, SIG de escritorio, procesamiento en la nube y sistemas de visualización para facilitar el análisis, la integración y el uso estratégico de información territorial.
        </p>

    </section>

    <footer>

        <p>
            Lab Interoperability CR
        </p>

        <p>
            Desarrollado por Grettel Vargas Azofeifa
        </p>

    </footer>

</body>

</html>
