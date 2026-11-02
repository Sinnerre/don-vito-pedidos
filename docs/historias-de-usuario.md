# Historias de usuario – Pizzería "Don Vito"

Las tres historias se gestionan como *issues* en el tablero del proyecto (estados: Por Hacer, En Progreso, Listo).

## Historia 1 – Centralización de pedidos

**Como** encargado del local, **quiero** registrar en una sola plataforma los pedidos de todos los canales, **para** evitar errores y omisiones en la toma de pedidos.

Criterios de aceptación:
- Los pedidos de local, teléfono y aplicaciones se cargan en el mismo sistema.
- Cada pedido queda con su canal de origen y su estado.

## Historia 2 – Asignación automática de repartidores

**Como** encargado de delivery, **quiero** que el sistema asigne automáticamente al repartidor disponible más cercano, **para** reducir el tiempo de entrega.

Criterios de aceptación:
- Un pedido de delivery queda asignado sin intervención manual.
- Si no hay repartidores disponibles, el pedido queda en espera.

## Historia 3 – Control de stock

**Como** encargado de administración, **quiero** que el sistema descuente los ingredientes al confirmar un pedido y bloquee los productos sin stock, **para** no aceptar pedidos que no podemos cumplir.

Criterios de aceptación:
- Al confirmarse un pedido se descuentan los insumos utilizados.
- Si un producto no tiene stock, el sistema no permite agregarlo al pedido.
