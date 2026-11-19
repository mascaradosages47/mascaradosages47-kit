# mascaradosages47-kit

Count lines, words and characters, with totals.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m mascaradosages47_kit.cli --help
```

```python
from mascaradosages47_kit.core import Mascaradosages47Tool

tool = Mascaradosages47Tool()
print(tool)
```

## Layout

```
mascaradosages47_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 mascaradosages47
