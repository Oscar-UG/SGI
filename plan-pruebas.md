# Plan de Pruebas de Software

## Objetivo
Definir los escenarios de verificación para validar que, en una futura etapa de desarrollo, el Sistema de Gestión y Reabastecimiento de Inventario (SGI) cumpla con los requisitos funcionales y las reglas de cálculo establecidas

| ID | Descripción de la Prueba | Entrada de Datos | Resultado Esperado | Estado |
|:---:|---|---|---|:---:|
| CP-01 | Cálculo de reabastecimiento (stock menor al mínimo) | Teclados: stock actual 4, mínimo 10 | Debe calcular 6 unidades a pedir y marcar **REABASTECER** | Pendiente |
| CP-02 | Stock suficiente (stock mayor al mínimo) | Mouse: stock actual 20, mínimo 15 | Debe calcular 0 unidades a pedir y marcar **OK** | Pendiente |
| CP-03 | Stock en el límite exacto | Monitores: stock actual 5, mínimo 5 | Debe calcular 0 unidades a pedir y marcar **OK** | Pendiente |
| CP-04 | Artículo totalmente agotado | Cargadores: stock actual 0, mínimo 12 | Debe aceptar el 0, calcular 12 unidades a pedir y marcar **REABASTECER** | Pendiente |
| CP-05 | Validación de entrada inválida | Audífonos: ingreso de texto o número negativo | Debe rechazar el dato y solicitar un número entero válido | Pendiente |
| CP-06 | Generación de reporte diario | Ingreso válido de los 5 artículos del catálogo | Debe mostrar el reporte completo con estados y cantidades | Pendiente |

## Criterios de Aceptación
Una vez implementado el software, el 100% de estos casos de prueba deberán ejecutarse con éxito antes de liberar el sistema a producción.
