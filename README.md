# Trabajo Práctico Integrador y Progresivo (TPI) – Entrega N.º 4
**Organización Empresarial** · Tecnicatura Universitaria en Programación a Distancia (TUPAD) · Universidad Tecnológica Nacional (UTN)

## Descripción del sistema

"Don Vito" es una pizzería de gestión familiar con local de atención al público, cocina propia y servicio de delivery. Este repositorio aloja la documentación técnica del módulo de software propuesto: un **sistema de gestión de pedidos y delivery** que:

- centraliza en una sola plataforma los pedidos de todos los canales (local, teléfono y aplicaciones de mensajería);
- asigna automáticamente a los repartidores y permite seguir las entregas en tiempo real;
- se integra con Inventario (descuento de insumos y control de stock) y con Facturación (comprobante de venta).

## Integrantes

- Marcos Federico Sinner

Docente titular: Prof. Gabriela Martínez.

Docentes adjuntos: Prof. Carolina Bruno, Prof. Mario Raúl López, Prof. Andrea Ramos.

## Indicadores de control y estándares de desempeño

Los indicadores derivan de las metas definidas en la Entrega N.º2 y sirven para auditar técnicamente el sistema una vez implantado.

| Indicador | Cómo se mide | Estándar de desempeño | Frecuencia |
|---|---|---|---|
| Cobertura de canales | Pedidos registrados en el sistema / pedidos totales | 100 % | Semanal |
| Tasa de error en pedidos | Pedidos con error u omisión / pedidos totales | Menor al 2 % | Semanal |
| Asignación automática | Pedidos de delivery asignados sin intervención manual / pedidos de delivery | Al menos 95 % | Semanal |
| Tiempo promedio de entrega | Tiempo entre la confirmación del pedido y la entrega | Reducción del 15 % respecto de la situación inicial | Mensual |
| Integridad del stock | Pedidos confirmados que descontaron insumos / pedidos confirmados; pedidos aceptados sin stock | 100 % | Semanal |
| Facturación automática | Ventas con comprobante generado automáticamente / ventas totales | 100 % | Semanal |
| Disponibilidad del sistema | Tiempo en servicio / tiempo del horario comercial | Al menos 99 % | Mensual |

## Declaración de uso de IA

**Asistente utilizado:** Claude Sonnet 5.5.

**Para qué se usó:** Editar el BPMN (achicarlo horizontalmente) y que me de una imagen .png del mismo. También se utilizó para ayudar a redactar los indicadores de control y estándares de desempeño.
**Prompts principales y justificación:**

- *"(Adjuntando el archivo .bpmn) Podes achicarlo más horizontalmente al bpmn, y después pasármelo de vuelta en png?"*.
   El .png original era muy grande horizontalmente, y en el PDF la imagen quedaba muy chica para ser leible. Consideré que pedirle a la IA que lo achicara y que luego me devuelva un png era más sencillo que hacerlo manualmente.
- *"(Habiendo adjuntado las entregas anteriores) me quedan los indicadores y el README, qué sigue?"*.
  No lo pedí originalmente, pero a partir de este prompt, me ayudó a redactar los indicadores y estándares de desempeño a partir de mis entregas anteriores automáticamente. 

**Correcciones humanas sobre los resultados de la IA:**

- Se hizo correcciones en el texto de indicadores y estándares, eliminando palabras de más y ajustando algunos porcentajes erróneos.
