# Estructura del Repositorio y Convenciones

## Árbol base
```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

## Propósito por carpeta/archivo
- **README.md:** presentación general de la práctica.
- **docs/propuesta.md:** definición del proyecto y alcance.
- **docs/caso_de_uso.md:** escenario principal de operación.
- **docs/estructura_repositorio.md:** reglas de organización.
- **docs/plan_de_pruebas.md:** estrategia de validación.
- **src/**: código fuente mínimo.
- **scripts/**: automatizaciones simples (ejecución local).
- **tests/**: evidencia de pruebas funcionales básicas.

## Convenciones recomendadas
- Nombres de archivo en minúsculas y con guion bajo.
- Commits con mensajes descriptivos.
- Evitar archivos binarios innecesarios.
- Documentar supuestos técnicos en `README.md`.

## Regla de simplicidad
Si una funcionalidad aumenta mucho la complejidad, se documenta como “fuera de alcance” para mantener el proyecto pequeño.
