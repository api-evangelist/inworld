# Inworld AI (inworld)

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

Inworld AI provides voice and conversational AI building blocks for games and interactive media. Public APIs cover Text-to-Speech, Speech-to-Text, a Realtime speech-to-speech API, and an LLM Router that fronts 220+ third-party models with unified billing.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/inworld/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/inworld/refs/heads/main/apis.yml)

## Tags

- AI
- Voice
- Characters
- Games
- Conversational

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Inworld Text-to-Speech API

TTS-2 and TTS-1.5 (Max/Mini) models for character voice synthesis. Priced per 1M characters with plan-tier discounts.

- **Human URL:** [https://docs.inworld.ai/docs/tts](https://docs.inworld.ai/docs/tts)
- **Base URL:** `https://api.inworld.ai`

#### Tags

- TTS
- Speech Synthesis
- Character Voice

#### Properties

- [Documentation](https://docs.inworld.ai/docs/tts)
- [Pricing](https://inworld.ai/pricing)
- [Postman Collection](collections/inworld.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/inworld.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Inworld Speech-to-Text API

Multi-provider transcription API priced at $0.35/hour standard rate.

- **Human URL:** [https://docs.inworld.ai/docs/stt](https://docs.inworld.ai/docs/stt)
- **Base URL:** `https://api.inworld.ai`

#### Tags

- STT
- Transcription

#### Properties

- [Documentation](https://docs.inworld.ai/docs/stt)
- [Postman Collection](collections/inworld.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/inworld.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Inworld Realtime API

Low-latency speech-to-speech voice API for natural conversation experiences. Included with all plans.

- **Human URL:** [https://docs.inworld.ai/docs/realtime](https://docs.inworld.ai/docs/realtime)
- **Base URL:** `https://api.inworld.ai`

#### Tags

- Realtime
- Speech-to-Speech
- Voice

#### Properties

- [Documentation](https://docs.inworld.ai/docs/realtime)
- [Postman Collection](collections/inworld.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/inworld.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Inworld LLM Router API

Routing layer over 220+ LLM models, billed at provider cost via Inworld's unified API.

- **Human URL:** [https://docs.inworld.ai/docs/llm-router](https://docs.inworld.ai/docs/llm-router)
- **Base URL:** `https://api.inworld.ai`

#### Tags

- LLM
- Router
- Inference

#### Properties

- [Documentation](https://docs.inworld.ai/docs/llm-router)
- [Postman Collection](collections/inworld.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/inworld.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/inworld-ai)
- [LinkedIn](https://www.linkedin.com/company/inworld-ai)
- [Website](https://inworld.ai/)
- [Documentation](https://docs.inworld.ai/)
- [Plans](plans/inworld-plans-pricing.yml)
- [Rate Limits](rate-limits/inworld-rate-limits.yml)
- [Fin Ops](finops/inworld-finops.yml)
- [L L Ms Txt](https://docs.inworld.ai/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
