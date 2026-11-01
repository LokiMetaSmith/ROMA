## Archived: 2026-10-31

*   **Repository Name:** ROMA (Recursive Open Meta-Agents)
*   **Description:** A meta-agent framework for building hierarchical high-performance multi-agent systems. It uses recursive hierarchical structures to solve complex problems through a plan-execute loop involving an Atomizer, Planner, Executors, and Aggregator.
*   **Tech Stack:** Python 3.12+, FastAPI/Flask (Backend), React + TypeScript (Frontend), AgnoAgents, E2B sandboxes for code execution.
*   **Key Features:** Recursive task decomposition, Agent agnostic (works with OpenAI, Anthropic, Google, local models), Complete transparency via stage tracing, Tool connections (E2B, file I/O).
*   **Pre-built Agents:** General Task Solver, Deep Research Agent, Crypto Analytics Agent.
*   **File Structure Overview:**
    *   `src/`: Main source code directory.
    *   `fastapi_server.py`: Backend server entry point.
    *   `frontend/`: React + TypeScript frontend code.
    *   `docs/`: Documentation files.
    *   `docker/`: Docker related configurations.
    *   `evals/`, `notebooks/`, `roma/`: Other project directories.
    *   `setup.sh`, `quickstart.sh`: Setup scripts.
    *   `pyproject.toml`, `uv.lock`, `Makefile`, `sentient.yaml`: Configuration files.
