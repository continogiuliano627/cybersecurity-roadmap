# Fase 5. Detección, respuesta y automatización

**Objetivo:** transformar el conocimiento de ataques en capacidades de análisis defensivo, aplicables a puestos de Blue Team y seguridad de aplicaciones.

## Experimentos

| ID | Experimento | Temas aplicados | Estado |
|----|-------------|-----------------|:------:|
| EXP-034 | Análisis de logs de autenticación | journalctl, logs SSH, eventos de login y accesos fallidos | ⬜ |
| EXP-035 | Construcción de una línea temporal de incidentes | Correlación temporal, eventos, conexiones, procesos y reconstrucción de actividad | ⬜ |
| EXP-036 | Detección de escaneos y conexiones anómalas | Reglas de detección, patrones de red, umbrales y falsos positivos | ⬜ |
| EXP-037 | Introducción a un IDS | Suricata o Snort, reglas, alertas, firmas y análisis de paquetes | ⬜ |
| EXP-038 | Análisis de archivos sospechosos sin ejecutarlos | Hashes, metadatos, indicadores de compromiso y análisis estático básico | ⬜ |
| EXP-039 | Automatización de análisis con Python | Procesamiento de logs, expresiones regulares, JSON, CSV, estadísticas y generación de alertas | ⬜ |

## Resultado esperado

Construir un pequeño flujo de detección que procese evidencias, genere alertas justificadas y permita explicar por qué una actividad merece investigación.

## Fuentes de evidencia

Los ataques reproducidos en las fases [2](../02-network-attacks/), [3](../03-web-security/) y [4](../04-linux-security/) generan los logs y capturas que se analizan aquí.

> **Alcance:** el análisis de archivos sospechosos (EXP-038) es estático. No se ejecutan las muestras.