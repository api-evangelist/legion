# Legion Security

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
