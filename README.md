# n8n-finanzas-bot

Automatización de registro de gastos personales mediante un bot de Telegram, utilizando n8n como motor de flujos y Supabase como base de datos.

## Objetivo

Este proyecto permite recibir comprobantes de pago (texto, imagen, PDF) a través de Telegram, extraer la información relevante, validarla con el usuario y registrar la transacción en Supabase. También ofrece funcionalidades de consulta, resumen mensual y categorización automática.

## Componentes

- **n8n**: plataforma de automatización auto-hosteada en Render.
- **Telegram Bot**: interfaz de entrada y validación.
- **Supabase**: almacenamiento de transacciones.
- **GitHub**: control de versiones y despliegue.
- **Render**: VPS gratuito para mantener el servicio online.

## Funcionalidades

- Extracción de datos desde recibos (texto, imagen, PDF).
- Validación interactiva con el usuario.
- Registro en Supabase con estado `pendiente` o `completado`.
- Menú de consultas: transacciones pendientes, últimas 10, resumen mensual.
- Categorización automática de gastos.
- Exportación opcional a Google Sheets.

## Estado

🚧 En desarrollo. Primera etapa: recepción, validación y registro de transacciones.

