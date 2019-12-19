# pre-commit-mirrors-elm-format

[![lint][LintStatusBadge]][LintStatusBadgeActions]

Hooks for [pre-commit] that validate [Elm] files

## Using elm-format with pre-commit

- To use this you first need to install [pre-commit]
- Run `pre-commit install` from the root of your project

Finally add this to your _.pre-commit-config.yaml_:

## Usage

```yaml
- repo: https://github.com/a-ibs/pre-commit-mirrors-elm-format
  rev: 1.0.0
  hooks:
    - id: elmformat
```

Now when you try to commit an Elm file,
it will run [elm-format] and prevent commit if the checks fail.

[LintStatusBadge]: https://github.com/a-ibs/pre-commit-mirrors-elm-format/workflows/lint/badge.svg
[LintStatusBadgeActions]: https://github.com/a-ibs/pre-commit-mirrors-elm-format/actions
[pre-commit]: https://pre-commit.com/
[Elm]: https://elm-lang.org/
[elm-format]: https://github.com/avh4/elm-format
