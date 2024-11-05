# Tienda de Focos
Este es un proyecto de tienda de focos desarrollado como parte de un proyecto escolar, utilizando HTML, CSS (con Bootstrap) y JavaScript. La tienda simula una plataforma de e-commerce que permite visualizar productos, agregarlos al carrito y gestionarlos.

Características del Proyecto
1. Productos y Categorías
Los productos están almacenados en un archivo productos.json, que contiene dos categorías: focos led y accesorios.
Al cargar la tienda, los productos de este archivo se cargan en el local storage para su gestión en la aplicación.
2. Navegación y Búsqueda
Filtros de Categoría: En la barra de navegación, los usuarios pueden filtrar los productos por las categorías disponibles.
Barra de Búsqueda: Incluye una barra de búsqueda que permite buscar productos por nombre o características.
3. Carrito de Compras
Cada producto tiene un botón de "Agregar al carrito", que guarda el producto en el local storage.
Página de Carrito: Permite visualizar los productos agregados.
Opciones en el carrito:
Vaciar Carrito: Elimina todos los productos del carrito.
Comprar: Al elegir esta opción, se vacía el carrito y se muestra un mensaje de agradecimiento, seguido de una redirección a una página 404, de acuerdo a las consignas del proyecto.
4. Panel de Administración
Inicio de Sesión para Administrador: Permite al usuario con permisos de administrador acceder a funciones adicionales.
Gestión de Productos:
Agregar nuevos productos: Permite añadir nuevos productos al local storage.
Resetear el local storage: Restaura los productos originales desde productos.json.
Tecnologías Utilizadas
HTML: Para la estructura del sitio.
CSS & Bootstrap: Para el diseño y estilo responsivo de la tienda.
JavaScript: Para la lógica de la aplicación, gestión de productos en el carrito y funciones de administrador.
Local Storage: Para almacenar productos del carrito y persistir datos de productos agregados o modificados.
Estructura del Proyecto
index.html: Página principal de la tienda, donde se visualizan los productos y se pueden filtrar o buscar.
productos.json: Archivo JSON que contiene los productos iniciales con sus categorías y detalles.
carrito.html: Página del carrito de compras, donde el usuario puede ver y gestionar los productos agregados.
admin.html: Página de administración donde se pueden agregar nuevos productos o restaurar los productos originales.
Cómo Usar la Tienda
Navegar entre las categorías y buscar productos con la barra de búsqueda.
Agregar productos al carrito y visualizar los seleccionados en la página de carrito.
Completar la compra para vaciar el carrito y ver un mensaje de agradecimiento.
Iniciar sesión como administrador para gestionar el catálogo de productos.
Notas Finales
Este proyecto es una simulación de una tienda en línea y está diseñado como una práctica escolar. No realiza transacciones reales y está limitado a funciones de front-end.
