# Estructura de directorios recomendada para el repositorio MAO\_Biblioteca\_Hidrolatos

```
MAO_Biblioteca_Hidrolatos/
│
├── README.md
├── CHECKLIST.md
├── PLANTILLA_HIDROLATO.md
├── knowledge_log.md
├── NOTAS_DE_INTEGRACION.md
│
├── Knowledges/                      # << NUEVO
│   ├── knowledge_log.md              # memoria viva
│   ├── knowledge_raw.md              # dump de data bruta
│   └── ...                           # logs históricos, versiones previas
│
├── Fichas_Plantas/
│   ├── Lamiaceae-
│   ├── Rosaceae-
│   ├── Asteraceae-
│   ├── Myrtaceae-
│   ├── Rutaceae-
│   ├── Cupressaceae-
│   ├── Apiaceae-
│   └── ... (familias futuras)
│
├── Bibliografia/
│   ├── [Libro1].pdf
│   ├── [Libro2].pdf
│   └── ...
│
├── Integracion/
│   ├── NOTAS_DE_INTEGRACION.md
│   ├── Referencias_Cruzadas.md
│   └── ...
│
└── Utiles/
    ├── Plantilla_Excel.xlsx
    ├── Tablas_comparativas.md
    └── ...
```

## Detalle de estructura

- **Knowledges/**: Memoria viva, logs de conocimiento, volcados brutos y control histórico.
- **Raíz:** Documentación, plantillas y archivos de control de proyecto.
- **Fichas\_Plantas/**: Todas las fichas en markdown, organizadas por familia, opcionalmente con subcarpetas si la familia es muy grande.
- **Bibliografia/**: PDFs, libros, papers y recursos fuente, debidamente citados.
- **Integracion/**: Notas metodológicas, referencias cruzadas, logs de integración y debates.
- **Utiles/**: Plantillas, tablas y herramientas complementarias para análisis y comparativas.

## Consejos

- Mantén nombres claros y estandarizados, evitando tildes y espacios.
- Versiona plantillas y documentos clave si modificas el formato.
- Cada archivo importante debe tener cabecera con fecha, autor y propósito.
- Sincroniza siempre el checklist y el knowledge\_log tras cada iteración relevante.

---

*Esta estructura asegura máxima escalabilidad, trazabilidad y facilidad de consulta colaborativa para el repositorio.*

