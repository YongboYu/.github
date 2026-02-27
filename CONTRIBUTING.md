# Contributing

Thanks for your interest in contributing!

## Getting Started

1. Fork the repo and create a feature branch from `main`
2. Install dev dependencies: `uv sync --group dev`
3. Install pre-commit hooks: `pre-commit install`
4. Make your changes
5. Run checks locally: `pre-commit run --all-files`
6. Run tests: `uv run pytest`
7. Open a pull request against `main`

## Pull Request Guidelines

- Keep PRs focused — one concern per PR
- All CI checks must pass (`pre-commit` and `test` jobs)
- Write or update tests for new functionality
- Follow existing code style (enforced automatically by ruff)
