# Contributing

Thanks for taking the time to contribute. These defaults apply to every
[@neuron7xLab](https://github.com/neuron7xLab) repository unless a repository
overrides them with its own `CONTRIBUTING.md`.

## Ground rules

- **Open an issue first** for anything beyond a typo or a one-line fix, so the
  approach can be agreed before code is written.
- **One logical change per pull request.** Small, reviewable diffs merge fast.
- **Tests are not optional.** New behaviour ships with tests that fail before the
  change and pass after it. Bug fixes ship with a regression test.
- **Green before review.** Lint, type-checks, and the test suite must pass locally
  and in CI before a PR is ready.

## Development loop

```bash
# 1. Fork, then clone your fork
git clone https://github.com/<you>/<repo>.git
cd <repo>

# 2. Create a focused branch
git checkout -b fix/short-description

# 3. Install dev dependencies (Python projects)
python -m pip install -e ".[dev]" || python -m pip install -r requirements-dev.txt

# 4. Run the quality gates the repo defines (typical set)
ruff format --check . && ruff check .
mypy .            # where configured
pytest -q

# 5. Commit, push, open a PR against `main`
```

If the repository defines a `Makefile`, `tox.ini`, `noxfile.py`, or a `CONTRIBUTING`
section in its README, those instructions take precedence over the generic loop above.

## Commit messages

Use clear, imperative subject lines (`Fix off-by-one in window edge`, not
`fixed stuff`). Reference the issue you close (`Closes #123`).

## Pull requests

- Fill in the PR template.
- Keep the PR description focused on **what changed and why**, not a diff narration.
- Be responsive to review comments; mark conversations resolved when addressed.

## Reporting security issues

Do **not** open a public issue for vulnerabilities. Follow
[`SECURITY.md`](./SECURITY.md).

By contributing you agree that your contributions are licensed under the same
license as the repository you are contributing to.
