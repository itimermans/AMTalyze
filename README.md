# AMTalyze

A Python-based data analysis project.

## Project Structure

```
AMTalyze/
├── docs/           # Documentation
├── notebooks/      # Jupyter notebooks
├── src/           # Source code
└── tests/         # Test files
```

## Installation

### For Users

Install the package using pip:
```bash
pip install amtalyze
```

### For Developers

1. Create and activate conda environment:
```bash
conda create -n amtalyze python=3.10
conda activate amtalyze
```

2. Install the package in development mode:
```bash
pip install -e .
```

## Development

- Use `black` for code formatting
- Write tests using `pytest`
- Use Jupyter notebooks in the `notebooks/` directory for exploratory analysis

### Dependency Management

This project uses `pyproject.toml` as the single source of truth for dependencies. The `requirements.txt` file is auto-generated from `pyproject.toml` and should not be edited manually.

To update dependencies:
1. Add or modify dependencies in `pyproject.toml`
2. Run `pip-compile pyproject.toml` to update `requirements.txt`

## License

[Add your license here]
