# Research Portfolio

Code and replication materials for empirical finance research.

Each paper has a self-contained directory with its own documentation, environment, and verification record.

| Project | Materials | Package status |
| --- | --- | --- |
| AJFS AI Trend | [Open project](papers/ajfs-ai-trend/) | Structure prepared; code migration and verification pending |

## Repository layout

```text
papers/
  ajfs-ai-trend/
    src/       # Reusable analysis code
    scripts/   # Setup and reproduction entry points
    configs/   # Analysis settings
    tests/     # Independent checks and regression tests
    data/      # Access instructions and permitted examples
    results/   # Selected reference outputs and reproduction notes
    docs/      # Methods, provenance, and verification records
```

Start with the README for the relevant paper. Exact paper metadata, authorship, contributions, dependencies, and reproduction commands will be documented as each package is prepared.

This initial scaffold contains no research code, datasets, or reproduced results. Package status describes the materials in this repository, not the publication status of a paper.

## Data and reuse

Data access and redistribution conditions are documented per paper. Credentials, restricted datasets, and local execution outputs must remain outside version control. A public example is not evidence that the full empirical analysis has been reproduced.

No repository-wide reuse license has been assigned yet. Rights and third-party licenses must be established before adding a license or importing research materials.
