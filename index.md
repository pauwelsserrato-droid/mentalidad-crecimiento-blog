# Automatizando filtros de fechas en Power Query mediante parámetros dinámicos

## Contexto

Durante una práctica de análisis de datos en Power Query debía automatizar el filtrado de registros de ventas según un rango de fechas. El objetivo era evitar modificar manualmente los filtros cada vez que cambiaba el período de análisis, permitiendo reutilizar la consulta de forma más eficiente.

---

## Problema

Inicialmente intenté aplicar un filtro de fechas directamente sobre la consulta. Aunque el resultado era correcto para un período específico, cada nuevo análisis requería editar nuevamente el filtro, lo que hacía el proceso repetitivo y propenso a errores.

Además, desconocía cómo utilizar parámetros dentro de Power Query para realizar un filtrado dinámico.

---

## Acciones realizadas

Para resolver el problema seguí los siguientes pasos:

1. Investigué el funcionamiento de los parámetros en Power Query.
2. Creé un parámetro llamado **FechaInicio**.
3. Configuré el tipo de dato como Fecha.
4. Reemplacé el valor fijo del filtro por el parámetro creado.
5. Probé distintos valores para validar que el filtro funcionara correctamente.
6. Documenté el procedimiento para futuras consultas.

---

## Post-Mortem Constructivo

### ¿Qué ocurrió?

El problema surgió por desconocimiento del uso de parámetros en Power Query.

### ¿Qué aprendí?

Comprendí que los parámetros permiten crear consultas reutilizables y reducen significativamente las modificaciones manuales.

### ¿Qué podría haberse hecho mejor?

Antes de comenzar la implementación debería haber revisado la documentación oficial de Power Query y planificado la estructura de la consulta.

### ¿Qué acciones implementaré en el futuro?

- Documentar el procedimiento antes de comenzar.
- Validar cada cambio de manera incremental.
- Consultar documentación oficial cuando aparezcan nuevas funcionalidades.
- Mantener evidencia de las modificaciones utilizando Git.

---

## Aprendizajes

Esta experiencia reforzó la importancia de adoptar una mentalidad de crecimiento frente a los errores técnicos.

En lugar de considerar el inconveniente como un fracaso, lo utilicé como una oportunidad para comprender una nueva funcionalidad de Power Query y mejorar la calidad de futuras soluciones.

También comprendí el valor de documentar los procesos de forma clara para facilitar el trabajo propio y el de otros integrantes del equipo.

---

## Evidencia de Control de Versiones

Durante el desarrollo de este proyecto se utilizaron Git y GitHub para registrar cada modificación realizada mediante commits, permitiendo mantener un historial de cambios y facilitar futuras mejoras.

---

## Reflexión sobre Feedback Radicalmente Sincero

Durante el desarrollo del ejercicio revisé la documentación con una actitud abierta a recibir observaciones. El feedback recibido permitió mejorar la claridad de las explicaciones, reorganizar algunas secciones y utilizar un lenguaje más simple para que tanto perfiles técnicos como no técnicos pudieran comprender el contenido.

Esta experiencia confirmó que recibir comentarios de manera abierta y respetuosa acelera el aprendizaje y mejora la calidad de la documentación técnica.