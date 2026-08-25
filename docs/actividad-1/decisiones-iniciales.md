# Registro de decisiones iniciales

Este documento contiene las decisiones iniciales tomadas a partir del análisis del problema y del contexto de la empresa.

Estas decisiones no representan todavía la arquitectura definitiva ni la selección de tecnologías. Su objetivo es establecer una dirección inicial para la solución y dejar registro de las razones por las cuales se toman estas decisiones.

## 1. Decisiones iniciales

| ID | Decisión | Justificación |
|---|---|---|
| D-001 | Centralizar la información logística | La empresa actualmente maneja información distribuida y esto puede generar duplicaciones, errores y falta de trazabilidad. |
| D-002 | Mantener los sistemas externos existentes | La plataforma no debe reemplazar sistemas como el ERP, CRM o sistema de pagos si estos ya cumplen una función dentro de la empresa. |
| D-003 | Registrar el estado de cada pedido | Permite conocer en qué etapa se encuentra un pedido y facilita el seguimiento de su proceso. |
| D-004 | Validar la disponibilidad del inventario | Es necesario conocer si los productos están disponibles antes de continuar con el proceso de entrega. |
| D-005 | Gestionar las rutas y los repartidores | La plataforma debe facilitar la asignación de pedidos y rutas para mejorar la coordinación de las entregas. |
| D-006 | Registrar las incidencias | Las situaciones como retrasos, entregas fallidas o problemas con los pedidos deben quedar registradas para facilitar su seguimiento. |
| D-007 | Permitir diferentes tipos de usuarios | Los clientes, operadores, administradores, repartidores y personal de soporte tienen diferentes responsabilidades y necesidades de información. |
| D-008 | Mantener trazabilidad de los pedidos | Se debe poder conocer el recorrido de un pedido desde su registro hasta la entrega o cierre de una incidencia. |
| D-009 | Considerar el crecimiento futuro | La solución debe tener en cuenta que pueden aumentar los pedidos, usuarios, almacenes y repartidores. |

---

## 2. Justificación de la solución inicial

A partir del análisis realizado, se propone inicialmente una plataforma centralizada de gestión logística de última milla.

La decisión de centralizar la información se toma porque el principal problema identificado es la falta de una vista completa y actualizada de los pedidos. Al tener la información organizada en un mismo sistema, los diferentes actores podrán consultar los datos que necesitan para realizar sus actividades.

La plataforma estará orientada principalmente a cinco procesos:

1. Gestión de pedidos.
2. Validación de inventario.
3. Gestión de rutas y repartidores.
4. Seguimiento de entregas.
5. Gestión de incidencias.

Esta propuesta busca mejorar la coordinación entre las diferentes áreas y reducir los problemas causados por información duplicada o desactualizada.

---

## 3. Decisiones que todavía no se han tomado

En esta etapa no se han definido aspectos técnicos específicos de la solución.

Todavía queda pendiente decidir:

- Lenguaje o lenguajes de programación.
- Frameworks.
- Base de datos.
- Tipo de arquitectura.
- Infraestructura.
- Servicios en la nube.
- Herramientas de monitoreo.
- Estrategia de despliegue.
- Tecnologías utilizadas para las aplicaciones de los diferentes usuarios.

Estas decisiones se tomarán en etapas posteriores, cuando se tenga una comprensión más completa de las necesidades del negocio, los sistemas existentes y las restricciones del proyecto.

---

## 4. Información que debe confirmarse

Antes de tomar decisiones técnicas definitivas será necesario confirmar:

- Cantidad promedio de pedidos diarios.
- Cantidad de usuarios.
- Cantidad de almacenes.
- Cantidad de repartidores.
- Sistemas que utiliza actualmente la empresa.
- Forma en que se reciben actualmente los pedidos.
- Forma en que se actualiza el inventario.
- Forma en que se gestionan actualmente las rutas.
- Sistemas externos disponibles para integración.
- Requisitos de seguridad y protección de datos.
- Crecimiento esperado de la operación.

Esta información permitirá determinar posteriormente qué características debe tener la arquitectura y qué tecnologías pueden ser adecuadas.

---

## 5. Principio utilizado para las decisiones

La principal idea utilizada para tomar las decisiones iniciales es que la arquitectura debe responder primero a las necesidades del negocio.

Por esta razón, no se seleccionan tecnologías únicamente porque sean conocidas o populares. Primero se busca entender el problema, los usuarios, los procesos, las restricciones y los riesgos.

Las decisiones técnicas definitivas deberán estar justificadas a partir de las necesidades reales del sistema.
