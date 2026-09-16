# Consensys-Incorporated/.github

This repository holds the public organization profile and the default community health files that GitHub
applies to every repository in the `Consensys-Incorporated` organization that does not provide its own copy.

## What this repository provides

| File | Where it applies |
| --- | --- |
| [`SECURITY.md`](SECURITY.md) | Default security policy. Shown on the **Security** tab of every repository in the organization, public or private, that has no `SECURITY.md` of its own. |
| [`profile/README.md`](profile/README.md) | Rendered on the [organization page](https://github.com/Consensys-Incorporated). |
| [`CODEOWNERS`](CODEOWNERS) | Review routing for this repository only. |

## Precedence

A repository's own file always takes precedence over the defaults kept here. GitHub looks for a community
health file in the repository's `.github/` directory, then in its root, then in its `docs/` directory, and
falls back to this repository only when none is found. `LICENSE` and `README` files are never inherited and
must live in each repository.

## Making changes

- Open a pull request. The code owners listed in [`CODEOWNERS`](CODEOWNERS) review every change.
- Keep the content evergreen: no personal names, dates, roadmaps, or per-project contact channels, and link
  to stable landing pages rather than deep links.
- Sign your commits and add a `Signed-off-by` trailer with `git commit -s`, as required across the organization.
- Repository access is managed as code by the organization administrators, not through the GitHub UI.

## Security

To report a vulnerability in any repository of this organization, email
[Security-Report@Consensys.com](mailto:Security-Report@Consensys.com) or follow the steps in
[`SECURITY.md`](SECURITY.md).
