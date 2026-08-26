# Web Dev Bootcamp Playground

Monorepo del bootcamp fullstack de Diego y Raúl. Aprendizaje por pares (XP / Ping-Pong Pair Programming), guiado por Claude Code como Lead Instructor con método socrático: pistas y code review, nunca soluciones.

## Estructura

- `modules/mod-XX-nombre/` — un módulo por etapa del roadmap, cada uno con su propio `README.md`, código fuente (`src/`) y capstone individual (`capstone/`).
- `docs/ARCHITECTURE.md` — principios de arquitectura y convenciones que aplican a todo el repo.
- `.github/PULL_REQUEST_TEMPLATE.md` — plantilla obligatoria para todo PR.

## Workflow

- `main` está protegida — nunca push directo.
- Trabajo en pareja: rama `feature/mod-XX-nombre-tarea`.
- Evaluación individual: rama `capstone/mod-XX-nombre-estudiante`.
- Commits en formato [Conventional Commits](https://www.conventionalcommits.org/): `tipo(alcance): descripción`.
- Todo cambio entra a `main` vía Pull Request, con aprobación del compañero de equipo (peer review) y de Claude Code.

## Módulos

1. Web Fundamentals, Git Workflow & Clean Architecture Base — *Dev Hub & Resource Directory*
2. JavaScript Moderno, Algoritmia & Primeros Pasos SOLID — *Task & Metrics Dashboard*
3. Backend con Node.js, TypeScript & Arquitectura Limpia — *Core REST API*
4. Persistencia de Datos, SQL & Autenticación Segura — *RBAC API*
5. Python Backend, Algoritmia Avanzada e Integración con IA — *AI Analytics Microservice*
6. Frontend Moderno, Fullstack Integration, Docker & Deployment — *SaaS Fullstack*

Avanzar de módulo requiere que ambos estudiantes tengan su capstone individual aprobado por el instructor.
