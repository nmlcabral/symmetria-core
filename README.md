# symmetria-core

**Purpose:** The core Python package for Project Symmetria — reusable, tested modules for data intake, signal computation, evaluation, and governance.  
This repo does **not** contain research notebooks or learning exercises.

## Boundaries
- ✅ Production-grade Python modules in `symmetria/`
- ✅ Unit tests in `tests/`
- ❌ No notebooks (use `symmetria-research`)
- ❌ No learning/exercises (use `Symmetria-lab`)
- ❌ No large datasets (see `symmetria-data` for schemas/samples only)

## Development (local)
1. Create a virtual environment (example shown with Python 3.11)  
2. Install dev tools (formatter, linter, tests)  
3. Run tests locally

*(Exact commands and packaging config will be added when we create the first module and CI.)*

## Branch Flow
- `main` — protected, always releasable  
- `dev` — integration branch  
- feature branches — `feat/<scope>`, `fix/<scope>`, `docs/<scope>`, `chore/<scope>`

## License
MIT © Nuno Cabral
