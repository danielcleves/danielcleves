# AGENTS.md — Perfil de GitHub danielcleves

## Proyecto
Repositorio de perfil público `danielcleves/danielcleves` (este directorio). El `README.md` es la pantalla principal del perfil de GitHub. Estilo oscuro moderno, contenido principal en español con badges en inglés.

## Preferencias del usuario (obligatorias)
- NO mencionar NLP, Machine Learning, ni clasificación de sentimiento en español (lo considera muy básico).
- `prestamos-equipos-ecci-backend`: el usuario es **líder técnico** (arquitectura, coordinación, revisión), NO autor del código.
- El usuario es **estudiante** de Ingeniería de Sistemas (ECCI), 8.º semestre de 9 — no egresado.
- LinkedIn real: https://www.linkedin.com/in/daniel-cleves-458799271/
- NO usar portafolio (todavía no existe) ni correo electrónico en el perfil.
- Estadísticas: NO usar cards de `github-readme-stats.vercel.app` (caídas, 503) ni `github-profile-trophy.vercel.app` (402). Usar badges dinámicos de shields.io (`/badge/dynamic/json` contra `api.github.com/users/danielcleves`). Repositorios + Followers en la misma línea. NO Following ni contador de visitas.

## Cosas que la API de GitHub no permite
- La API no expone mutación para anclar repos al perfil; se hace solo vía UI (Customize your pins).

## Estado actual (sept 2026)
- Repo creado, README publicado y funcional.
- Pendientes del usuario (manuales): anclar repos por UI (zorn-api, zorn-frontend, prestamos-equipos-ecci-backend, cv-color-classifier) y completar la bio de GitHub (vacía).

## Convenciones
- Commits en la rama `main`, mensajes estilo `docs: ...` / `chore: ...`.
- Para verificar que un badge carga: `curl -s -o /dev/null -w "%{http_code}" URL` debe dar 200.