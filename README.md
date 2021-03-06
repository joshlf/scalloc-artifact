# Scalloc Artifact Repository

**PLEASE REFER TO THE LATEST STABLE VERSION WHEN CONDUCTING EXPERIMENTS!**

This repository contains the tools and benchmarks needed to build interesting
allocators (including scalloc) and evaluate them in various benchmarks.

## Evaluation

The current stable release for the artifact is 1.2

The artifact has been tested on Ubuntu 14.04 LTS.

See the [manual](doc/manual.pdf) for instructions on how to set up and use the
artifact.

The following commands can be used to prepare a new artifact environment

```bash
git clone https://github.com/cksystemsgroup/scalloc-artifact.git
cd scalloc-artifact
git checkout 1.2
tools/make_deps.sh
tools/create_env.sh
```
