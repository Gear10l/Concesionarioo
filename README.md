# Grupo_5_Concesionarioo
Sistema de software para administrar las operaciones de un concesionario de vehículos, centraliza información de vehículos, clientes, inventario y ventas.



Fase 1 

Mini proyecto: Sistema de gestión de un concesionario de vehículos 

Descripción del sistema:  La idea es desarrollar un sistema de software que permita administrar las operaciones de un concesionario de vehículos. 

Sera una aplicación que centralice la información de los vehículos, clientes, inventario y ventas. 

El ecosistema de este proyecto está compuesto por los usuarios, los procesos y los módulos que permiten administrar de manera organizada las operaciones del concesionario.  

Componentes del ecosistema: 
Relacion entre los actores: Los actores principales que interactúan en el ecosistema son los siguientes y de la siguiente manera: 

Administrador: Aquel que supervisa y controla el funcionamiento del ecosistema. 

Vendedores: Quienes utilizan el ecosistema para atender y gestionar las ventas. 

Clientes: Proporcionan sus datos con el fin de comprar el vehículo de su interés. 

Entre los actores también encontramos partes del ecosistema que actúan en el sin ser un usuario como: 

Módulo de inventario: informa sobre vehículos disponibles. 

Módulo de ventas: registra transacciones y actualiza la información correspondiente. 

Base de datos: conecta los diferentes módulos y conserva los datos necesarios para el funcionamiento del ecosistema. 

 

¿Como funciona el ecosistema? 

El funcionamiento del sistema comienza cuando u usuario autorizado inicia sesión. Según su rol puede realizar unas tareas específicas. 

El administrador puede registrar vehículos, actualizar sus datos, gestionar usuarios y consultar reportes. Por su parte, el vendedor puede consultar el inventario disponible, registrar la información de los clientes y realizar el proceso de venta. 

Cuando se concreta una venta, el sistema registra la transacción, relaciona al cliente con el vehículo adquirido y actualiza la disponibilidad del vehículo en el inventario. Toda esta información queda almacenada en la base de datos, lo que permite mantener los registros organizados y evitar inconsistencias. 

Flujo de información y procesos 

El administrador registra vehículos y sus características 

El vendedor consulta el inventario para conocer la disponibilidad 

Se registra la información del cliente interesado 

Se selecciona el vehículo a comprar 

Se registra la venta en el sistema 

El inventario se actualiza  

La información se guarda y queda almacenada 


Beneficios del ecosistema:  

La implementación del ecosistema tiene los siguientes beneficios: 

Información organizada y centralizada 

Mayor control del inventario de vehículos 

Registros de clientes y ventas ordenados 

Reducción de errores asociados al manejo de inventario manual 

Consulta rápida de inventario y ventas 

Mejor seguimiento de operaciones 

Apoyo a la toma de decisiones mediante reportes 

Fase 2  

Modelo patrones  

- Factory Method 

En nuestro sistema de concesionario implementaremos el patrón Factory Method para organizar la creación de los diferentes tipos de vehículos. La fábrica se encargará de decidir qué tipo de objeto crear según la selección del usuario. Esto permitirá centralizar la lógica de creación, reducir la repetición de código y facilitar la incorporación de nuevos tipos de vehículos. 

-Facade 

En nuestro concesionario implementaremos el patrón Facade para facilitar y organizar el proceso de venta de vehículos. Este permitirá realizar varias acciones, como verificar la disponibilidad del vehículo, registrar la venta, actualizar el inventario y generar el comprobante, de una manera más sencilla y ordenada, sin tener que gestionar cada paso por separado. 

-Iterator 

 Actúa en el concesionario como un asistente que unifica el inventario: sin importar si un auto está registrado en una lista digital, en papel o por sucursal, este se encarga de buscarlo y mostrártelo uno por uno de forma idéntica. Esto permite que tus vendedores consulten, filtren u ordenen los vehículos por precio o antigüedad de manera independiente y fluida, evitando que el sistema falle o se complique si en el futuro decides cambiar la forma de guardar los datos de tus vehículos. 

-State 

En nuestro concesionario implementaremos el patrón State para gestionar los diferentes estados de un vehículo, como disponible, reservado, en taller o vendido. Esto permitirá que el sistema actúe de manera diferente según la situación del vehículo. Por ejemplo, si está disponible, se podrá vender; pero si está en taller, no se permitirá realizar la venta. Así podremos controlar mejor las operaciones y evitar errores en el sistema. 

Integrantes:
Gabriela Maria Puentes Gil
Manuel Felipe Cifuentes Torres
Jesus Sebastian Medina Carlos
Cesar Duvan Lozano Bastidas
