# Python Code Quality Pipeline Template

This is a template repository for learning Python code quality concepts using:

- Black (code formatter)
- isort (import sorter)
- PyLint (linter)
- pre-commit (automation)

## Instructions

1. `python -m venv venv`
2. Mac `source venv/bin/activate` Windows: `venv\Scripts\activate`
3. `pip install -r requirements-dev.txt`
4. `https://github.com/mikecolbert/3300-code-quality-pipeline.git`
5. `pre-commit install`

## Usage

Just code and commit! Tools will run automatically.
You can also run all tools manually:
`black . && isort . && pylint .`

## VS Code

Settings are preconfigured in `.vscode/settings.json`.
Tasks can be run with `Cmd+Shift+B` / `Ctrl+Shift+B`.

## Structure

.
├── .pre-commit-config.yaml
├── .vscode
│ └── settings.json
│ └── tasks.json
├── requirements-dev.txt
├── tasks.json
├── example.py
└── README.md
