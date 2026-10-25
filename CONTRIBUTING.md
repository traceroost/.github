# Contributing to TraceRoost

Thank you for your interest in contributing.

Most of TraceRoost lives in [traceroost/core](https://github.com/traceroost/core), and that's where
almost every contribution belongs. Its
[CONTRIBUTING.md](https://github.com/traceroost/core/blob/main/CONTRIBUTING.md) covers development
setup, the MIT / BSL 1.1 license zones, and the checks CI runs.

- **Bugs:** open an issue in [traceroost/core](https://github.com/traceroost/core/issues/new/choose)
  using the bug report template.
- **Ideas and feature requests:** open an issue in core describing the problem you want solved.
- **Security issues:** don't open a public issue — see [SECURITY.md](SECURITY.md).

## Other repositories

- **[homebrew-tap](https://github.com/traceroost/homebrew-tap)** — the formula is generated and
  committed by core's release workflow on every release, so don't edit it by hand. Fix the
  generator (`scripts/homebrew-formula.mjs` in core) instead, or open an issue in core.

## Pull requests

- For anything beyond a small fix, open an issue first so we can agree on the approach.
- Keep each pull request to one change, and describe what it does and how you tested it.
- First-time contributors are asked to sign the
  [Contributor License Agreement](https://github.com/traceroost/core/blob/main/.github/CLA.md) by
  commenting on the pull request; a bot will prompt you.

Everyone taking part is expected to follow the [Code of Conduct](CODE_OF_CONDUCT.md).
