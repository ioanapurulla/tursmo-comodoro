<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Turismo Comodoro</title>
    <link rel="shortcut icon" href="c:\Users\practica\Desktop\agencia de turismo\imagenes\logo.jpg"  width="200">
    <link rel="stylesheet" href="styles.css"> <!-- Enlace a un archivo CSS para estilos -->
</head>
<body>
    <header>
        <h1>¡Bienvenidos a COMODORORIVADAVIA!</h1>
        <h3>LA CIUDAD DEL VIENTO</h3>
        <nav>
            <ul>
                <li><a href="#nosotros">Nosotros</a></li>
                <li><a href="#servicio">Servicio</a></li>
                <li><a href="#galeria">Galería</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="bienvenida">
            <img src="C:\Users\practica\Desktop\agencia de turismo\imagenes\comodoro.jpg"alt="Imagen de bienvenida" style="width:100%;">
            
        </section>

        <section id="nosotros">
            <h2>Nosotros</h2>
            <article>
                <p>Comodoro Rivadavia, coloquialmente denominada «Comodoro», es la ciudad más habitada de la provincia del Chubut y la cabecera del departamento Escalante en Argentina. Está ubicada al centro este de la Patagonia en el corazón de la zona hidrocarburífera del golfo San Jorge</p>
                <p>Es una de las ciudades más importantes de la Patagonia argentina. Las ciudades más cercanas son Caleta Olivia, a 77 kilómetros, y Colonia Sarmiento, a 155 kilómetros.</p>          
                <p>Comodoro Rivadavia es un concentrador comercial, de transporte regional y un importante punto de exportación. Por medio de su puerto salen al mundo petróleo, productos industriales y agrícolas regionales. </p>
            </article>
        </section>

        <section id="servicio">
            <h2>Vivi comodoro</h2>
            <div class="menu-desplegable">
                <button class="desplegable-btn" id="desplegable-btn">Actividades en la Ciudad</button>
                <nav class="submenu" id="submenu">
                    <ul>
                        <li><a href="Senderos y riradores">Senderos y miradores</a></li>
                        <li><a href="Atractivos naturales">Atractivos Naturales</a></li>
                        <li><a href="Barrios Petroleros">Barrios Petroleros</a></li>
                        <li><a href="Museo y Centro de Expociciones">Museo y Centro de Expociciones</a></li>
                        <li><a href="Centro Culturales">Centro Culturales</a></li>
                        <li><a href="Circuitos">Circuitos</a></li>
                        <li><a href="Paseos Regionales">Paseos Regionales</a></li>
                        <li><a href="Parques y Campings">Parques y Campings</a></li>
                    </ul>
                </nav>
            </div>
            <article>
                <p>Descubre las diferentes actividades que ofrece la cuidad para tu estadia</p>
            </article>
        </section>
   

        <section id="galeria">
            <h2>Galería</h2>
            <article>
                <div class="galeria-imagenes">
                    <img src="c:\Users\practica\Desktop\agencia de turismo\imagenes\paisaje1.jpg" alt="Descripción de la imagen 1">
                    <img src="c:\Users\practica\Desktop\agencia de turismo\imagenes\paisaje2.jpg" alt="Descripción de la imagen 2">
                    <img src="c:\Users\practica\Desktop\agencia de turismo\imagenes\faro.jpg" alt="Descripción de la imagen 3">
                    <img src="c:\Users\practica\Desktop\agencia de turismo\imagenes\loberia.jpg" alt="Descripción de la imagen 4">
                    <img src="c:\Users\practica\Desktop\agencia de turismo\imagenes\costanera.jpg" alt="Descripción de la imagen 5">
                    <img src="C:\Users\practica\Desktop\agencia de turismo\imagenes\chalet huergo.jpg" alt="Descripción de la imagen 6">
                    <img src="C:\Users\practica\Desktop\agencia de turismo\imagenes\desde el mar.jpg" alt="Descripción de la imagen 7">

                </div>
            </article>
        </section>

        <section id="contacto">
            <h2>Contacto</h2>
            <div class="informacion-contacto">
                <h3>Información de Contacto</h3>
                <p><strong>Teléfono:</strong> 02974137552</p>
                <p><strong>Email:</strong> info@buentour.com</p>
                <p><strong>Dirección:</strong>Avenida Rivadavia 252, Comodoro Rivadavia, Chubut, Argentina</p>
            </div>
            
            <div class="formulario-contacto">
                <h3>Envíanos un Mensaje</h3>
                <form id="formulario" action="tu_script_de_envio.php" method="post">
                    <label for="nombre">Nombre:</label>
                    <input type="text" id="nombre" name="nombre" required>
        
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>
        
                    <label for="mensaje">Mensaje:</label>
                    <textarea id="mensaje" name="mensaje" rows="4" required></textarea>
        
                    <button type="submit">Enviar</button>
                </form>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Nombre del Sitio. Todos los derechos reservados.</p>
    </footer>
    <script>
        document.getElementById('desplegable-btn').addEventListener('click', function() {
            const submenu = document.getElementById('submenu');
            submenu.style.display = submenu.style.display === 'block' ? 'none' : 'block';
        });
        
   
    </script>
</body>
</html>
