# Pagina-Web---Proyecto-de-Grado
Proyecto de Grado - Pagina Web sistema POS 9310 integrado en una plataforma digital para modernizar y optimizar las actividades comerciales y productivas del sector agrícola en la región de Ocaña y las provincias,
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registro de Usuario</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Registro de Usuario</h1>
        <form id="registerForm">
            <label for="username">Nombre de Usuario:</label>
            <input type="text" id="username" name="username" required>

            <label for="email">Correo Electrónico:</label>
            <input type="email" id="email" name="email" required>

            <label for="password">Contraseña:</label>
            <input type="password" id="password" name="password" required>

            <label for="confirmPassword">Confirmar Contraseña:</label>
            <input type="password" id="confirmPassword" name="confirmPassword" required>

            <button type="submit">Registrar</button>
        </form>
        <div id="message"></div>
    </div>
    <script src="script.js"></script>
</body>
</html>
