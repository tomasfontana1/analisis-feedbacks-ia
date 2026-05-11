# Workflows M2 sanitizados

Estos archivos son versiones limpiadas para portfolio/GitHub público.

Se removió o reemplazó:

- Credenciales de n8n (`credentials`).
- `webhookId`.
- IDs/URLs reales de Google Sheets.
- IDs/URLs reales de Airtable.
- IDs reales de canales de Slack.
- Metadata de instancia, workflow ID y versionId.
- `pinData`.
- Estado activo: todos quedaron con `active: false`.

Antes de importar en otro n8n, cada integración debe reconectarse manualmente con credenciales propias.

Archivos incluidos:
- `m2-integradora-sanitizado.json` generado desde `M2 Integradora (4).json`
- `manejo-errores-sanitizado.json` generado desde `Manejo de errores (1).json`
- `seguimiento-48hs-soporte-reclamo-sanitizado.json` generado desde `48 horas soporte y reclamo (1).json`
