# Reporte ejecutivo: encuesta a distribuidoras

## Objetivo

Identificar por qué las distribuidoras dejan de colocar, qué valoran de otras financieras y qué condiciones podrían favorecer su reactivación o exclusividad.

## Base analizada

- 377 intentos de llamada.
- 64 llamadas efectivas (17.0% del total).
- 64 distribuidoras únicas con respuesta efectiva.
- 0 registros efectivos con id_cliente duplicado.

## Hallazgos

- **Satisfacción:** 47 de 63 calificaciones válidas fueron 4 o 5 (74.6%). Satisfacción y actividad comercial no son equivalentes.
- **Colocación:** la falta o dificultad para conseguir clientes es la señal más frecuente en P1 y debe ser la primera hipótesis de intervención.
- **Competencia:** 54 respuestas fueron "Sí", 6 "No" y 1 requieren revisión por texto no estandarizado.
- **Disposición:** P5 tiene 26 respuestas "Sí", 6 "Tal vez" y 4 "No". Los faltantes son condicionales del cuestionario y no deben contarse automáticamente como rechazo.
- **Necesidades:** P4 concentra señales sobre condiciones financieras, apoyo operativo/comercial, clientes confiables y herramientas digitales.

## NLP exploratorio

Se aplicó TF-IDF + NMF por separado a P1 y P4. Los grupos encontrados apuntan a clientes/colocación, temor o falta de actividad, condiciones financieras, exclusividad y búsqueda de clientes. Son señales exploratorias, no categorías definitivas ni porcentajes oficiales.

## Sentimiento del texto libre

Un diccionario de palabras positivas/negativas con negación simple (sección 10) clasifica 23 de 64 respuestas de P1 (motivo) como abiertamente negativas en tono. A nivel general, 38 distribuidoras tienen un tono general positivo, 13 neutro y 12 negativo. Es una señal complementaria a la calificación cerrada de P2, no un reemplazo.

## Recomendaciones

1. Priorizar recuperación de clientes y acompañamiento comercial.
2. Revisar plazos, fechas de pago, disponibilidad, intereses y comisiones frente a la competencia.
3. Reforzar gestoría, cobranza, atención y seguimiento de coordinadores.
4. Evaluar mejoras en la aplicación y opciones digitales.
5. Recontactar primero a quienes respondieron "Sí" o "Tal vez" en P5.
6. Validar manualmente los temas NLP antes de usarlos como indicadores.

## Limitaciones

La muestra tiene 64 respuestas, las preguntas abiertas son breves y contienen errores ortográficos y respuestas ambiguas. El reporte describe señales de esta muestra y no permite generalizar a todas las distribuidoras sin una muestra mayor.


## Segmentación de recontacto

- Prioridad alta: 32 distribuidoras.
- Prioridad media: 26 distribuidoras.
- Baja o indeterminada: 6 distribuidoras.
- La región con más casos de alta prioridad es SUR.

El listado detallado está en `segmentos_recontacto.csv` y el guion operativo en `plan_recontacto.md`.
