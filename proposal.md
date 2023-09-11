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
El sistema a desarrollar tiene como objetivo principal apoyar la gestión de ventas y control de productos de un emprendimiento de impresiones 3d:
* Registro de insumos y clientes.
* Organización de productos en categorías.
* Registro de pedidos de clientes.


### Modelo
![8c4ca3bf-f762-4d11-a230-07820584717c](https://github.com/maticatala/Propuesta--TP--Ecommerce3D/assets/117945432/aef55e09-28f1-402f-ad6a-0b26fca6322f)


## Alcance Funcional 


### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Provincia<br>2. CRUD Categoria<br>3. CRUD Insumos|
|CRUD dependiente|1. CRUD Cliente {depende de} CRUD Localidad y CRUD provincia<br>2. CRUD Producto {depende de} CRUD categoria|
|Listado<br>+<br>detalle| 1. Listado de Productos filtrado por tipo de categoria, muestra idCategoria y nombre de categoria y nombre del producto => detalle listado completo de los datos del producto y de la categoria<br> 2. Listado de Pedidos filtrado por rango de fecha, muestra nro de pedido, fecha en la que se realiza, cuit y nombre del cliente => detalle muestra datos completos del y del cliente|
|CUU/Epic|1. Registrar pedido para un cliente<br>2. Cancelar pedido de un cliente|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Precio<br>2. CRUD Pedidos<br>3. CRUD Localidad<br>4. CRUD Provincias<br>5. CRUD prod_ins<br>6. CRUD Marca|
|CUU/Epic|1. Realizar facturacion del pedido<br>2. Registrar historial de precios de las marcas de los plásticos<br>3. Informar pedidos pendientes|

