# hugo-version-test

A dummy repository to confirm that a given version of Hugo is available for use in a GitHub Action.

Requires a Repository Secret HUGO_VERSION to set the version of Hugo you wish to check. With the GitHub CLI set the variable:

```bash
gh variable set HUGO_VERSION
```

Run the check:

```bash
gh workflow run check.yaml
```
