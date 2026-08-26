# Arquitectura del Bootcamp

## Principios transversales

- **Separation of Concerns**: cada módulo aísla su dominio; dentro de cada módulo, se separan estructura (HTML/rutas), presentación (CSS/estilos) y comportamiento (JS/lógica).
- **DRY / KISS / YAGNI**: no dupliques lógica, prefiere la solución simple que resuelve el problema actual, no construyas para necesidades hipotéticas.
- **SOLID**: se introduce progresivamente desde JS/TS (módulo 2 en adelante) hasta aplicarse completo en el backend (módulos 3-4).

## Estructura del monorepo

Un módulo por etapa del roadmap. Cada módulo contiene:

- `README.md` — objetivos, tecnologías, proyecto real, historias de usuario.
- `src/` — código fuente del proyecto en pareja.
- `capstone/student-a/` y `capstone/student-b/` — evaluación individual, sin ayuda de la IA.

## Estrategia de ramas

- `main` — código estable, protegido, solo vía PR aprobado.
- `feature/mod-XX-nombre-tarea` — desarrollo en pareja.
- `capstone/mod-XX-nombre-estudiante` — evaluación individual.

## Gate de avance

Un módulo no se da por cerrado hasta que **ambos** estudiantes tengan su capstone aprobado por el instructor.
