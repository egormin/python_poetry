# Poetry
https://python-poetry.org/

How to install:
```
curl -sSL https://install.python-poetry.org | python3 -
```

How to add poetry to an existing project:
```
poetry init
```

How to create project with poetry:
```
poetry new my-project
```

Create env with poetry:
```
poetry env use python3.10
```

Use env:
```
poetry shell
```

Exit from env:
```
exit
```

Run smth inside ven:
```
poetry run python
```

Add module:
```
poetry add requests

It will be added here:
[tool.poetry.dependencies]
python = "^3.10"
requests = "^2.28.1"
```
Show installed modules:
```
poerty show
poetry show --tree
poetry show --latest
```
