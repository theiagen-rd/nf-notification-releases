# nf-notification-releases

Public release artifacts for the [nf-notification](https://github.com/theiagen-rd/nf-notification) Nextflow plugin.

Source code is maintained in a private repository. This repo hosts only compiled
release artifacts so that Nextflow can auto-install the plugin without
authentication.

## Installation

```bash
export NXF_PLUGINS_TEST_REPOSITORY="https://github.com/theiagen-rd/nf-notification-releases/releases/download/v0.6.0/nf-notification-0.6.0-meta.json"
nextflow run your-pipeline.nf -plugins nf-notification@0.6.0
```
