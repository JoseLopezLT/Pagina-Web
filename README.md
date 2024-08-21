<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Ropa Fashion</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }

        header {
            background-color: #ff6347; /* Tomate */
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
            letter-spacing: 2px;
        }

        nav {
            background-color: #ffa07a; /* Salmon claro */
            padding: 10px 0;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 1.2em;
        }

        #hero {
            background-color: #20b2aa; /* Turquesa */
            color: #fff;
            text-align: center;
            padding: 100px 20px;
            background-image: url('https://via.placeholder.com/1920x600');
            background-size: cover;
            background-blend-mode: multiply;
        }

        #hero h2 {
            font-size: 3em;
            margin: 0 0 10px 0;
        }

        #hero p {
            font-size: 1.5em;
            margin: 0 0 20px 0;
        }

        .btn {
            background-color: #ff4500; /* Naranja Rojo */
            color: #fff;
            padding: 15px 30px;
            text-decoration: none;
            font-size: 1.5em;
            border-radius: 50px;
            display: inline-block;
            transition: background-color 0.3s ease;
        }

        .btn:hover {
            background-color: #ff6347; /* Tomate */
        }

        .productos {
            display: flex;
            justify-content: space-around;
            margin: 50px 0;
        }

        .producto {
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
            width: 30%;
            padding: 20px;
            transition: transform 0.3s ease;
        }

        .producto img {
            max-width: 100%;
            border-radius: 10px;
        }

        .producto h3 {
            margin: 20px 0 10px 0;
            font-size: 1.8em;
            color: #333;
        }

        .producto p {
            font-size: 1.5em;
            color: #ff6347;
            font-weight: bold;
        }

        .producto:hover {
            transform: translateY(-10px);
        }

        .comprar-btn {
            background-color: #32cd32; /* Verde Lima */
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            margin-top: 10px;
            font-size: 1.2em;
            transition: background-color 0.3s ease;
        }

        .comprar-btn:hover {
            background-color: #228b22; /* Verde Forst */
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }

        footer p {
            margin: 0;
            font-size: 1em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Tienda Fashion</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#">Inicio</a></li>
            <li><a href="#">Catálogo</a></li>
            <li><a href="#">Ofertas</a></li>
            <li><a href="#">Contacto</a></li>
        </ul>
    </nav>

    <section id="hero">
        <h2>Descubre Tu Estilo</h2>
        <p>¡Las mejores camisetas y ropa a un clic de distancia!</p>
        <a href="#" class="btn">Ver Catálogo</a>
    </section>

    <section class="productos">
        <div class="producto">
            <img src="https://via.placeholder.com/300x300" alt="Camiseta 1">
            <h3>Camiseta 1</h3>
            <p>$20.00</p>
            <a href="https://wa.me/573213733338?text=Deseo%20comprar%20Camiseta%201" class="comprar-btn">Comprar</a>
        </div>
        <div class="producto">
            <img src="https://via.placeholder.com/300x300" alt="Camiseta 2">
            <h3>Camiseta 2</h3>
            <p>$25.00</p>
            <a href="https://wa.me/573213733338?text=Deseo%20comprar%20Camiseta%202" class="comprar-btn">Comprar</a>
        </div>
        <div class="producto">
            <img src="https://via.placeholder.com/300x300" alt="Camiseta 3">
            <h3>Camiseta 3</h3>
            <p>$30.00</p>
            <a href="https://wa.me/573213733338?text=Deseo%20comprar%20Camiseta%203" class="comprar-btn">Comprar</a>
        </div>
    </section>

    <footer>
        <p>© 2024 Tienda Fashion. Todos los derechos reservados.</p>
    </footer>
</body>
</html>

