# 4dcitygml

**Open tools and small demonstration datasets for exploring CityGML as
versioned building data.**

4dcitygml is an early-stage, community-led project for learning, exploring,
and enjoying CityGML, urban data, statistics, and visualization. It experiments
with building-level change histories while preserving the source format and
stable building identifiers.

## Start here

- [Portal](https://4dcitygml.github.io/) — browse cities and find downloads
- [Tools](https://github.com/4dcitygml/tools) — local editors, checks, and converters
- [City template](https://github.com/4dcitygml/city-template) — start an independent city repository
- [Tokyo Station](https://github.com/4dcitygml/sample-tokyo-station) ·
  [Munich Hauptbahnhof](https://github.com/4dcitygml/sample-munich-station) ·
  [Grand Central](https://github.com/4dcitygml/sample-newyork-station) — compact demonstration datasets

## How the repositories fit together

`city-template` supplies the starting structure. Each city repository then
maintains its own source-compatible CityGML and history, while pinning a reviewed
version of `tools` for checks and local editing. Generated CityGML editions are
published as derived releases rather than replacing the canonical source data.

Contributions and issue reports are welcome. Please use the repository that owns
the relevant code or data, and read its source attribution and contribution rules
before submitting data or images.

> 4dcitygml is an independent experimental project. It is not an official
> publication of OGC, Project PLATEAU, i-UR, or any source-data provider.
