<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda Online</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #023A72; /* Cambio de color de fondo a azul */
            padding: 20px;
            text-align: center; /* Centrar texto horizontalmente */
            margin: 0; /* Eliminar márgenes predeterminados */
        }
        h1 {
            color: #fff; /* Color de texto blanco */
        }

        .producto {
            border: 1px solid #ccc;
            background-color: #fff;
            margin: 10px;
            padding: 10px;
            width: 200px;
            display: inline-block;
            text-align: center;
        }
        .producto img {
            max-width: 100%;
            height: auto;
        }
        .carrito {
            position: fixed;
            top: 20px;
            right: 20px;
            width: 60px; /* Ajustar el tamaño del carrito */
            height: 60px; /* Ajustar el tamaño del carrito */
            background-image: url('https://cdn-icons-png.freepik.com/512/9284/9284424.png'); /* Nueva URL del ícono del carrito */
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
            cursor: pointer; /* Cambiar cursor al pasar sobre el carrito */
            z-index: 1000; /* Asegurar que esté por encima de otros elementos */
            border-radius: 50%; /* Hacer el carrito redondo */
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Sombra ligera al carrito */
        }
        .carrito:hover {
            opacity: 0.8; /* Cambiar la opacidad al pasar sobre el carrito */
        }
        .carrito ul {
            list-style-type: none;
            padding: 0;
        }
        .carrito li {
            margin-bottom: 5px;
        }
        #lista-carrito {
            max-height: 300px; /* Altura máxima para la lista del carrito */
            overflow-y: auto; /* Scroll vertical si hay muchos elementos */
            padding-right: 10px; /* Espacio para evitar solapamiento del scroll */
        }
    </style>
</head>

<body>
    <h1>HALLMARK by ERICK</h1>
<body>


<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSeo3yEZheXqOGL_4R-v9tyT9RI1ZUGESjVMjG-Viy3GxB5zqQ/viewform?embedded=true" width="640" height="593" frameborder="0" marginheight="0" marginwidth="0">Cargando…</iframe>



<meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Imagen que Ocupa Todo el Ancho de la Ventana</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
        }
        .contenedor-ventana {
            width: 100vw; /* Ancho igual al ancho de la ventana */
            height: 60vh; /* Altura igual a la altura de la ventana */
            overflow: hidden; /* Para evitar que la imagen se desborde de la ventana */
            position: relative; /* Posicionamiento relativo para los contenidos */
        }
        .contenedor-ventana img {
            width: 100%; /* Ancho de la imagen al 100% del contenedor */
            height: auto; /* Altura automática para mantener la proporción */
            object-fit: cover; /* Ajusta la imagen para cubrir el contenedor */
            position: absolute; /* Posicionamiento absoluto para llenar el contenedor */
            top: 0;
            left: 0;
        }
    </style>
</head>
<body>
    <div class="contenedor-ventana">
        <img src="https://gscreativas.com/blog/wp-content/uploads/2020/08/mejores-tiendas-online.jpg" alt="Imagen de ejemplo">
    </div>
    <!-- Contenido de productos -->
        <div class="producto">
        <img src="https://cdn-media.glamira.com/media/product/newgeneration/view/3/sku/gwd-n1061-MEN/alloycolour/white/accent/black/width/w8/profile/prA.jpg" alt="Anillos para hombres">
        <p>Anillos para hombres</p>
        <p>$50.00</p>
        <button onclick="agregarAlCarrito('Producto 1', 50.00)">Agregar al carrito</button>
    </div>
 <div class="producto">
        <img src="https://motopower.vtexassets.com/arquivos/ids/159371/32472-1.jpg?v=638109460763770000" alt="Accesorios motos">
        <p>Accesorios motos</p>
        <p>$50.00</p>
        <button onclick="agregarAlCarrito('Producto 1', 50.00)">Agregar al carrito</button>
    </div>
 <div class="producto">
        <img src="https://th.bing.com/th/id/R.cbe98a25f0bb594dfba81dca2810baa4?rik=hRcMGy6TMvPtrA&riu=http%3a%2f%2fg01.a.alicdn.com%2fkf%2fHTB1SNPgJFXXXXXSXpXXq6xXFXXX4%2fNuevo-multi-capa-collares-para-mujer-Vintage-azul-Crystal-Beads-collares-colgantes-mejores-amigos-accesorios-de.jpg&ehk=UbkxvbKiICZ%2bOFPb%2bK111J5c7Ojw%2fmtya7OC%2fZ8Nuw4%3d&risl=&pid=ImgRaw&r=0" alt="Collares">
        <p>Collares</p>
        <p>$50.00</p>
        <button onclick="agregarAlCarrito('Producto 1', 50.00)">Agregar al carrito</button>
    </div>
 <div class="producto">
        <img src="https://www.aromasyrecuerdos.com/wp-content/uploads/2022/10/PAR-DE-ARETES-Gota-Azul.jpg" alt="Aretes">
        <p>Aretes</p>
        <p>$50.00</p>
        <button onclick="agregarAlCarrito('Producto 1', 50.00)">Agregar al carrito</button>
    </div>
 <div class="producto">
        <img src="https://belcorpecuador.vtexassets.com/arquivos/ids/309047-800-800?v=638545968198070000&width=800&height=800&aspect=true" alt="Perfumes">
        <p>Perfumes</p>
        <p>$50.00</p>
        <button onclick="agregarAlCarrito('Producto 1', 50.00)">Agregar al carrito</button>
    </div>

    
    <div class="producto">
        <img src="https://vasari.vteximg.com.br/arquivos/ids/207129-1000-1000/VGC174169-NG.jpg?v=637963496460300000" alt="Gorras">
        <p>Gorras</p>
        <p>$30.00</p>
        <button onclick="agregarAlCarrito('Producto 2', 30.00)">Agregar al carrito</button>
    </div>
    
    <div class="producto">
        <img src="https://intelcomex.com/wp-content/uploads/2021/09/Accesorios_para_PC.png" alt="Accesorios para pc">
        <p>Accesorios para pc</p>
        <p>$20.00</p>
        <button onclick="agregarAlCarrito('Producto 3', 20.00)">Agregar al carrito</button>
    </div>
  <div class="producto">
        <img src="https://vasari.vteximg.com.br/arquivos/ids/207129-1000-1000/VGC174169-NG.jpg?v=637963496460300000" alt="Gorras">
        <p>Gorras</p>
        <p>$30.00</p>
        <button onclick="agregarAlCarrito('Producto 2', 30.00)">Agregar al carrito</button>
    </div>
    
    <div class="producto">
        <img src="https://www.tiendastec.com/wp-content/uploads/2022/10/PROTECTOR-DE-14-PULGADAS_-Tiendas-TEC.webp" alt="Accesorios para pc">
        <p>Accesorios para pc</p>
        <p>$20.00</p>
        <button onclick="agregarAlCarrito('Producto 3', 20.00)">Agregar al carrito</button>
    </div>
    <div class="producto">
        <img src="https://www.aromasyrecuerdos.com/wp-content/uploads/2022/10/PAR-DE-ARETES-Gota-Azul.jpg" alt="Aretes">
        <p>Aretes</p>
        <p>$50.00</p>
        <button onclick="agregarAlCarrito('Producto 1', 50.00)">Agregar al carrito</button>
    </div>
 <div class="producto">
        <img src="https://belcorpecuador.vtexassets.com/arquivos/ids/309047-800-800?v=638545968198070000&width=800&height=800&aspect=true" alt="Perfumes">
        <p>Perfumes</p>
        <p>$50.00</p>
        <button onclick="agregarAlCarrito('Producto 1', 50.00)">Agregar al carrito</button>
    </div>
<div class="producto">
        <img src="https://cdn-media.glamira.com/media/product/newgeneration/view/3/sku/gwd-n1061-MEN/alloycolour/white/accent/black/width/w8/profile/prA.jpg" alt="Anillos para hombres">
        <p>Anillos para hombres</p>
        <p>$50.00</p>
        <button onclick="agregarAlCarrito('Producto 1', 50.00)">Agregar al carrito</button>
    </div>


    <!-- Carrito de compras -->
    <div class="carrito">
        <ul id="lista-carrito">
            <!-- Aquí se mostrarán los productos agregados al carrito -->
        </ul>
        <p>Total: $<span id="total">0.00</span></p>
    </div>
<!-- Flechas de desplazamiento -->
    <a href="#top" class="flecha">↑</a>
    <a href="#bottom" class="flecha">↓</a>

    <script>
        // Función para agregar un producto al carrito
        function agregarAlCarrito(nombre, precio) {
            var carrito = document.getElementById('lista-carrito');
            var totalElemento = document.getElementById('total');
            
            // Crear nuevo elemento de lista para el producto
            var nuevoProducto = document.createElement('li');
            nuevoProducto.textContent = nombre + ' - $' + precio.toFixed(2);
            carrito.appendChild(nuevoProducto);
            
            // Calcular y actualizar el total
            var totalActual = parseFloat(totalElemento.textContent);
            var nuevoTotal = totalActual + precio;
            totalElemento.textContent = nuevoTotal.toFixed(2);
        }
    </script>
<script src="https://js.stripe.com/v3/"></script>
<!-- Formulario de pago -->
<div id="formulario-pago">
    <form id="payment-form">
        <div id="card-element">
            <!-- Elemento donde se mostrará el campo de la tarjeta -->
        </div>
        <button id="submit-button">Pagar</button>
    </form>
</div>
<head>
<style>
    #formulario-pago {
        max-width: 400px;
        margin: 0 auto;
        background-color: #fff;
        padding: 20px;
        border-radius: 8px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        text-align: center;
    }
    #card-element {
        margin-bottom: 20px;
    }
    #submit-button {
        padding: 10px 20px;
        background-color: #0275d8;
        color: #fff;
        border: none;
        border-radius: 4px;
        cursor: pointer;
        font-size: 16px;
    }
    #submit-button:hover {
        background-color: #025aa5;
    }
</style>
<script>
    var stripe = Stripe('tu_clave_publica_de_stripe');
    var elements = stripe.elements();

    // Elemento de la tarjeta de crédito
    var cardElement = elements.create('card');
    cardElement.mount('#card-element');

    var form = document.getElementById('payment-form');

    form.addEventListener('submit', function(event) {
        event.preventDefault();

        stripe.createPaymentMethod({
            type: 'card',
            card: cardElement,
        }).then(function(result) {
            if (result.error) {
                // Mostrar errores al usuario (puedes modificar según tu diseño)
                var errorElement = document.getElementById('card-errors');
                errorElement.textContent = result.error.message;
            } else {
                // Aquí enviar result.paymentMethod.id a tu servidor para procesar el pago
                console.log(result.paymentMethod.id);
                alert('Pago exitoso');
                // Puedes redirigir o realizar acciones adicionales después del pago
            }
        });
    });
</script>
</head>
</body>
</html>
