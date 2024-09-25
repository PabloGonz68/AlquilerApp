<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            margin: 20px;
            background-color: #f7f7f7;
            color: #333;
        }
        h1, h2, h3 {
            color: #3498db;
            text-align: center;
        }
        h1 {
            font-size: 2.5em;
            margin-bottom: 0.5em;
        }
        h2 {
            border-bottom: 2px solid #3498db;
            padding-bottom: 5px;
            margin-top: 20px;
            font-size: 1.8em;
        }
        h3 {
            margin-top: 15px;
            color: #2980b9;
            font-size: 1.5em;
        }
        p {
            margin: 15px 0;
        }
        ul, ol {
            margin: 10px 0;
            padding-left: 20px;
        }
        li {
            margin: 5px 0;
        }
        .highlight {
            background-color: #e7f3fe;
            padding: 10px;
            border-left: 4px solid #3498db;
            margin-bottom: 20px;
        }
        .footer {
            margin-top: 40px;
            font-size: 0.9em;
            text-align: center;
            color: #555;
        }
    </style>
</head>
<body>

    <h1>Proyecto 1</h1>

    <h2>Desarrollando una aplicación web</h2>
    <h3>De la teoría a la práctica</h3>

    <h2>Documento de propuesta</h2>

    <div class="highlight">
        <p><strong>Asignatura:</strong> Desarrollo Web<br>
        <strong>Entorno al Cliente</strong><br>
        <strong>Fecha:</strong> 24/09/2024<br>
        <strong>Nombre:</strong> Pablo González Silva</p>
    </div>

    <h2>¿Qué contiene?</h2>
    <ul>
        <li>Descripción de la idea de la aplicación y su propósito.</li>
        <li>Público objetivo y relevancia.</li>
        <li>Análisis de mercado y propuesta de valor diferenciadora.</li>
        <li>Funcionalidades clave de la aplicación.</li>
        <li>Tecnologías seleccionadas para el desarrollo, con justificación.</li>
    </ul>

    <h2>Descripción de la idea y propósito</h2>
    <p>La plataforma web se dedica al alquiler de productos entre particulares, creando un espacio donde los usuarios pueden ofrecer y alquilar objetos poco utilizados, como herramientas, equipos electrónicos o muebles. Se fomenta un uso eficiente de los recursos y se promueve la economía colaborativa.</p>

    <p>El objetivo es facilitar el acceso temporal a productos necesarios, abordando el consumismo excesivo y promoviendo un consumo más sostenible. También permite a los usuarios monetizar bienes poco usados, generando ingresos pasivos.</p>

    <h2>Público objetivo</h2>
    <p>La aplicación está dirigida a:</p>

    <h3>Personas que necesitan productos de uso temporal:</h3>
    <ul>
        <li><strong>Particulares:</strong> que necesitan productos puntuales sin querer comprarlos.</li>
        <li><strong>Estudiantes y jóvenes profesionales:</strong> que buscan soluciones temporales.</li>
    </ul>

    <h3>Propietarios de productos en desuso:</h3>
    <ul>
        <li><strong>Generar ingresos:</strong> alquilando objetos que no utilizan frecuentemente.</li>
    </ul>

    <h3>Personas interesadas en consumo sostenible:</h3>
    <ul>
        <li><strong>Reducción de desperdicios:</strong> buscando alternativas al consumismo.</li>
    </ul>

    <h3>Comunidades locales:</h3>
    <ul>
        <li><strong>Facilitando transacciones:</strong> entre personas de la misma zona.</li>
    </ul>

    <h2>Análisis de mercado y propuesta de valor</h2>
    <p>El alquiler de productos entre particulares es parte de la economía colaborativa, ganando popularidad por su impacto económico y medioambiental positivo. Competidores como Wallapop y Fat Llama ofrecen servicios similares, pero nuestra propuesta tiene ventajas competitivas:</p>
    
    <ol>
        <li><strong>Enfoque Exclusivo en el Alquiler:</strong> Optimizando la experiencia de alquiler.</li>
        <li><strong>Foco en la Comunidad Local:</strong> Facilita entregas y devoluciones.</li>
        <li><strong>Segmentación Flexible de Categorías:</strong> Amplia gama de productos.</li>
        <li><strong>Sostenibilidad:</strong> Alineada con tendencias de consumo responsable.</li>
        <li><strong>Valoraciones y Reputación:</strong> Filtro de confianza para los usuarios.</li>
    </ol>

    <h2>Funcionalidades clave de la aplicación</h2>
    
    <ol>
        <li><strong>Registro de Usuarios:</strong>
            <ul>
                <li>Registro y Login mediante correo o redes sociales.</li>
                <li>Verificación de identidad mediante documentos.</li>
                <li>Perfil de usuario con historial de alquileres.</li>
            </ul>
        </li>
        <li><strong>Publicación de Productos:</strong>
            <ul>
                <li>Subida de productos con descripciones y fotos.</li>
                <li>Gestión de disponibilidad mediante calendario.</li>
                <li>Precios flexibles según tiempo de alquiler.</li>
            </ul>
        </li>
        <li><strong>Búsqueda y Filtrado:</strong>
            <ul>
                <li>Búsqueda avanzada por categoría y ubicación.</li>
                <li>Geolocalización para encontrar productos cercanos.</li>
            </ul>
        </li>
        <li><strong>Proceso de Alquiler:</strong>
            <ul>
                <li>Reserva de productos en fechas disponibles.</li>
                <li>Pagos integrados mediante plataformas seguras.</li>
                <li>Contratos digitales que estipulan condiciones.</li>
            </ul>
        </li>
        <li><strong>Sistema de Valoraciones:</strong>
            <ul>
                <li>Calificación mutua entre arrendadores y arrendatarios.</li>
                <li>Construcción de reputación basada en valoraciones.</li>
            </ul>
        </li>
    </ol>

    <h2>Tecnologías seleccionadas</h2>

    <h3>Parte Cliente (Frontend)</h3>
    <ul>
        <li><strong>Angular:</strong> Framework principal para la interfaz de usuario.</li>
        <li><strong>HTML5:</strong> Estructura semántica de la interfaz.</li>
        <li><strong>CSS3:</strong> Diseño responsivo y atractivo.</li>
        <li><strong>TypeScript:</strong> Lenguaje principal para un código más seguro.</li>
        <li><strong>Google Maps API:</strong> Integración de mapas interactivos.</li>
    </ul>

    <h3>Parte Servidor (Backend)</h3>
    <ul>
        <li><strong>MySQL:</strong> Gestión de base de datos para almacenar información.</li>
        <li><strong>Google Maps API:</strong> Procesamiento de ubicaciones en el backend.</li>
    </ul>

    <div class="footer">
        <p>Este documento presenta la propuesta para una innovadora plataforma de alquiler de productos entre particulares, diseñada para ser sostenible y accesible.</p>
    </div>

</body>
</html>
