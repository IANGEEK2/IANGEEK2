-<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apoya a Adrián Marcelo en La Casa de los Famosos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e0f7fa;
            margin: 0;
            padding: 0;
            color: #004d40;
        }

        header {
            background-color: #004d40;
            color: white;
            text-align: center;
            padding: 20px;
        }

        h1 {
            font-size: 2.5em;
            margin: 0;
            color: white;
        }

        nav {
            background-color: #00796b;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 1.2em;
        }

        .container {
            padding: 20px;
        }

        .section {
            margin-bottom: 40px;
        }

        .section h2 {
            color: #004d40;
            font-size: 2em;
            border-bottom: 3px solid #00796b;
            padding-bottom: 10px;
        }

        .section p {
            font-size: 1.2em;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .gallery img {
            width: 100%;
            height: auto;
            border: 5px solid #004d40;
            border-radius: 10px;
            transition: transform 0.3s;
        }

        .gallery img:hover {
            transform: scale(1.05);
        }

        .vote-section {
            text-align: center;
            margin-top: 20px;
        }

        .vote-section a {
            background-color: #004d40;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            font-size: 1.5em;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        .vote-section a:hover {
            background-color: #00796b;
        }

        footer {
            background-color: #004d40;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }

        .social-links a {
            color: white;
            font-size: 1.5em;
            text-decoration: none;
        }
    </style>
</head>
<body>

<header>
    <h1>Apoya a Adrián Marcelo en La Casa de los Famosos</h1>
</header>

<nav>
    <a href="#adrian">Fotos de Adrián Marcelo</a>
    <a href="#votar">Votar</a>
    <a href="#redes-sociales">Redes Sociales</a>
</nav>

<div class="container">
    <section id="adrian" class="section">
        <h2>Fotos de Adrián Marcelo</h2>
        <div class="gallery">
            <img src="adrian_marcelo_1.jpg" alt="Adrián Marcelo 1">
            <img src="adrian_marcelo_2.jpg" alt="Adrián Marcelo 2">
            <img src="adrian_marcelo_3.jpg" alt="Adrián Marcelo 3">
        </div>
    </section>

    <section id="votar" class="section vote-section">
        <h2>¡Vota por Adrián Marcelo!</h2>
        <p>Haz clic en el enlace a continuación para votar por Adrián Marcelo en "La Casa de los Famosos".</p>
        <a href="https://votacion.casadelfamoso.com" target="_blank">Vota Aquí</a>
    </section>

    <section id="redes-sociales" class="section">
        <h2>Sigue a Adrián Marcelo en sus Redes Sociales</h2>
        <div class="social-links">
            <a href="https://www.instagram.com/adrianmarcelo" target="_blank">Instagram</a>
            <a href="https://www.twitter.com/adrianmarcelo" target="_blank">Twitter</a>
            <a href="https://www.facebook.com/adrianmarcelo" target="_blank">Facebook</a>
        </div>
    </section>
</div>

<footer>
    <p>&copy; 2024 Apoya a Adrián Marcelo. Todos los derechos reservados.</p>
</footer>

</body>
</html>
