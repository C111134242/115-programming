# AGENTS.md

Greenfield repo for 115學年度計算機程式課程資料 (course materials). Only `README.md`, `LICENSE` (MIT), and a Python `.gitignore` exist; no source, toolchain, or CI yet.

- 專案語言為 Python；所有回應一律使用繁體中文。
- 一律使用 conda 管理 Python 套件，環境名稱為 `iem_python`（例如 `conda run -n iem_python python ...`）；不得改用 pip / venv / uv 建立其他環境。
- Do not assume any build, test, lint, or formatter is configured. Check for manifests/scripts before running anything; do not invent commands.
- When adding tooling, prefer the simplest standard setup and document the exact commands in `README.md`.
- Keep course examples self-contained with no hidden env/service dependencies unless explicitly requested.
