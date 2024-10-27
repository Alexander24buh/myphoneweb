<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Phone - Venta de Celulares</title>
    <style>
        /* Estilos básicos para diseño y responsividad */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: white;
            padding: 1em;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #555;
        }
        .container {
            padding: 20px;
        }
        .catalogo, .ofertas {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .tarjeta {
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 16px;
            background-color: white;
            width: 200px;
            text-align: center;
        }
        .tarjeta img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .btn-comprar {
            background-color: #28a745;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .btn-comprar:hover {
            background-color: #218838;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<!-- Encabezado y Menú de Navegación -->
<header>
    <h1>My Phone</h1>
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#catalogo">Catálogo</a>
        <a href="#ofertas">Ofertas</a>
        <a href="#contacto">Contacto</a>
    </nav>
</header>

<div class="container">

    <!-- Sección de Filtros -->
    <section id="filtros">
        <h2>Filtrar por:</h2>
        <label>Marca:
            <select>
                <option>Apple</option>
                <option>Samsung</option>
                <option>Huawei</option>
                <option>Xiaomi</option>
            </select>
        </label>
        <label>Diseño:
            <select>
                <option>Plegable</option>
                <option>Gama Alta</option>
                <option>Gama Media</option>
                <option>Gama Baja</option>
            </select>
        </label>
    </section>

    <!-- Sección de Catálogo de Productos -->
    <section id="catalogo">
        <h2>Catálogo de Productos</h2>
        <div class="catalogo">
            <!-- Tarjeta de Producto -->
            <div class="tarjeta">
                <img src="ruta-a-imagen.jpg" alt="Imagen del celular">
                <h3>iPhone 13</h3>
                <p>Marca: Apple</p>
                <p>Diseño: Gama Alta</p>
                <p>Precio: $999</p>
                <button class="btn-comprar">Comprar</button>
            </div>
            <!-- Agrega más tarjetas de productos aquí -->
        </div>
    </section>

    <!-- Sección de Ofertas -->
    <section id="ofertas">
        <h2>Ofertas Especiales</h2>
        <div class="ofertas">
            <div class="tarjeta">
                <img src="ruta-a-imagen.jpg" alt="Imagen del celular en oferta">
                <h3>Samsung Galaxy S21</h3>
                <p>Marca: Samsung</p>
                <p>Diseño: Gama Alta</p>
                <p>Precio: <del>$899</del> $799</p>
                <button class="btn-comprar">Comprar</button>
            </div>
            <!-- Agrega más tarjetas de ofertas aquí -->
        </div>
    </section>

    <!-- Formulario de Contacto -->
    <section id="contacto">
        <h2>Contáctanos</h2>
        <form action="#" method="POST">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>
            <br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <br>
            <label for="mensaje">Mensaje:</label>
            <textarea id="mensaje" name="mensaje" rows="4" required></textarea>
            <br>
            <button type="submit">Enviar</button>
        </form>
    </section>

</div>

<!-- Pie de Página -->
<footer>
    <p>&copy; 2024 My Phone. Todos los derechos reservados.</p>
    <p><a href="#terminos">Términos y Condiciones</a> | <a href="#privacidad">Política de Privacidad</a></p>
</footer>

</body>
</html>
