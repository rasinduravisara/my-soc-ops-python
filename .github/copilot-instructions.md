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

## Design Guide (Retro Theme)
- Use pixel/arcade fonts: 'Press Start 2P', 'VT323', monospace
- Neon color palette: #ff00cc (pink), #00fff7 (cyan), #1a0033 (deep purple), #fffbe7 (cream)
- Borders: double or solid, thick, with neon glow/shadow
- Buttons: .retro-btn for all CTAs, hover for color swap
- Boards: .retro-board for backgrounds, .retro-square for bingo cells
- Use text-shadow and box-shadow for glowing effects
- Layout: Centered, max-width, generous padding
- See app/static/css/app.css for utility classes and examples
