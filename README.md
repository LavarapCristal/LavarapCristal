<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Servicio de Lavado - Lavadero Cristal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #003366;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        section {
            padding: 20px;
        }
        .services {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .service {
            background-color: #ffffff;
            padding: 15px;
            margin: 10px;
            border-radius: 5px;
            width: 30%;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .service h2 {
            color: #003366;
        }
        .service p {
            font-size: 16px;
            color: #666;
        }
        form {
            background-color: #ffffff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            margin-top: 20px;
        }
        input[type="text"], input[type="email"], textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        button {
            background-color: #003366;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0055cc;
        }
        @media screen and (max-width: 768px) {
            .service {
                width: 100%;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Lavadero Cristal</h1>
    <p>¡Servicios de lavandería y limpieza de calidad cerca de ti!</p>
</header>

<section>
    <h2>Servicios</h2>
    <div class="services">
        <div class="service">
            <h2>Lavado de Ropa</h2>
            <p>Ofrecemos lavado de ropa de todo tipo, asegurándonos de que quede limpia y fresca.</p>
        </div>
        <div class="service">
            <h2>Limpieza de Tapizados</h2>
            <p>Lavado de sofás, colchones, y tapizados de todo tipo con productos de calidad.</p>
        </div>
        <div class="service">
            <h2>Lavado de Interiores Vehiculares</h2>
            <p>Te ayudamos a mantener el interior de tu vehículo limpio y fresco.</p>
        </div>
    </div>

    <h2>Realiza tu Pedido</h2>
    <form action="mailto:centocavalli.hotmail.com" method="POST" enctype="text/plain">
        <label for="name">Nombre</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Correo Electrónico</label>
        <input type="email" id="email" name="email" required>

        <label for="service">Servicio Solicitado</label>
        <textarea id="service" name="service" rows="4" required></textarea>

        <button type="submit">Enviar Pedido</button>
    </form>
</section>

</body>
</html>![IMG-20240623-WA0068](https://github.com/user-attachments/assets/a9b49b33-18c8-4558-8dbe-26d847e65152)
