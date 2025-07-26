# Propuesta TP DSW

## Grupo
### Integrantes
* 47542 - Hildebrandt, Lucas.

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)
*Nota*: si utiliza un monorepo indicar un solo link con fullstack app.

## Tema
### Descripción
La tienda de indumentaria HL nos contrató para desarrollar un sistema de ventas online. Se especializan en calzado y accesorios, y cuentan con un área de "Outlet" para productos discontinuos o con fallas. El sitio web debe permitir a los clientes buscar productos, filtrarlos, agregarlos al carrito, pagar y elegir entre retiro o envío. También solicitan una función de "favoritos" para guardar productos, y de esos "favoritos" recibir alertas de ofertas, compartir listas y aplicar cupones.

### Modelo

## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Tipo Categoría|
|CRUD dependiente|1. CRUD Producto {depende de} CRUD Categoría<br>2. CRUD Cliente {depende de} CRUD Localidad|
|Listado<br>+<br>detalle| 1. El cliente puede ver un listado de productos filtrado por categoría, como "Zapatillas", "Zapatos", "Accesorios", etc => detalle CRUD Producto<br> 2. El listado muestra nombre, descripción, precio y stock disponible.|
|CUU/Epic|1. Comprar Producto|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Producto<br>2. CRUD Categoría<br>3. CRUD Cliente<br>4. CRUD Favorito<br>5. CRUD Pedidos<br>5. CRUD Administrador<br>7. CRUD Pago|
|CUU/Epic|1. Agregar productos a favoritos<br>2. Recibir alertas de novedades en favoritos<br>3. Compartir lista de favoritos|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Historial de productos filtrados por cliente muestra datos del pedido, estado y descripción.|
|CUU/Epic|1. Cancelación pedido.<br>|
|Otros|1. Envío de notificación por email con ubicación del pedido cuando es despachado.|

