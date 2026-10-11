# orbit-data

Generated, public AI news snapshots (JSON) for the ORBIT browser extension.

This repository contains data only. It is intended to be served as static files by GitHub Pages:

- `snapshot/latest.json` is a small pointer to the newest snapshot version.
- `snapshot/<version>/` holds immutable `universe.json` and `archive.json` files, with sizes and
  sha256 checksums recorded in `latest.json`.

Each story is a short excerpt and metadata (title, link, publication date, source, topics) taken
from public feeds and APIs of the publishers and platforms named in its provenance. Every story
links to its original publisher; read the full article there.

No snapshots have been published yet. Source code, ingestion state and credentials are not part
of this repository. Provided as is, with no warranty of accuracy, completeness or availability.

Maintainer: Isha Chaudhari — https://www.linkedin.com/in/ishachaudhari/
