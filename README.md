<!-- TEMPLATE: substitua todos os trechos entre <> e apague este comentário. Renomeie src/project_name e o "name" no pyproject.toml. -->

# <Project name>

[![CI](https://github.com/FreddiSantos/<repo>/actions/workflows/ci.yml/badge.svg)](https://github.com/FreddiSantos/<repo>/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

<One sentence: what this project does and for whom.>

> 🇧🇷 <Resumo de uma linha em português.>

## Problem

<What problem does this solve? Why does it matter? Include context from civil engineering or AI if relevant.>

## Solution

<How the project approaches the problem. Add an architecture diagram or a screenshot/GIF if possible.>

## Getting started

Requirements: [uv](https://docs.astral.sh/uv/) (it installs the right Python version automatically).

```bash
git clone https://github.com/FreddiSantos/<repo>.git
cd <repo>
uv sync
uv run pytest
```

<How to run the main script or notebook, e.g. `uv run python -m project_name`.>

### Data

<Where the data comes from, its license, and how to download it. Raw data is not versioned — see [data/README.md](data/README.md).>

### Reproducibility

- Dependencies are pinned in `uv.lock`.
- Random seed: <value and where it is set>.

## Stack

<Python · pandas · PyTorch · ...>

## Results

<Metrics, charts or sample outputs. Compare with a baseline when possible.>

## Roadmap

- [ ] <Next step>
- [ ] <Next step>

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). This project follows the [Code of Conduct](CODE_OF_CONDUCT.md).

## License

[MIT](LICENSE) © Pedro Freddi
