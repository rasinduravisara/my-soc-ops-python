# Copilot Workspace Instructions

## Development Checklist (MANDATORY)
- [ ] `uv run ruff check .` passes (lint)
- [ ] `uv run pytest` passes (test)
- [ ] `uv run uvicorn app.main:app --reload --port 8000` runs (build/dev server)
- [ ] No unused variables/imports; use snake_case and type hints

## Project Summary
- Social Bingo game (Python, FastAPI, Jinja2, HTMX)
- Custom CSS utilities in app/static/css/app.css
- State managed server-side, cookies for persistence, HTMX for partial updates

## Conventions
- Never use VS Code Simple Browser for preview
- See README.md for setup, CONTRIBUTING.md for CLA/code of conduct
- Workshop guides: [workshop/](workshop/)
