# Contributing — symmetria-core

## Branches
- main — protected, always releasable
- dev — integration branch
- features — `feat/<scope>`, fixes — `fix/<scope>`, docs — `docs/<scope>`, chores — `chore/<scope>`

## Commits
Use conventional style: `type(scope): message`
Examples:
- feat(loader): add csv reader
- fix(stats): correct rolling mean window
- docs(readme): clarify boundaries

## PRs
- Title mirrors commit style.
- Describe: What changed? Why? How tested? Risks/rollback?
- Merge to `dev` via PR; `main` only from green `dev`.

## Code Quality
- Black for formatting, Flake8 for linting, tests in `tests/`.
- CI (GitHub Actions) will be added to check style and tests before merging to `main`.
