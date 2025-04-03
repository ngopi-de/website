# Ngopi Public Website

[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-%23FE5196?logo=conventionalcommits&logoColor=white)](https://conventionalcommits.org)

This repository contains the public website of www.ngopi.de as a Hugo project.

As a website generator, we use Hugo with the Fresh theme (see also [Credits](https://www.ngopi.de/credits/)).

## Development-related

We use Conventional Commits. To enable the linter locally, run:

```bash
npm ci    # in project's root
```

If the SSH host `uberspace.ngopi` is set up, the Hugo website can be built and deployed to our web space: 

```bash
./deploy  # in project's root
```