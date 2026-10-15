# Reporte de preflight

Fecha UTC: 2026-10-15T16:50:37+00:00
Sistema: Darwin 25.6.0

Este reporte comprueba el entorno local. No autentica cuentas, no llama a APIs y no prueba una integración real.

| Comprobación | Estado | Detalle |
|---|---|---|
| Python | PASS | 3.9.6 (se requiere 3.9+) |
| Dataset mínimo | PASS | 3 casos sintéticos legibles |
| Git | PASS | git version 2.50.1 (Apple Git-155) |
| Repo propio | PASS | origin GitHub cristinaespinosa-ca/Copia_Leon; commit local 7f942d0 |
| Identidad Git | PASS | user.name y user.email están configurados |
| Claude Code | PARTIAL | no encontrado; usa Cowork como fallback y revisa docs/claude-code.md |
| Node.js / npm | DEFERRED | no necesario para el instalador nativo de Claude Code |
| GitHub CLI | DEFERRED | no instalado; GitHub web o GitHub Desktop son suficientes |
| Base de datos | DEFERRED | sqlite3: 3.51.0 2025-06-12 13:14:41 f0ca7bba1c5e232e5d279fad6338121ab55af0c8c68c84cdfb18ba5114dcaapl (64-bit); se decide según tu proyecto |

**Resultado:** `PARTIAL`

Siguiente: puedes avanzar con el fallback; registra qué quedó pendiente antes del commit de cierre.
