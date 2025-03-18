<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Monitoreo de Enfermedades Vectoriales</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background: url('C:/Users/user/OneDrive - unicolmayor.edu.co/Escritorio/Evidencias SENA/Pagina web/fondo-imagen') no-repeat center center/cover;
            color: #333;
        }

        header {
            background: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 1rem;
            text-align: center;
        }

        header img {
            height: 80px;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-size: 18px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        main {
            padding: 20px;
            text-align: center;
        }

        .mapa {
            margin-top: 20px;
        }

        footer {
            text-align: center;
            padding: 1rem;
            background: #222;
            color: white;
        }

        a {
            color: #4CAF50;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }
    </style>
</head>

<body>
    <header>
        <img src="C:/Users/user/OneDrive - unicolmayor.edu.co/Escritorio/Evidencias SENA/Pagina web/logo-imagen" alt="Logo de la Aplicación">
        <h1>Monitoreo de Enfermedades Vectoriales</h1>
        <nav>
            <a href="index.html">Inicio</a>
            <a href="datos.html">Datos</a>
            <a href="formulario.html">Formulario</a>
            <a href="registro.html">Registro</a>
        </nav>
    </header>

    <main>
        <h2>Bienvenido a la Plataforma de Monitoreo</h2>
        <p>Esta aplicación permite reportar casos sospechosos, recibir alertas en tiempo real y acceder a información educativa sobre malaria y leishmaniasis.</p>

        <div class="mapa">
            <h3>Mapa de Zonas Afectadas en Colombia</h3>
            <img src="C:/Users/user/OneDrive - unicolmayor.edu.co/Escritorio/Evidencias SENA/Pagina web/mapa-colombia" alt="Mapa de Colombia" width="80%">
        </div>

        <section>
            <h3>Características Principales:</h3>
            <ul>
                <li>Reporte de casos sospechosos.</li>
                <li>Alertas en tiempo real.</li>
                <li>Información educativa detallada.</li>
                <li>Ubicación de centros de salud cercanos.</li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Monitoreo de Enfermedades Vectoriales | <a href="#">Contacto</a></p>
    </footer>
</body>

</html>


<!-- Pagina datos.html -->
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <title>Datos - Monitoreo de Enfermedades</title>
</head>

<body>
    <h1>Datos Relevantes</h1>
    <p>Aquí se mostrarán estadísticas y datos relacionados con enfermedades vectoriales en Colombia.</p>
    <a href="index.html">Volver al inicio</a>
</body>

</html>


<!-- Pagina formulario.html -->
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <title>Formulario - Monitoreo de Enfermedades</title>
</head>

<body>
    <h1>Formulario de Reporte</h1>
    <form action="#" method="post">
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" name="nombre" required><br><br>

        <label for="ubicacion">Ubicación:</label>
        <input type="text" id="ubicacion" name="ubicacion" required><br><br>

        <label for="descripcion">Descripción del caso:</label><br>
        <textarea id="descripcion" name="descripcion" rows="4" required></textarea><br><br>

        <button type="submit">Enviar Reporte</button>
    </form>
    <a href="index.html">Volver al inicio</a>
</body>

</html>


<!-- Pagina registro.html -->
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <title>Registro - Monitoreo de Enfermedades</title>
</head>

<body>
    <h1>Registro de Usuario</h1>
    <form action="#" method="post">
        <label for="usuario">Usuario:</label>
        <input type="text" id="usuario" name="usuario" required><br><br>

        <label for="email">Correo Electrónico:</label>
        <input type="email" id="email" name="email" required><br><br>

        <label for="password">Contraseña:</label>
        <input type="password" id="password" name="password" required><br><br>

        <button type="submit">Registrar</button>
    </form>
    <a href="index.html">Volver al inicio</a>
</body>

</html>
