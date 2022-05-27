# {{ workflow_name }}

[![Snakemake](https://img.shields.io/badge/snakemake-≥6.3.0-brightgreen.svg)](https://snakemake.github.io)
[![GitHub actions status](https://github.com/{{ repo_full_name }}/workflows/Tests/badge.svg?branch={{ main_branch }})](https://github.com/{{ full_name }}/actions?query=branch%3Amain+workflow%3ATests)


{{ workflow_description }}

The usage of this workflow is described in the [Snakemake Workflow Catalog](https://snakemake.github.io/snakemake-workflow-catalog/?usage=<owner>%2F<repo>) and WorkflowHub registry.


## Usage

Run as:

```bash
snakemake --snakefile workflow/Snakefile  --configfile config/default.yml --cores
```

## Acknowledgements
If you use this workflow in a paper, don't forget to give credits to the authors by citing the URL of this (original)  and its DOI (see above).

