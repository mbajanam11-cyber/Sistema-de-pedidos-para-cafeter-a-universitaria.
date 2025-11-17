# Sistema-de-pedidos-para-cafeter-a-universitaria.
Componente practico experimental
# Sistema de Pedidos para Cafetería Universitaria

## Descripción del Caso
El sistema de pedidos para una cafetería universitaria es una aplicación diseñada para facilitar el registro, gestión y seguimiento de los pedidos realizados por estudiantes, docentes y personal administrativo. El sistema permite visualizar el menú disponible, tomar pedidos de manera rápida, gestionar el estado de cada solicitud y optimizar el flujo de atención dentro del establecimiento.

## Objetivos del Sistema
- Agilizar el proceso de toma de pedidos para reducir tiempos de espera.  
- Crear un registro digital organizado y accesible de todos los pedidos.  
- Permitir al personal de la cafetería gestionar estados de pedido.  
- Mejorar la experiencia del usuario mediante una interfaz simple y funcional.  
- Facilitar la generación de datos para decisiones operativas.  

## Requerimientos del Sistema

### **Requerimientos Funcionales**
1. El sistema debe permitir registrar nuevos pedidos seleccionando productos del menú.  
2. El sistema debe mostrar el menú con nombre, precio y disponibilidad.  
3. El sistema debe permitir actualizar el estado del pedido.  
4. El sistema debe generar un identificador único para cada pedido.  
5. El sistema debe permitir consultar el historial de pedidos realizados.  

### **Requerimientos No Funcionales**
1. El sistema debe contar con una interfaz intuitiva y fácil de usar.  
2. El tiempo de respuesta en cada operación no debe superar los 2 segundos.  
3. El sistema debe garantizar la integridad de los datos almacenados.  

## Tabla de Pruebas (Test Cases)

| Caso de Prueba | Descripción | Entrada | Resultado Esperado | Estado |
|----------------|-------------|---------|---------------------|--------|
| CP01 | Registrar pedido | Selección de productos | Pedido registrado con ID único | |
| CP02 | Mostrar menú | — | Lista completa del menú | |
| CP03 | Cambiar estado del pedido | ID de pedido + nuevo estado | Estado actualizado correctamente | |
| CP04 | Consultar historial | — | Lista de pedidos previos | |
| CP05 | Manejo de error: producto no disponible | Producto fuera de stock | Mensaje de advertencia | |

## Tipo de Mantenimiento Propuesto
Se recomienda aplicar **mantenimiento evolutivo**, para incluir nuevas funciones como pagos en línea, reportes, o integración con otros sistemas.  
También se considera necesario un **mantenimiento correctivo** para resolver fallos que puedan surgir con el uso diario.

## Reflexión
Implementar un sistema de pedidos en una cafetería universitaria moderniza la operación, reduce errores en la toma manual de pedidos y mejora la eficiencia del servicio. Además, permite obtener datos clave para optimizar recursos y mejorar la experiencia de los usuarios dentro de la institución.

