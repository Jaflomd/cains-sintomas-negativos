# CAINS · Evaluación de síntomas negativos

Aplicación web, de acceso abierto, para aplicar y registrar la **Clinical Assessment Interview for Negative Symptoms (CAINS)** en su versión en castellano.

**Usar en línea:** https://jaflomd.github.io/cains-sintomas-negativos/

## Qué hace

- **Entrevista:** un ítem por pantalla, con introducción, pregunta de entrada, ramas (con o sin contacto, con o sin papel laboral), preguntas de seguimiento y anclas 0–4.
- **Ayuda de conteo:** en los ítems de frecuencia (3, 4, 6, 8 y 9) se marcan días o experiencias y la app sugiere el puntaje que corresponde a las anclas.
- **Ítems de expresión (10–13):** guía de observación; se puntúan al final, con lo observado en toda la entrevista.
- **Registro rápido:** los 13 ítems en una tabla, para transcribir una entrevista ya hecha.
- **Resultado:** MAP (0–36), EXP (0–16), total (0–52), subescalas y alertas de coherencia (pareja puntuada dos veces, puntaje distinto al conteo).
- **Salidas:** resumen para la historia clínica, hoja imprimible A4 con firma y CSV.
- **Seguimiento:** historial local y cambio frente a la evaluación previa del mismo ID.

## Estructura

| Subescala | Ítems | Rango |
|---|---|---|
| Social (motivación y placer) | 1–4 | 0–16 |
| Trabajo y escuela (motivación y placer) | 5–6 | 0–8 |
| Recreación y entretenimiento (motivación y placer) | 7–9 | 0–12 |
| Expresión | 10–13 | 0–16 |
| **MAP** (motivación y placer) | 1–9 | 0–36 |
| **EXP** (expresión) | 10–13 | 0–16 |

## Privacidad

Es un solo archivo HTML. No envía datos a ningún servidor. Las respuestas se guardan solo en el navegador de quien la usa (`localStorage`). Use iniciales o un código, nunca el nombre completo del paciente.

También funciona sin internet: descargue `index.html` y ábralo en el navegador.

## Advertencias

- No reemplaza el manual ni el entrenamiento oficial de la CAINS.
- La CAINS no tiene puntos de corte de severidad validados. Mayor puntaje = mayor déficit.
- Es una herramienta de apoyo. No sustituye el juicio clínico.

## Referencias

- Kring AM, Gur RE, Blanchard JJ, Horan WP, Reise SP. The Clinical Assessment Interview for Negative Symptoms (CAINS): final development and validation. *Am J Psychiatry*. 2013;170(2):165–172.
- Valiente-Gómez A, Mezquida G, Romaguera A, et al. Validation of the Spanish version of the Clinical Assessment for Negative Symptoms (CAINS). *Schizophr Res*. 2015.

La escala CAINS pertenece a sus autores. Este proyecto no está afiliado a ellos.

## Autor

MEd MC Javier A. Flores Cohaila · ORCID [0000-0002-9169-2094](https://orcid.org/0000-0002-9169-2094)

## Licencia

Código bajo licencia MIT (ver `LICENSE`).
