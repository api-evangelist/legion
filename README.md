# Legion Security

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Legion Security is a browser-native AI SOC analyst that learns a security team's real workflows from inside the browser and then helps execute and automate them in phases — Learning Mode (workflow capture and mapping), Guided Mode (human-in-the-loop execution), and Autonomous Mode (phased autonomy). The platform targets alert triage, investigation, and evidence gathering in the security operations center.

Seed-stage, backed by Accel — https://www.legionsecurity.ai/

## Artifacts in this repo

| Artifact | File | Method |
|---|---|---|
| security.txt (RFC 9116) | `well-known/legion-security.txt` | searched |
| Well-known index | `well-known/legion-well-known.yml` | searched |
| llms.txt | `llms/legion-llms.txt` | searched |
| Trust center | `security/legion-trust-center.yml` | searched |
| Vulnerability disclosure | `security/legion-vulnerability-disclosure.yml` | searched |
| Domain security | `security/legion-domain-security.yml` | probed |

## Notes

**No public API.** Legion Security publishes no public developer API, OpenAPI, SDK, or
developer portal as of 2026-07-19 — `docs.legionsecurity.ai` is a gated customer sign-in.
`apis[]` is intentionally empty, and the spec-grounded artifacts (OpenAPI, MCP, skills,
conventions, errors, data-model) are therefore skipped rather than fabricated.

**Slug collision.** Three unrelated companies named "Legion" appear across the VC
portfolio feeds and were collapsed into this one slug. This repo profiles Accel's
**Legion Security** (legionsecurity.ai), matching the Website originally committed here.
The other two still need their own slugs:

- **Legion Intelligence** — https://www.legionintel.com/ — agentic AI for national security (Bloomberg Beta)
- **Legion Technologies** — https://legion.co/ — workforce management (Norwest Venture Partners)
