# Fase 2. Ataques y seguridad de redes

**Objetivo:** comprobar cómo se aprovechan determinados comportamientos de los protocolos y aprender a reconocer y mitigar esas situaciones.

> **Alcance:** las técnicas de suplantación e interceptación se realizan exclusivamente sobre máquinas propias y redes virtuales aisladas. La parte defensiva no es opcional: cada ataque incluye análisis de evidencias y mitigaciones.

## Experimentos

| ID | Experimento | Temas aplicados | Estado |
|----|-------------|-----------------|:------:|
| EXP-009 | Suplantación ARP en una LAN aislada | ARP spoofing, caché ARP, confianza en la red local y detección | ⬜ |
| EXP-010 | Man-in-the-Middle controlado | Intermediación, forwarding, rutas del tráfico y visibilidad de paquetes | ⬜ |
| EXP-011 | Comparación entre HTTP y HTTPS | TLS, cifrado, certificados, confidencialidad e integridad | ⬜ |
| EXP-012 | Inspección de una conexión TLS | Handshake TLS, certificados, SNI cuando corresponda y límites de la inspección | ⬜ |
| EXP-013 | Análisis de suplantación DNS en laboratorio | Resolución de nombres, respuestas falsas, caché DNS y detección | ⬜ |
| EXP-014 | Análisis de un escaneo de puertos | TCP SYN, conexiones completas, puertos abiertos, cerrados y filtrados | ⬜ |
| EXP-015 | Detección de anomalías de red | Tráfico inesperado, patrones de escaneo, conexiones repetitivas y filtros de Wireshark | ⬜ |
| EXP-016 | Defensa de una red local | Segmentación VLAN, aislamiento de equipos, controles anti-spoofing y firewall | ⬜ |

## Resultado esperado

Poder explicar qué condición permitió una interceptación, qué datos quedaron expuestos, qué protección habría cambiado el resultado y qué señales permitirían detectar el incidente.

## Requisitos del laboratorio

- Red virtual en modo aislado (host-only o internal), sin salida a Internet durante las prácticas ofensivas.
- Mínimo tres máquinas: atacante, víctima y gateway.
- Capturas de referencia de la [fase 1](../01-network-fundamentals/) para comparar tráfico normal contra tráfico manipulado.