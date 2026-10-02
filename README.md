# 4dcitygml organization defaults

This special repository provides the public organization profile and default
community health files for repositories owned by `4dcitygml`.

- `profile/README.md` is shown on the organization Overview page.
- Root community files (`CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `SECURITY.md`,
  `SUPPORT.md`) apply only when a repository does not provide its own.
- `GOVERNANCE.md` is the organization-level statement; GitHub does not
  propagate it, so repositories link to it rather than inherit it.
- `.github/ISSUE_TEMPLATE/` and `.github/PULL_REQUEST_TEMPLATE.md` contain
  general defaults. City-data repositories should keep their data-specific
  forms locally.
- Licenses and source-data notices are always maintained in each repository.

Project repositories may override these defaults where their contribution,
security, or data-provenance requirements differ.

This repository distributes no workflows.

## Maintaining this repository

`SECURITY.md` holds the canonical description of the private report form; the
other documents link to it rather than restating it.
