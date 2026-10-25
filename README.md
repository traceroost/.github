# traceroost/.github

Organization profile and shared defaults for TraceRoost — local-first monitoring for coding agents.

| File | Purpose |
| --- | --- |
| [`profile/README.md`](profile/README.md) | The overview shown on <https://github.com/traceroost>. |
| [`SECURITY.md`](SECURITY.md) | Default security policy: how to report a vulnerability privately. |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | Default contributing guide; points contributors to `traceroost/core`. |
| [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) | Default code of conduct (same text as core's). |
| [`SUPPORT.md`](SUPPORT.md) | Where to get help. |
| [`ISSUE_TEMPLATE/config.yml`](ISSUE_TEMPLATE/config.yml) | Issue chooser links to core, the docs and the security policy. |
| [`pull_request_template.md`](pull_request_template.md) | The PR template for every repository in the organization. |

GitHub uses these files for any repository in the organization that doesn't have its own copy.
A repository's own file always wins, so `traceroost/core` keeps its own `SECURITY.md`,
`CONTRIBUTING.md`, `CODE_OF_CONDUCT.md` and issue templates. Keep the defaults consistent with
core's when either changes.

No repository has its own PR template, so they all share this one. Don't add a
`pull_request_template.md` to an individual repository — it would replace this one there.
