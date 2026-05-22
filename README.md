# Renovate

Renovate is an Open Source, cross-platform dependency automation tool by Mend.io that automatically creates pull requests to keep software dependencies up to date. It supports over 90 package managers and language ecosystems including npm, PyPI, Maven, Docker, Helm, Go modules, Ruby Gems, NuGet, and more. Renovate runs as a CLI, Docker container, GitHub Action, or hosted cloud service (Mend Renovate App). Configuration is done via a `renovate.json` file in the repository root.

**GitHub Repository:** [https://github.com/renovatebot/renovate](https://github.com/renovatebot/renovate)

**Documentation:** [https://docs.renovatebot.com](https://docs.renovatebot.com)

---

## Project Overview

Renovate is a GitHub-first Open Source tool with 21,000+ GitHub stars. No HTTP API is exposed; it operates as a bot that processes Git repositories directly. The project is primarily consumed via:

- **npm package:** `npm install -g renovate`
- **Docker image:** `docker pull renovate/renovate`
- **GitHub Action:** `renovatebot/github-action`
- **Helm chart:** `renovatebot/helm-charts`
- **Hosted app:** Mend Renovate GitHub App

---

## Artifacts

### JSON Schema

| File | Description |
|---|---|
| [json-schema/renovate-config-schema.json](json-schema/renovate-config-schema.json) | JSON Schema for renovate.json configuration file |

### JSON Structure

| File | Description |
|---|---|
| [json-structure/renovate-config-structure.json](json-structure/renovate-config-structure.json) | Structural documentation for Renovate configuration |

### JSON-LD

| File | Description |
|---|---|
| [json-ld/renovate-context.jsonld](json-ld/renovate-context.jsonld) | JSON-LD context for Renovate dependency management concepts |

### Vocabulary

| File | Description |
|---|---|
| [vocabulary/renovate-vocabulary.yml](vocabulary/renovate-vocabulary.yml) | Dependency automation domain vocabulary |

---

## Common Properties

| Property | URL |
|---|---|
| GitHub | [https://github.com/renovatebot/renovate](https://github.com/renovatebot/renovate) |
| Documentation | [https://docs.renovatebot.com](https://docs.renovatebot.com) |
| Mend Renovate | [https://www.mend.io/renovate/](https://www.mend.io/renovate/) |
| GitHub App | [https://github.com/apps/renovate](https://github.com/apps/renovate) |
| GitHub Action | [https://github.com/renovatebot/github-action](https://github.com/renovatebot/github-action) |
| npm Package | [https://www.npmjs.com/package/renovate](https://www.npmjs.com/package/renovate) |
| Docker Image | [https://hub.docker.com/r/renovate/renovate](https://hub.docker.com/r/renovate/renovate) |
| Helm Charts | [https://github.com/renovatebot/helm-charts](https://github.com/renovatebot/helm-charts) |
| Tutorial | [https://github.com/renovatebot/tutorial](https://github.com/renovatebot/tutorial) |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
