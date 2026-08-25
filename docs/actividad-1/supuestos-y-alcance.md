# Supuestos, alcance y restricciones

## 1. Alcance del sistema

La plataforma estará enfocada en la gestión de la logística de última milla de la empresa. Su objetivo principal será centralizar la información de los pedidos y facilitar la coordinación entre los diferentes actores involucrados en el proceso de entrega.

### Dentro del alcance

La primera versión de la plataforma contempla:

- Registrar y consultar pedidos.
- Consultar y validar la disponibilidad del inventario.
- Gestionar la preparación de pedidos.
- Asignar pedidos a rutas y repartidores.
- Realizar seguimiento al estado de las entregas.
- Registrar y consultar incidencias.
- Facilitar al área de soporte la consulta de información sobre los pedidos.
- Intercambiar información con sistemas externos necesarios para la operación.

### Fuera del alcance

En esta etapa no se contempla desarrollar desde cero otros sistemas que la empresa pueda utilizar actualmente.

Quedan inicialmente fuera del alcance:

- Crear una tienda virtual completa.
- Crear un sistema de pagos propio.
- Crear un ERP.
- Crear un CRM.
- Reemplazar todos los sistemas actuales de la empresa.
- Administrar directamente todos los procesos financieros y contables de la organización.

Estos sistemas pueden mantenerse como sistemas externos y comunicarse con la plataforma cuando sea necesario.

---

## 2. Supuestos

Para realizar el diagnóstico inicial se tienen en cuenta los siguientes supuestos:

- La empresa continuará recibiendo pedidos desde diferentes canales.
- La empresa cuenta con uno o varios almacenes para manejar el inventario.
- Los repartidores necesitan recibir información sobre los pedidos y las rutas asignadas.
- Los repartidores tendrán algún medio para actualizar el estado de sus entregas.
- La empresa utiliza o utilizará sistemas externos para procesos como pagos, notificaciones, geolocalización y gestión empresarial.
- Los diferentes usuarios tendrán diferentes niveles de acceso dependiendo de sus funciones.
- La cantidad de pedidos puede aumentar con el crecimiento de la empresa.
- La información de los pedidos debe mantenerse actualizada para que las diferentes áreas puedan trabajar correctamente.
- El área de soporte necesita consultar información actualizada para atender las solicitudes de los clientes.

Estos supuestos deberán confirmarse posteriormente con información real de la empresa antes de tomar decisiones definitivas sobre la solución.

---

## 3. Restricciones

Durante el desarrollo de la solución se deben tener en cuenta algunas restricciones que pueden afectar las decisiones futuras.

### Dependencia de sistemas externos

La plataforma tendrá que interactuar con sistemas como pagos, geolocalización, notificaciones y ERP o CRM. Esto significa que algunas funciones dependerán de sistemas que no son controlados directamente por la plataforma.

### Protección de la información

El sistema manejará información relacionada con clientes, pedidos, direcciones y operaciones. Por lo tanto, será necesario tener en cuenta la seguridad y protección de la información.

### Conectividad

Algunos actores, especialmente los repartidores, necesitarán conexión para consultar información y actualizar el estado de las entregas. Una conexión inestable podría afectar algunas operaciones.

### Crecimiento de la operación

La solución debe considerar que la cantidad de pedidos, usuarios, almacenes y repartidores puede aumentar con el tiempo.

### Sistemas existentes

La empresa puede tener sistemas que ya utiliza para diferentes procesos. La nueva plataforma debe considerar la posibilidad de integrarse con ellos en lugar de asumir que serán reemplazados completamente.

### Información incompleta

En esta etapa todavía no se conoce toda la información relacionada con la operación real de la empresa. Por esta razón, algunas decisiones deberán confirmarse posteriormente.

---

## 4. Límites iniciales del sistema

El límite principal de la plataforma será la gestión de la información relacionada con la logística de última milla.

La plataforma será responsable de centralizar y gestionar información sobre:

- Pedidos.
- Inventario relacionado con los pedidos.
- Preparación.
- Rutas.
- Repartidores.
- Entregas.
- Incidencias.

Los sistemas externos, como el sistema de pagos, el servicio de geolocalización, el sistema de notificaciones y el ERP o CRM, estarán fuera de la plataforma, pero podrán intercambiar información con ella.

Por lo tanto, la plataforma no busca reemplazar todos los sistemas de la empresa, sino servir como punto central para coordinar la operación logística.

---

## 5. Aspectos que deben confirmarse

Antes de definir la arquitectura y las tecnologías definitivas será necesario conocer:

- Cuántos pedidos recibe diariamente la empresa.
- Cuántos almacenes existen.
- Cuántos repartidores participan en la operación.
- Qué canales utilizan actualmente los clientes para realizar pedidos.
- Qué sistemas de ERP y CRM utiliza la empresa.
- Qué sistema de pagos se utiliza actualmente.
- Qué servicio de geolocalización se utiliza.
- Cómo se gestionan actualmente las rutas.
- Cómo se actualiza actualmente el estado de los pedidos.
- Qué información necesita exactamente el área de soporte.
- Qué políticas de seguridad y protección de datos debe cumplir la empresa.
- Cuál es el crecimiento esperado de la operación.

Estas preguntas permitirán reducir las dudas actuales y tomar decisiones más acertadas en las siguientes etapas del proyecto.
