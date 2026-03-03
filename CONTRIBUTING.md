# Contributing

Thank you for your interest in contributing!  
These repositories are primarily **research-oriented**. Contributions that improve correctness, reproducibility, clarity, and documentation are especially welcome.

---

## Ways to Contribute

- Bug reports and reproducibility fixes
- Documentation improvements
- New baselines or benchmark extensions
- Code refactoring and test improvements
- Performance or memory optimizations

---

## Reporting Issues

When opening an issue, please include:

- What you expected vs. what happened
- Exact command or configuration used
- Environment details (OS, Python, key library versions)
- Minimal reproducible example (if possible)

For research-result discrepancies, also include:

- Random seed(s)
- Dataset version / preprocessing details
- Commit hash

---

## Development setup

We recommend `uv` for managing dependencies.

```bash
uv sync --group dev
source .venv/bin/activate
```

Run tests (if available in this repo):

```bash
pytest
pre-commit run --all-files
```

If this repository’s README specifies a different environment (e.g., CUDA/PyTorch/conda), please follow the README instead.

---

## Pull Requests

Please:

- Keep PRs focused and small
- Clearly explain motivation and validation
- Ensure tests (if available) pass
- Document any result changes (metrics, configs, seeds)

---

## Large Files and Datasets

Do **not** commit large datasets or artifacts.

Instead:

- Provide download scripts or links to official sources
- Document dataset licenses
- Include small samples only when permitted
