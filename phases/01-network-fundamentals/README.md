# Fase 1. Fundamentos y análisis de redes

**Objetivo:** comprender cómo se comunican los equipos, identificar protocolos en capturas y establecer una línea de base de funcionamiento normal.

## Experimentos

| ID | Experimento | Temas aplicados | Estado |
|----|-------------|-----------------|:------:|
| EXP-001 | Captura y análisis de tráfico de red | Wireshark, interfaces, paquetes, tramas, filtros de captura y visualización | ⬜ |
| EXP-002 | Análisis de Ethernet y direcciones MAC | Capa de enlace, direcciones MAC, tipos de trama, broadcast y unicast | ⬜ |
| EXP-003 | Resolución de direcciones mediante ARP | Caché ARP, solicitudes y respuestas, IP a MAC, dominio de broadcast | ⬜ |
| EXP-004 | Comunicación IPv4 entre equipos | Direccionamiento IP, máscara, gateway, subredes y tablas de rutas | ⬜ |
| EXP-005 | Diagnóstico de conectividad con ICMP | ping, traceroute, TTL, latencia, pérdida de paquetes y filtrado | ⬜ |
| EXP-006 | Funcionamiento de DHCP | DORA, concesiones, servidor DHCP, gateway, DNS y configuración automática | ⬜ |
| EXP-007 | Resolución DNS | Consultas y respuestas, registros A/AAAA/CNAME, caché y UDP/TCP | ⬜ |
| EXP-008 | Establecimiento y cierre de conexiones TCP | Three-way handshake, SYN, ACK, puertos, secuencias, retransmisiones y cierre | ⬜ |

## Resultado esperado

Poder abrir una captura de Wireshark y explicar qué equipos se comunican, qué protocolo utilizan, qué ocurre en cada etapa y cómo distinguir un funcionamiento normal de una anomalía.

## Relación con la fase siguiente

Las capturas de funcionamiento normal de esta fase son la línea de base contra la que se comparan los ataques de la [fase 2](../02-network-attacks/).