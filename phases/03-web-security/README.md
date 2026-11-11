# Fase 3. Seguridad web y APIs

**Objetivo:** comprender cómo se originan las vulnerabilidades en aplicaciones web y APIs, reproducirlas en un entorno de prueba, explicar su impacto y corregirlas en código.

> **Alcance:** trabajar con una aplicación deliberadamente vulnerable (OWASP Juice Shop) o una API de laboratorio propia. No exponerla a Internet.

## Experimentos

| ID | Experimento | Temas aplicados | Estado |
|----|-------------|-----------------|:------:|
| EXP-017 | Anatomía de una solicitud HTTP | Métodos, headers, cuerpo, códigos de estado, cookies y parámetros | ⬜ |
| EXP-018 | Inspección de una API con un proxy web | Burp Suite o OWASP ZAP, solicitudes, respuestas, repetición y modificación de peticiones | ⬜ |
| EXP-019 | Autenticación y gestión de sesiones | Cookies, tokens, expiración, logout, almacenamiento y fijación de sesiones | ⬜ |
| EXP-020 | Control de acceso y autorización | Autenticación vs. autorización, IDOR/BOLA, acceso horizontal y vertical | ⬜ |
| EXP-021 | Inyección SQL en una aplicación de laboratorio | Consultas SQL, concatenación de cadenas, consultas parametrizadas y validación | ⬜ |
| EXP-022 | Cross-Site Scripting (XSS) | Contextos HTML/JavaScript, entrada no confiable, codificación de salida y sanitización | ⬜ |
| EXP-023 | Cross-Site Request Forgery (CSRF) | Cookies, solicitudes autenticadas, tokens CSRF, SameSite y validación de origen | ⬜ |
| EXP-024 | Seguridad de contraseñas | Hashing, salts, Argon2/bcrypt, fuerza bruta controlada y limitación de intentos | ⬜ |
| EXP-025 | Seguridad de JWT y tokens | Claims, firma, expiración, validación de algoritmo, issuer y audience | ⬜ |
| EXP-026 | Configuración insegura de APIs | CORS, validación de DTOs, rate limiting, exposición de errores y documentación pública | ⬜ |

## Resultado esperado

Comprender cómo se originan las vulnerabilidades web, reproducirlas en una aplicación de prueba, explicar su impacto y corregirlas en código.

## Stack de referencia

React, Next.js, NestJS, TypeORM y PostgreSQL. Cada vulnerabilidad se documenta con dos versiones del código: la vulnerable y la corregida.