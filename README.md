# Prosperity Bank (prosperity-bank)

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

Prosperity Bank is a Texas-chartered commercial bank (member FDIC, NMLS ID 466414) and the banking subsidiary of Prosperity Bancshares, Inc. (NYSE: PB), a Houston, Texas based regional financial holding company with roughly $37-43 billion in total assets and 300-plus full-service branches across Texas and central Oklahoma. It offers consumer and commercial banking, treasury management, mortgage, and wealth services.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/prosperity-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/prosperity-bank/refs/heads/main/apis.yml)

## Open-Finance / API Posture

Prosperity Bank runs **no first-party public developer portal or documented API**. Probing on 2026-07-23:

- `developer.prosperitybankusa.com` — does not resolve (no host)
- `developers.prosperitybankusa.com` — does not resolve (no host)
- `api.prosperitybankusa.com` — does not resolve (no host)
- `prosperitybankusa.com/developers` — 404
- `prosperitybankusa.com/api` — 404
- No GitHub organization (`github.com/prosperitybank` / `prosperitybankusa` → 404)

Consumer-permissioned account and transaction data is reachable only through **third-party data aggregators** — Finicity (Mastercard Open Banking), Plaid, and similar — rather than a directly published bank API. No **FDX**-conformant data-access API and no stated **CFPB Section 1033** posture are publicly documented by the bank as of this review. This is the honest, common reality for US regional banks: participation in open finance occurs via aggregators and the bank's core provider, not a first-party API surface.

## Tags

- Financial Services
- Banking
- United States
- Regional Bank
- Texas
- Open Finance
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

None. Prosperity Bank does not publish a public developer API.

## Common Properties

- [Website](https://www.prosperitybankusa.com/)
- [LinkedIn](https://www.linkedin.com/company/prosperity-bank)
- [Terms of Use](https://www.prosperitybankusa.com/terms-of-use)
- [Privacy Policy](https://www.prosperitybankusa.com/privacy)
- [Support](https://www.prosperitybankusa.com/contact-us)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
