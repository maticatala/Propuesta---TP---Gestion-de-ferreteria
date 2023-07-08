# Propuesta TP DSW

## Grupo
### Integrantes
* 47899 - Catala, Matias
* 49417 - Gnavi Faustino
* 49487 - Pieroni Tiago
* 49475 - Tosello Mateo
* 49121 - Verano Federico

### Repositorios
* [Frontend SG_Ferreteria](https://github.com/maticatala/FrontEndFerreteria)
* [Backend SG_Ferreteria](https://github.com/maticatala/BackEndFerreteria)

## Tema
### Descripción
El sistema a desarrollar para la ferretería tiene como objetivo principal apoyar la
gestión de ventas y control de productos:
* Registro de proveedores y clientes.
* Organizacion de productos en categorias.
* Resgistro de pedidos de clientes


### Modelo
![EF1 8_Ferretería drawio (1)](https://github.com/maticatala/Propuesta---TP---Gestion-de-ferreteria/assets/117945432/fb911fb9-13fe-4857-8142-26eafcaf2301)

## Alcance Funcional 


### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Provincia<br>2. CRUD Categoria<br>3. CRUD Proovedores|
|CRUD dependiente|1. CRUD Cliente {depende de} CRUD Localidad y CRUD provincia<br>2. CRUD Producto {depende de} CRUD categoria|
|Listado<br>+<br>detalle| 1. Listado de Productos filtrado por tipo de categoria, muestra idCategoria y nombre de categoria y nombre del producto => detalle listado completo de los datos del producto y de la categoria<br> 2. Listado de Pedidos filtrado por rango de fecha, muestra nro de pedido, fecha en la que se realiza, cuit y nombre del cliente => detalle muestra datos completos del y del cliente|
|CUU/Epic|1. Registrar pedido para un cliente<br>2. Cancelar pedido de un cliente|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Precio<br>2. CRUD Pedidos<br>3. CRUD Localidad<br>4. CRUD Descuentos<br>5. CRUD prod_prov
|CUU/Epic|1. Realizar facturacion del pedido<br>2. Registrar historial de precios de los productos de un proveedor<br>3. Informar pedidos para una fecha|

