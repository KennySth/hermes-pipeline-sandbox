# Hermes Pipeline Sandbox

Repositorio público de pruebas para el pipeline Hermes -> opencode.

Las tareas se ejecutan en ramas con prefijo según el tipo de cambio:

- `docs/` — documentación
- `feature/` — nuevas funcionalidades
- `fix/` — correcciones
- `refactor/` — refactorizaciones
- `test/` — pruebas
- `chore/` — mantenimiento

Cada tarea se revisa mediante pull request antes de mergear en la rama principal.

## Estructura

- `README.md` — este documento
- `docs/` — documentos de prueba y notas del pipeline

## Flujo de trabajo

1. Hermes genera el plan y la rama a partir de la tarea.
2. opencode implementa el plan en la rama.
3. Los cambios se commitean y se abre un pull request para revisión.
4. Tras la aprobación se mergea y se limpian la rama y el worktree.
