# Renovate

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Renovate is an Open Source, cross-platform dependency automation tool by Mend.io that automatically creates pull requests to keep software dependencies up to date. It supports over 90 package managers and language ecosystems including npm, PyPI, Maven, Docker, Helm, Go modules, Ruby Gems, NuGet, and more. Renovate runs as a CLI, Docker container, GitHub Action, or hosted cloud service (Mend Renovate App). Configuration is done via [a number of different locations](https://docs.renovatebot.com/configuration-options/) in the repository: most commonly a `renovate.json` file in the repository root.

**GitHub Repository:** [https://github.com/renovatebot/renovate](https://github.com/renovatebot/renovate)

**Documentation:** [https://docs.renovatebot.com](https://docs.renovatebot.com)

---

## Project Overview

Renovate is a cross-Forge Open Source tool with 21,000+ GitHub stars. No HTTP API is exposed; it operates as a bot that processes Git repositories directly. The project is primarily consumed via:

- **npm package:** `npm install -g renovate`
- **Docker image:** `docker pull renovate/renovate` / `docker pull ghcr.io/renovatebot/renovate`
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
| Docker Image | [https://hub.docker.com/r/renovate/renovate](https://hub.docker.com/r/renovate/renovate) [ghcr.io/renovatebot/renovate](https://ghcr.io/renovatebot/renovate) |
| Helm Charts | [https://github.com/renovatebot/helm-charts](https://github.com/renovatebot/helm-charts) |
| Tutorial | [https://github.com/renovatebot/tutorial](https://github.com/renovatebot/tutorial) |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
