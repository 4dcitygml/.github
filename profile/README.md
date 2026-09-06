# 4dcitygml

**Extend open-source culture to city data and the tools and practices that sustain it.**

4dcitygml is an early-stage, community-led project for learning, exploring,
and enjoying CityGML, urban data, statistics, and visualization. It experiments
with building-level change histories while preserving the source format and
stable building identifiers. Cities improve their data through proposals,
checks and review. The shared processing, definitions and guidance improve
through the same cycle, informed by cases from those cities.

## Start here

- [Portal](https://4dcitygml.github.io/) — browse cities and find downloads
- [Tools](https://github.com/4dcitygml/tools) — Hub, editors, shared processing, checks, definitions and guidance
- [City template](https://github.com/4dcitygml/city-template) — start an independent city repository
- [Tokyo Station](https://github.com/4dcitygml/sample-tokyo-station) ·
  [Munich Hauptbahnhof](https://github.com/4dcitygml/sample-munich-station) ·
  [Grand Central](https://github.com/4dcitygml/sample-newyork-station) — compact demonstration datasets

## How the repositories fit together

`city-template` supplies the starting structure. Each city repository then
maintains its own source-compatible CityGML and history, while pinning a reviewed
version of `tools` for checks and local editing. Generated CityGML editions are
published as derived releases rather than replacing the canonical source data.

4dcitygml gathers reusable findings from city issues and pull requests and
returns improvements through common tools releases. Cities can also consult
the project directly about shared-tool problems. Cities retain the decision
to adopt data changes; tools maintainers review changes to the shared machinery.

This operational work connects individual city cases with common standards:
it turns rules into usable checks and procedures, and helps distinguish data
and implementation errors from questions to raise with standards developers.
Read [the approach](https://github.com/4dcitygml/tools/blob/main/docs/principles.md)
([日本語](https://github.com/4dcitygml/tools/blob/main/docs/ja/principles.md)).

Client releases (`hub-v`) provide Mac and Windows downloads. City tooling
releases (`tools-v`) provide shared processing, checks, definitions and guidance.
They have different adoption paths and can advance independently; see the
[distribution status](https://github.com/4dcitygml/tools/blob/main/docs/shared-tooling-release.md).

Contributions and issue reports are welcome. Please use the repository that owns
the relevant code or data, and read its source attribution and contribution rules
before submitting data or images.

> 4dcitygml is an independent experimental project. It is not an official
> publication of OGC, Project PLATEAU, i-UR, or any source-data provider.
