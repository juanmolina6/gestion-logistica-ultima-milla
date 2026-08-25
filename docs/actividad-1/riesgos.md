# Registro de riesgos

En esta etapa se identifican los principales riesgos que podrían afectar el funcionamiento de la plataforma de gestión logística de última milla.

Los riesgos se identifican desde el contexto actual del negocio y no representan todavía una solución definitiva. Su objetivo es conocer los posibles puntos de falla que deberán tenerse en cuenta durante las siguientes etapas del proyecto.

## 1. Riesgos identificados

| ID | Riesgo | Descripción | Consecuencia | Prioridad |
|---|---|---|---|---|
| R-001 | Duplicación de pedidos | Un mismo pedido podría registrarse más de una vez desde diferentes canales o procesos. | Entregas duplicadas, errores en la información y aumento de costos. | Alta |
| R-002 | Inconsistencias de inventario | La información sobre la disponibilidad de un producto podría no estar actualizada. | Se podrían aceptar pedidos de productos que realmente no están disponibles. | Alta |
| R-003 | Entregas retrasadas | Una mala coordinación de rutas, almacenes o repartidores podría retrasar las entregas. | Reclamos de clientes y una mala experiencia de compra. | Alta |
| R-004 | Entregas fallidas | El pedido podría no ser entregado por problemas con la dirección, el cliente o el repartidor. | Costos adicionales y necesidad de coordinar una nueva entrega. | Alta |
| R-005 | Pérdida de trazabilidad | Podría no quedar registrada correctamente la información sobre los cambios de estado de un pedido. | Dificultad para saber qué ocurrió y resolver reclamos. | Alta |
| R-006 | Mala coordinación entre áreas | Almacenes, repartidores y soporte podrían trabajar con información diferente. | Errores operativos y retrasos en el proceso. | Media |
| R-007 | Crecimiento de la operación | El aumento de pedidos, usuarios y repartidores podría superar la capacidad inicialmente prevista. | Problemas para mantener una operación estable y organizada. | Media |
| R-008 | Problemas de seguridad | Personas no autorizadas podrían acceder a información de clientes o de la operación. | Pérdida o exposición de información y posibles problemas para la empresa. | Alta |
| R-009 | Dependencia de sistemas externos | Una falla en pagos, geolocalización, notificaciones o ERP/CRM podría afectar algunos procesos. | Interrupciones o retrasos en determinadas funciones. | Media |
| R-010 | Información desactualizada | La información del estado de un pedido podría no actualizarse a tiempo. | El cliente y los empleados podrían recibir información incorrecta. | Alta |

## 2. Riesgos principales

Aunque existen varios riesgos, los que se consideran más importantes en esta primera etapa son los siguientes:

### Duplicación de pedidos

Es uno de los riesgos principales porque la empresa recibe pedidos desde diferentes canales. Si no existe una correcta coordinación de la información, un mismo pedido podría aparecer más de una vez.

### Inconsistencias de inventario

La disponibilidad de los productos es fundamental para poder cumplir los pedidos. Si la información no está actualizada, se podrían generar pedidos que posteriormente no puedan ser preparados.

### Retrasos o fallas en las entregas

La entrega es una de las partes más importantes del proceso de última milla. Problemas con las rutas, los almacenes o los repartidores pueden afectar directamente al cliente.

### Pérdida de trazabilidad

La empresa necesita conocer qué ha ocurrido con cada pedido. Si no se registra correctamente su recorrido y los cambios de estado, será más difícil solucionar problemas o responder a los clientes.

### Seguridad de la información

La plataforma manejará información relacionada con clientes y operaciones, por lo que debe considerarse la posibilidad de accesos no autorizados o pérdida de información.

## 3. Tratamiento inicial de los riesgos

En esta etapa todavía no se define una solución técnica para cada riesgo. Sin embargo, se considera importante que estos sean tenidos en cuenta durante el diseño posterior del sistema.

Las siguientes etapas deberán analizar cómo reducir la posibilidad de que estos riesgos ocurran y cómo responder en caso de que se presenten.

Por ejemplo, la duplicación de pedidos deberá ser controlada mediante una correcta identificación de cada pedido; las inconsistencias de inventario requerirán información actualizada; y la pérdida de trazabilidad deberá considerarse desde el momento en que se registra un pedido hasta que finaliza su entrega.

## 4. Seguimiento

Los riesgos identificados deberán revisarse nuevamente durante las siguientes etapas del proyecto, ya que pueden aparecer nuevos riesgos cuando se conozcan más detalles de la operación y de los sistemas existentes.

La prioridad de los riesgos también podrá cambiar cuando se obtenga información real sobre la cantidad de pedidos, usuarios, almacenes, repartidores y sistemas externos involucrados.
