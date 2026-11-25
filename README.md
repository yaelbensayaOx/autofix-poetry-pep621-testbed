# OXDEV-109396 autofix testbed

Poetry pyproject.toml layouts on which autofix answered "no change":

- poetry2-pep621-app, poetry2-pep621-no-tool-deps: Poetry 2, dependencies in PEP 621 [project]
- legacy-dev-next-to-group-dev, legacy-dev-after-group-dev, legacy-dev-conflicting-pin: legacy [tool.poetry.dev-dependencies] next to [tool.poetry.group.dev]

poetry.lock pins the vulnerable versions.
