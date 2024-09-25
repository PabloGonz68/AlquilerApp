<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proyecto 1 - Propuesta</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #ece9e6, #ffffff);
            color: #333;
            line-height: 1.6;
            padding: 20px;
        }
        h1, h2, h3 {
            color: #ff6347;
        }
        h1 {
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 20px;
            animation: slideIn 1s;
        }
        h2 {
            border-bottom: 2px solid #ff6347;
            padding-bottom: 5px;
            margin-top: 40px;
        }
        p {
            margin: 10px 0;
        }
        .content {
            max-width: 800px;
            margin: 0 auto;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            animation: fadeIn 1.5s;
        }
        ul {
            margin: 10px 0 20px 20px;
            list-style-type: square;
        }
        .highlight {
            background-color: #f0f8ff;
            padding: 10px;
            border-left: 4px solid #ff6347;
        }
        @keyframes slideIn {
            from { transform: translateY(-50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>
<body>
    <div class="content">
        <h1>Proyecto 1</h1>
        <h2>Desarrollando una aplicación web</h2>
        <h3>De la teoría a la práctica</h3>
        
        <p class="highlight">Documento de propuesta</p>
        
        <p><strong>Asignatura:</strong> Desarrollo Web</p>
        <p><strong>Entorno al Cliente</strong></p>
        <p><strong>Fecha:</strong> 24/09/2024</p>
        <p><strong>Nombre:</strong> Pablo González Silva</p>
        
        <h2>¿Qué contiene?</h2>
        <ul>
            <li>Descripción de la idea de la aplicación y su propósito.</li>
            <li>Público objetivo y relevancia.</li>
            <li>Análisis de mercado y propuesta de valor diferenciadora.</li>
            <li>Funcionalidades clave de la aplicación.</li>
            <li>Tecnologías seleccionadas para el desarrollo, con justificación.</li>
        </ul>
        
        <h2>Descripción de la idea y propósito</h2>
        <p>
            La idea es una plataforma web dedicada al alquiler de productos entre particulares. El objetivo es crear un espacio donde los usuarios puedan ofrecer y alquilar objetos que no utilizan frecuentemente, como herramientas, equipos electrónicos, o muebles para eventos. Esto fomenta un uso más eficiente de los recursos, evitando la compra de artículos de uso ocasional y promoviendo la economía colaborativa.
        </p>
        <p>
            Facilita el acceso temporal a productos que las personas necesitan, pero no desean comprar. Esto aborda el problema del consumismo excesivo y promueve un consumo más sostenible, permitiendo a los usuarios monetizar los bienes que no utilizan.
        </p>

        <h2>Público objetivo y relevancia</h2>
        <p>Dirigida a un público amplio que incluye:</p>
        <ul>
            <li><strong>Personas que necesitan productos de uso temporal:</strong> Particulares que requieren herramientas, equipos deportivos o muebles, pero no desean comprarlos.</li>
            <li><strong>Personas que poseen productos en desuso:</strong> Propietarios de objetos que buscan generar ingresos alquilándolos.</li>
            <li><strong>Personas interesadas en el consumo sostenible:</strong> Usuarios preocupados por el medio ambiente que buscan reducir el desperdicio.</li>
            <li><strong>Comunidades locales:</strong> Facilita el alquiler de productos entre personas de la misma zona.</li>
        </ul>

        <h2>Análisis de mercado y propuesta de valor</h2>
        <p>
            El mercado del alquiler de productos entre particulares forma parte de la economía colaborativa, que ha ganado popularidad por su impacto positivo. Aunque existen competidores como Wallapop y Fat Llama, nuestra aplicación tiene ventajas competitivas:
        </p>
        <ul>
            <li><strong>Enfoque Exclusivo en el Alquiler:</strong> Optimización de funcionalidades para una experiencia fluida.</li>
            <li><strong>Foco en la Comunidad Local:</strong> Facilita entregas y devoluciones sin intermediarios.</li>
            <li><strong>Segmentación Flexible de Categorías:</strong> Amplia gama de productos adaptables a nichos específicos.</li>
            <li><strong>Sostenibilidad como Pilar Central:</strong> Alineada con tendencias de consumo responsable.</li>
            <li><strong>Valoraciones y Reputación como Filtro de Confianza:</strong> Genera un ambiente seguro y confiable.</li>
        </ul>

        <h2>Funcionalidades clave</h2>
        <ul>
            <li><strong>Registro de Usuarios y Verificación de Identidad:</strong> Facilita el registro y genera confianza.</li>
            <li><strong>Publicación de Productos para Alquilar:</strong> Gestión de disponibilidad y precios flexibles.</li>
            <li><strong>Búsqueda y Filtrado de Productos:</strong> Búsqueda avanzada y geolocalización.</li>
            <li><strong>Proceso de Alquiler:</strong> Reserva fácil, pagos integrados y contratos digitales.</li>
            <li><strong>Sistema de Valoraciones y Reputación:</strong> Fomenta confianza y transparencia.</li>
        </ul>

        <h2>Tecnologías seleccionadas para el desarrollo</h2>
        <h3>Parte Cliente (Frontend)</h3>
        <ul>
            <li><strong>Angular:</strong> Framework principal para la interfaz de usuario.</li>
            <li><strong>HTML5:</strong> Estructura semántica y optimizada.</li>
            <li><strong>CSS3:</strong> Diseño responsivo y atractivo.</li>
            <li><strong>TypeScript:</strong> Código seguro y estructurado.</li>
            <li><strong>Google Maps API:</strong> Mapas interactivos para la experiencia de usuario.</li>
        </ul>

        <h3>Parte Servidor (Backend)</h3>
        <ul>
            <li><strong>MySQL:</strong> Gestión de base de datos relacional.</li>
            <li><strong>Google Maps API:</strong> Procesamiento de ubicaciones en el backend.</li>
        </ul>
    </div>
</body>
</html>
