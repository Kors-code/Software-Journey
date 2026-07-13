Primera version 


Como primera version este software va a tener la capacidad de añadir o quitar productos añadir precios y cantidad en inventario 
( Esta vista es especifica para configuracion el usuario va a ver varios botones que le permiten dinamicamente poder jugar con ello 
Y ver en tiempo real como se esta creando la lista de productos y consultarlos en el momento )

El administrador una vez configurado puede ingresar a ventas o caja donde podra en una mesa en especifico añadir los productos y asi este software le calcula al instante cuanto debe cobrarle ala persona 

Una vez pagado el total se suma en ventas del dia y asi cuando la caja le de cierre podremos saber sus ventas del dia y cuando dinero debe tener 

# Reglas de negocio 

Este negocio tendra como regla ala hora de ingresar productos que ingresemos productos tales como pan lechuga etc (Para hamburguesa )

Y el software descuente automaticamente uno de cada producto por cada hamburguesa vendida 

Segundo 
La estructura del software debe ser limpia y clara para evitar fallas de logica 

Un mesero intenta vender 5 hamburguesas, pero solo queda pan para 3.
(El software debe ser capaz de manejar esto y decir no tenemos ingredientes sufcientes Existencias 3 )


Una mesa ya pagó y alguien intenta agregar otra Coca-Cola.


Una persona intenta cerrar caja mientras existe una mesa con una cuenta abierta.
(Aviso no puedes cerrar caja sin cerrar las mesas activas)
Un administrador cambia el precio de la hamburguesa de $20.000 a $25.000 después de que una mesa ya la pidió.
Mantener 20k para todos los pedidos anteriores 
Una Coca-Cola se cae y se rompe. No fue vendida, pero ya no existe en inventario.
Poder añadir estos productos aun apartado llamado perdidos (Puede pasar tambien que se piuerdan )