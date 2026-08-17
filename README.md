# Kotcha

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

Kotcha is a consumer running-coaching mobile application operated by PACEUP SAS, a French company based
in Paris, and co-founded with marathon world-record holder Eliud Kipchoge and the NN Running Team. The
app generates personalized, adaptive training plans for 5K, 10K, half-marathon and marathon distances
through a conversational AI coach, and imports activity and health data from Strava, Garmin Connect,
Apple, Coros and Huawei devices. Kotcha raised EUR 3.5M in October 2025 in a round led by Racine², operated
by Serena and makesense.

## No API surface

As of **2026-08-17**, Kotcha publishes **no public API**. Contract discovery found no developer portal,
no API reference, no OpenAPI/Swagger/GraphQL/AsyncAPI document, no MCP server and no A2A agent card:

- `www.kotcha.com/openapi.json`, `/openapi.yaml`, `/swagger.json`, `/v1/openapi.json`, `/api-docs`,
  `/docs`, `/redoc`, `/graphql`, `/llms.txt` — all **404**
- Every `/.well-known/*` path 307-redirects to `/en/.well-known/*` and returns **404**
  (see [`well-known/kotcha-well-known.yml`](well-known/kotcha-well-known.yml))
- `api.kotcha.com`, `app.kotcha.com`, `developer.kotcha.com`, `docs.kotcha.com`,
  `backend.kotcha.com` — all **NXDOMAIN**
- No GitHub organization exists at `github.com/kotcha`
- Kotcha's Terms & Conditions §6 explicitly prohibit *"accessing services through unauthorized means or
  automated methods"* — the mobile application backend was **not** probed

Kotcha is an API **consumer** (Garmin Connect, Strava, Apple Health) rather than an API producer. This
profile therefore records a verified absence, captured as `x-coverage: {state: none, reason:
no-developer-program}` in [`apis.yml`](apis.yml). What *is* recorded here is the company identity, its
published legal/support surface, a probed domain-security posture, the well-known and pricing absences,
and a generated `llms.txt`.

**Published a developer program since?** Open an issue and the profile will be re-run and re-scored.

Source: portfolio company of [serena](https://github.com/api-evangelist/serena) — https://www.kotcha.com/
