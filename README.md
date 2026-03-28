

# 🕹️ Soc Ops: Retro Social Bingo

<img src="https://img.shields.io/badge/theme-retro%20arcade-ff00cc?style=for-the-badge&logo=windows95&logoColor=white" alt="Retro Arcade Badge" />

> Step into a neon-lit, pixel-powered world! Soc Ops is now a retro-inspired social bingo game—think arcades, synthwave, and 80s/90s nostalgia. Find people who match the prompts, tap their square, and race to get 5 in a row. Powered by FastAPI, Jinja2, and HTMX.

---

## 🕹️ How It Works

1. Each player gets a unique bingo board with fun prompts.
2. Mingle and find people who match each square.
3. Tap a square to mark it. Get 5 in a row to win!

---

## 🚀 Try It Out Locally

```bash
python -m uv sync                # Install dependencies
python -m uv run pytest          # Run tests
python -m uv run ruff check .    # Lint
python -m uv run uvicorn app.main:app --reload --port 8000  # Start server
```
Then open [http://localhost:8000](http://localhost:8000) in your browser.

---

## 📚 Lab Guide

| Part | Title |
|------|-------|
| [**00**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=00-overview) | Overview & Checklist |
| [**01**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=01-setup) | Setup & Context Engineering |
| [**02**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=02-design) | Design-First Frontend |
| [**03**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=03-quiz-master) | Custom Quiz Master |
| [**04**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=04-multi-agent) | Multi-Agent Development |

> 📝 Lab guides are also available in the [`workshop/`](workshop/) folder for offline reading.

---

## ✨ Features

- Fast, modern UI with custom CSS utilities
- Real-time board updates with HTMX
- Server-side state for fairness and persistence
- Easy to extend with your own prompts

---

## 🤝 Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines and code of conduct.
