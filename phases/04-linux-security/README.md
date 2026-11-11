# Fase 4. Seguridad de Linux y servicios

**Objetivo:** comprender cómo se protege un sistema operativo y cómo una configuración incorrecta puede abrir una vía de acceso.

## Experimentos

| ID | Experimento | Temas aplicados | Estado |
|----|-------------|-----------------|:------:|
| EXP-027 | Usuarios, grupos y permisos Linux | chmod, chown, permisos tradicionales, umask y privilegio mínimo | ⬜ |
| EXP-028 | Procesos, servicios y puertos de escucha | ps, ss, systemctl, procesos, sockets y servicios expuestos | ⬜ |
| EXP-029 | Configuración segura de SSH | Autenticación por claves, acceso remoto, permisos y endurecimiento de configuración | ⬜ |
| EXP-030 | Análisis de permisos y configuraciones inseguras | Archivos sensibles, secretos, permisos excesivos y revisión de configuración | ⬜ |
| EXP-031 | Firewall y control de conexiones | UFW/nftables, reglas entrantes y salientes, puertos y segmentación | ⬜ |
| EXP-032 | Gestión de privilegios y sudo | sudoers, ejecución privilegiada, errores de configuración y escalada de privilegios en laboratorio | ⬜ |
| EXP-033 | Actualizaciones y dependencias vulnerables | Gestión de paquetes, CVE, versiones afectadas, parches y reducción de superficie de ataque | ⬜ |

## Resultado esperado

Inspeccionar un Linux propio, identificar configuraciones riesgosas y aplicar medidas de endurecimiento sin romper los servicios legítimos.

## Criterio de endurecimiento

Cada cambio de configuración se documenta con tres datos: estado inicial, estado final y verificación de que el servicio legítimo sigue funcionando.