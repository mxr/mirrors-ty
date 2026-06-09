ty mirror
============================

Mirror of ty for pre-commit. Created with [pre-commit-mirror-maker](https://github.com/pre-commit/pre-commit-mirror-maker).

For pre-commit: see https://github.com/pre-commit/pre-commit

For ty: see https://pypi.org/project/openapi-generator-cli/

### Using ty with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
-   repo: https://github.com/mxr/mirrors-ty
    rev: ''  # Use the sha / tag you want to point at
    hooks:
    -   id: ty
```
