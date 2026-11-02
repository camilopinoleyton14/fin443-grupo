# Instrucciones para IA - FIN443

## Contexto
Proyecto grupal de Programación en Finanzas,
Magíster en Finanzas, UAI, 2026.

## Objetivo
Desarrollar código financiero reproducible,
verificable y comprensible.
La pregunta de investigación está pendiente.

## Entorno y estructura
- Lenguaje principal: R.
- datos/: archivos originales.
- codigo/: programas y funciones.
- resultados/: salidas reproducibles.
- Utilizar rutas relativas.
- Documentar cómo ejecutar el código.

## Convenciones financieras
- Retornos diarios simples.
- 252 días bursátiles para anualización.
- CAGR con días calendario / 365,25.
- Desviación estándar muestral.
- Tasa libre de riesgo anual configurable.
- Incluir costos cuando corresponda.

## Validación
- Revisar fechas, duplicados, NA y splits.
- Evitar look-ahead, supervivencia y sobreajuste.
- No utilizar información futura en backtests.
- Comprobar los resultados independientemente.

## Uso de IA
- No inventar datos ni referencias.
- Explicar los supuestos y decisiones.
- Registrar prompts y correcciones en bitácoras.
- Verificar DOI y fuentes académicas.
- Priorizar las instrucciones del profesor.
