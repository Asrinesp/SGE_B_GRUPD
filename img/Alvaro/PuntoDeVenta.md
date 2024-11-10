##PUNTO DE VENTA PARA EL RESTAURANTE "THE BEAR" (EL OSO)

Después de establecer nuestro modulo de facturación, con el cual podemos emitir ticket de compra y facturas a los clientes. 

Podemos empezar a trabajar con el modulo de **Punto de Venta.**
Este modulo nos ofrece un software con muchas herramientas que nos ayudara a optimizar el tiempo para gestionar las ventas de la empresa. 
En esta ocasión mostraremos el funcionamiento básico del modulo, ejemplificando una venta, cobro y pago en el punto de venta.

ODOO nos permite escoger una clase de productos con el cual trabajar, dependerá de nuestra empresa cual elegir, en este caso elegimos los de la clase Restaurante.

####1. ABRIMOS CAJA
######En este bloque de "Control de Apertura"
Se mostrara el ultimo cierre realizado y con que monto de efectivo se cerró. 
Debido a que empezaremos con 0,00€ tendremos que introducir un monto de efectivo para empezar el día.

![CONTROL DE APERTURA](/SGE_B_GRUPD/img/Alvaro/ODOO_SSHOTS/01_00_CONTROLAPERTURA.png)

Como demo para el cliente, abrimos con 199,99€. 

![CAJAABIERTA](/SGE_B_GRUPD/img/Alvaro/ODOO_SSHOTS//01_01_ABRIRCAJA.png)

Debido a que elegimos la clase empresa Restaurante, tenemos productos por defecto para ofrecer.

![LISTADEPRODUCTOS](/SGE_B_GRUPD/img/Alvaro/ODOO_SSHOTS//01_02_PRODUCTOS.png)


####2. GESTIONANDO PEDIDOS Y ORDENES

Tenemos el Nº de pedido a la esquina superior izquierda y también el botón para agregar más productos, la sección de los productos, la sección de cliente, acciones, también una barra de búsqueda de productos  

![CAJAABIERTA](/SGE_B_GRUPD/img/Alvaro/ODOO_SSHOTS/01_03_PRODUCTOSSEÑALADOS)

Ahora recibimos una orden para el pedido 601 , Beef Sandwich con un precio de 10,89€, al prepararlo, entregarlo y posteriormente cobrarlo. 

####3. COBRO Y PAGOS

Tenemos este menú.
El menú es bastante intuitivo, podemos elegir el metodo de pago, entre tarjeta, efectivo y tambien como cuenta de cliente.(Pero esta ultima necesita otra aplicación).
Tambien podemos activar la opción de factura para los clientes que lo necesiten.
Incluso podemos informatizar al cliente para ahorrarnos tiempo.

![MENU DE COBRO](/SGE_B_GRUPD/img/Alvaro/ODOO_SSHOTS/02_00_COBROMENU.png)

Primero elegimos el metodo de pago, dependiendo cual, al seleccionarlo se introducira el monto del precio completo. 

![PAGOS](/SGE_B_GRUPD/img/Alvaro/ODOO_SSHOTS/02_01_PAGO.png)
 
Podemos utilizar el teclado numerico para agregar las unidades en € del dinero recibido y por recibir, en caso de efectivo restante, se retornara para que la caja pueda cuadrar al finalizar el día.

![PAGOS](/SGE_B_GRUPD/img/Alvaro/ODOO_SSHOTS/02_02_PAGO1.png)

![PAGOS](/SGE_B_GRUPD/img/Alvaro/ODOO_SSHOTS/02_03_PAGO2.png)

Si el cliente nos paga en efectivo, sin restante, al validarlo, se imprimira el ticket de compra, con la opción de enviarlo por correo al cliente y también **imprimirlo en papel**
en caso el cliente lo requiera.

![PAGOS](/SGE_B_GRUPD/img/Alvaro/ODOO_SSHOTS/02_04_PANTALLAFINAL_VENTA.png)

####4. CIERRE DE CAJA

Al finalizar el día necesitaremos saber el efectivo que hay en caja en nuestro punto de venta, para cerrar caja nos dirigiremos a las opciones a la esquina superior derecha.
Seleccionamos Cerrar caja registradora. 
Y tenemos el menú donde nos detalla el efectivo de apertura los Pagos en efectivo cobrados, Entrada y Salida de efectivo, el dinero contado.

En caso de tener pagos en Tarjeta también nos lo indicara en esta sección. Lo mismo con la cuenta del cliente.
También podemos descargar un reporte de ventas del día.

![PAGOS](/SGE_B_GRUPD/img/Alvaro/ODOO_SSHOTS/03_CIERRACAJA.png)

Entonces introducimos el efectivo que se encuentra en caja en este caso 221,77€.
Conforme a ello Cerramos la caja.

