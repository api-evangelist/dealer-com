# Dealer.com (dealer-com)

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

Dealer.com, a Cox Automotive brand, builds automotive dealership websites, digital advertising, and digital marketing technology used by thousands of franchise and independent dealers across North America.

**Access model: partner-gated / contact-sales.** Dealer.com does **not** publish an open, self-serve public API. Third parties integrate through the **Dealer.com Integrated Partner Program** (Website Integration API) and, at the platform level, through the **Cox Automotive Integration Platform** at [developer.coxautoinc.com](https://developer.coxautoinc.com/), which uses OAuth (Okta) and requires an approved partner agreement. The API entries below are **logical models** of those partner capabilities and are marked `endpointsModeled: true` — they intentionally assert no fabricated base URLs or endpoints, because no open specification is published.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/dealer-com/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dealer-com/refs/heads/main/apis.yml)

## Tags

- Automotive
- Dealership
- Digital Marketing
- Website Platform
- Inventory
- Leads
- Digital Advertising
- Cox Automotive
- Partner Program

## Timestamps

- **Created:** 2026-07-10
- **Modified:** 2026-07-10

## APIs (modeled partner capabilities)



### Dealer.com Leads API

Lead generation and management — pre-qualification, messaging, and customer-engagement tools that capture website leads and route them into dealer CRM and Cox Automotive systems (Dealertrack, VinSolutions). The Cox Automotive Integration Platform documents Lead Management operations (view, create, update leads; trade-ins; vehicles of interest) behind OAuth and a partner agreement.

- **Human URL:** [Cox Automotive Integration Platform](https://developer.coxautoinc.com/)
- `endpointsModeled: true`



## Common Properties

- [LinkedIn](https://www.linkedin.com/company/dealer-com)
- [Website](https://www.dealer.com)
- [Documentation — Integrated Partner Program](https://www.dealer.com/products/integrated-partner-program)
- [Documentation — Cox Automotive Integration Platform](https://developer.coxautoinc.com/)
- [Plans](plans/dealer-com-plans-pricing.yml)
- [Rate Limits](rate-limits/dealer-com-rate-limits.yml)
- [Fin Ops](finops/dealer-com-finops.yml)

## Review

Does Dealer.com expose a documented public WebSocket API? **No.** See [review.yml](review.yml). Dealer.com publishes no open public API of any transport; documented Cox Automotive Integration Platform APIs are OAuth-gated REST over HTTPS. No WebSocket or SSE surface is documented.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
