# Diccionario de datos inicial – Pizzería "Don Vito"

Entidades críticas del negocio que soportan el flujo del sistema de gestión de pedidos y delivery.

## Entidad: Pedido

Registra cada pedido recibido, sin importar el canal de venta.

| Campo | Tipo de dato | Descripción funcional |
|---|---|---|
| id_pedido | Integer | Identificador único del pedido (clave primaria). |
| id_cliente | Integer | Cliente que realiza el pedido (clave foránea a Cliente). |
| canal | String | Origen del pedido: local, teléfono o aplicación. |
| estado | String | Etapa actual: recibido, en cocina, en reparto, entregado o cancelado. |
| total | Decimal | Importe total del pedido. |

## Entidad: Cliente

Almacena los datos necesarios para contactar al cliente y entregar el pedido.

| Campo | Tipo de dato | Descripción funcional |
|---|---|---|
| id_cliente | Integer | Identificador único del cliente (clave primaria). |
| nombre | String | Nombre del cliente. |
| telefono | String | Teléfono de contacto para confirmar el pedido. |
| direccion | String | Domicilio de entrega para pedidos de delivery. |

## Entidad: Repartidor

Permite la asignación automática de pedidos y el seguimiento de las entregas.

| Campo | Tipo de dato | Descripción funcional |
|---|---|---|
| id_repartidor | Integer | Identificador único del repartidor (clave primaria). |
| nombre | String | Nombre del repartidor. |
| disponible | Boolean | Indica si puede recibir un nuevo pedido. |
| ubicacion_actual | String | Coordenadas actuales, usadas para el tracking y la asignación. |

## Entidad: Insumo

Controla el stock de ingredientes para evitar aceptar pedidos sin disponibilidad.

| Campo | Tipo de dato | Descripción funcional |
|---|---|---|
| id_insumo | Integer | Identificador único del insumo (clave primaria). |
| nombre | String | Nombre del ingrediente (por ejemplo: harina, queso, salsa). |
| stock_actual | Decimal | Cantidad disponible en el local. |
| stock_minimo | Decimal | Cantidad mínima que dispara una alerta de reposición. |
