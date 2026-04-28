# Asistente de Estudio en Terminal

## Descripción general
Esta actividad te pide **diseñar y documentar** una propuesta de proyecto pequeño para terminal, pensado para implementarse con recursos limitados y en poco tiempo. El objetivo principal es practicar planeación técnica, estructura de repositorio y justificación de decisiones antes de escribir mucho código.

Tu propuesta debe centrarse en una práctica temática y elegir **un lenguaje principal** entre:

- ARM64 Assembly
- C
- Python
- Bash

> **Recomendación docente:** si eliges ARM64 Assembly, mantenlo en programas muy pequeños (por ejemplo, utilidades de entrada/salida simple o cálculos básicos), para que sea viable en una sola práctica.

## Contexto de la actividad
- Se publicará en GitHub Classroom.
- No hay plantilla inicial preconfigurada.
- El enfoque principal es documentación y claridad de diseño.
- Se espera un alcance pequeño (mini toolkit o utilidad puntual).
- Evita frameworks grandes, APIs pagadas, bases de datos, nube, contenedores o dependencias complejas.

## Objetivo de aprendizaje
Al finalizar, el estudiante será capaz de:
1. Definir una idea de proyecto técnicamente viable y acotada.
2. Justificar elección de lenguaje y alcance.
3. Diseñar estructura de repositorio clara y mantenible.
4. Plantear pruebas básicas para validar funcionalidad.

## Entregables obligatorios
El repositorio debe incluir, como mínimo:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

Además, de forma opcional:

- `src/`
- `scripts/`
- `tests/`

## Estructura recomendada del repositorio
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

## Instrucciones para el estudiante
1. Selecciona una temática concreta (ejemplo: organizador de archivos, reporteador de sistema, asistente de estudio, juego de comandos básico).
2. Define el problema que resolverás en contexto real.
3. Elige un lenguaje principal y justifica por qué es el más adecuado.
4. Redacta la propuesta técnica en `docs/propuesta.md`.
5. Documenta un caso de uso principal en `docs/caso_de_uso.md`.
6. Explica la estructura del repo y el propósito de cada carpeta en `docs/estructura_repositorio.md`.
7. Diseña pruebas mínimas en `docs/plan_de_pruebas.md`.
8. Si decides programar un prototipo, incluye solo lo mínimo indispensable.

## Criterios de evaluación sugeridos
- **Claridad de la propuesta (30%)**: objetivo, alcance y viabilidad.
- **Justificación técnica (25%)**: elección de lenguaje, límites y supuestos.
- **Documentación y estructura (25%)**: organización del repositorio y calidad de redacción.
- **Plan de pruebas (20%)**: casos relevantes, resultados esperados y trazabilidad básica.

## Restricciones
- Proyecto pequeño y acotado.
- Sin dependencias complejas.
- Sin servicios de pago.
- Sin infraestructura cloud.
- Priorizar funcionamiento local y reproducible.

## Formato de entrega
- Repositorio en GitHub Classroom con todos los archivos solicitados.
- Markdown claro y consistente.
- Commits descriptivos.
