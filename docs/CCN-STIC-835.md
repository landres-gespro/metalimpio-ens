# Referencias normativas — CCN-STIC-835

## Medida [mp.info.5] — Borrado de metadatos

> "Se eliminarán los metadatos y datos ocultos de los documentos electrónicos
> antes de su distribución, especialmente cuando se difundan ampliamente o se
> publiquen en web."

## Medidas relacionadas

- **[op.exp.2]** — Configuración segura de aplicaciones
- **[org.3]** — Registro de actividad y auditoría
- **[mp.per.3]** — Protección de perímetros

## Tipos de metadatos según riesgo

| Riesgo | Ejemplos |
|--------|----------|
| ALTO | Autor, empresa, GPS, rutas de red |
| MEDIO | S.O., versión software, fechas |
| BAJO | Estadísticas de edición |
| CONSERVAR | Copyright / propiedad intelectual |

## Herramientas complementarias

- Inspector de Documentos de MS Office (macros VBA)
- Adobe Acrobat (macros JS, adjuntos)
- `exiftool` (limpieza exhaustiva en terminal)
