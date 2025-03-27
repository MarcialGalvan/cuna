<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Web</title>
    <link href="https://fonts.googleapis.com/css2?family=Inconsolata&display=swap" rel="stylesheet">
    <style>
        body {
            background-color: #f0f0f0; /* Un gris muy claro */
            color: #333; /* Gris oscuro para el texto */
            font-family: 'Inconsolata', monospace; /* Fuente estilo máquina de escribir */
            margin: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            padding: 20px;
            text-align: center;
        }
        h1 {
            font-size: 2.5em;
            margin-bottom: 20px;
            white-space: nowrap;
            overflow: hidden;
            border-right: .15em solid orange; /* El cursor */
            animation: typing 3.5s steps(40, end),
                       blink-caret .75s step-end infinite;
        }
        @keyframes typing {
            from { width: 0 }
            to { width: 100% }
        }
        @keyframes blink-caret {
            from, to { border-color: transparent }
            50% { border-color: orange; }
        }
        p {
            font-size: 1.2em;
            margin-bottom: 30px;
        }
        .descarga-links {
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin-bottom: 30px;
        }
        .descarga-link {
            background-color: #fff; /* Blanco */
            color: #333; /* Gris oscuro para el texto */
            padding: 12px 25px;
            text-decoration: none;
            border: 1px solid #ccc; /* Borde gris claro */
            border-radius: 5px;
            font-size: 1.1em;
            transition: background-color 0.3s ease, color 0.3s ease;
            width: 200px; /* Ancho fijo para los botones */
            text-align: center;
        }
        .descarga-link:hover {
            background-color: #f0f0f0; /* Un gris muy claro al pasar el ratón */
            color: #333;
        }
        footer {
            font-size: 0.9em;
            color: #888; /* Gris más claro para el pie de página */
            margin-top: 20px;
        }
        @media (max-width: 600px) {
            h1 {
                font-size: 2em;
            }
            p {
                font-size: 1em;
            }
            .descarga-links {
                flex-direction: column;
                align-items: center;
            }
            .descarga-link {
                width: 100%; /* Los botones ocupan el ancho completo en pantallas pequeñas */
            }
        }
    </style>
</head>
<body>
    <h1>Tu Nombre</h1>
    <p>¡Bienvenido a mi página web!</p>
    <div class="descarga-links">
        <a href="#" class="descarga-link">Descarga el Contenido 1</a>
        <a href="#" class="descarga-link">Descarga el Contenido 2</a>
    </div>
    <footer>
        <p>© 2024 Tu Nombre. Todos los derechos reservados.</p>
    </footer>
    <script>
        // No se necesita JavaScript adicional para el estilo de máquina de escribir, está en el CSS.
    </script>
</body>
</html>
