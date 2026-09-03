# Contributing to 4dcitygml

Thank you for helping improve 4dcitygml. Choose the repository that owns the
thing you want to change:

- tools, validation, conversion, and user-interface changes: `4dcitygml/tools`
- reusable city-repository structure and general data guidance: `4dcitygml/city-template`
- a building, attribute, geometry, texture, or source record: the relevant city repository
- portal listings and public documentation: `4dcitygml/4dcitygml.github.io`

If you are unsure, open a question in the closest repository. Maintainers can
move the discussion before implementation begins.

Submitting city-data PRs from your own tool, script, or the GitHub web UI —
without the official editors — is explicitly welcome. The machine contract
(reason anchor, commit trailers, editing style, CI gates) is published in the
[PR Exchange Contract](https://github.com/4dcitygml/tools/blob/main/docs/exchange-contract.md),
and the practice repositories serve as a sandbox for client developers.

## Before submitting

1. Search existing issues and pull requests.
2. For a material change, open or reference an issue explaining the need and evidence.
3. Keep the change scoped to one concern and avoid formatting unrelated files.
4. Run the checks documented in that repository.
5. Explain what changed, why, how it was verified, and which source supports it.

Do not include credentials, private contact details, confidential material, or
evidence that cannot be published. Report security vulnerabilities privately as
described in [SECURITY.md](SECURITY.md).

## Code and documentation

Code and documentation contributions follow the license stated in the target
repository. By intentionally submitting a contribution, you represent that you
have the right to do so and agree that it may be distributed under that license.

## City data and images

City repositories retain the terms and attribution of their official source
datasets. Read the target repository's `NOTICE`, provenance documentation, and
data contribution policy before changing CityGML or textures.

Only submit evidence and images that you may lawfully publish. For photographs,
use your own work, taken from a lawful location, and remove recognizable faces,
vehicle plates, nameplates, interiors, and other personal information. The city
repository's explicit contribution terms govern any rights in submitted data or images.

To request removal of published material that contains personal data or content
you hold rights to, use the private report form (see [SUPPORT.md](SUPPORT.md))
instead of opening a public issue.

## Review and conduct

Automated checks support review but do not replace source, semantic, licensing,
privacy, or safety judgment. A maintainer may ask for a smaller change, clearer
evidence, or repository-specific steps. Participation is subject to the
[Code of Conduct](CODE_OF_CONDUCT.md).
