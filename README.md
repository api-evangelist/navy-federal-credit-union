# Navy Federal Credit Union

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

Navy Federal Credit Union is a federally chartered credit union headquartered in Vienna, Virginia, and the largest credit union in the world by both assets and membership, serving more than 14 million members across the armed forces, Department of Defense, veterans, and their families. As a not-for-profit, member-owned financial cooperative regulated by the National Credit Union Administration (NCUA), it offers deposit accounts, credit cards, auto and mortgage lending, and investment services. On the open-finance front, Navy Federal operates a genuine first-party developer program — the Navy Federal API Exchange at developer.navyfederal.org — that publishes a consumer- permissioned, open-banking-style API catalog of eight data-access products (account details, holders, statements, transactions, customer accounts, customer details, plus OAuth/API-management and an mTLS gateway-connectivity test). Access is partner-gated behind registration and a signed Data Access Agreement, secured with OAuth member consent and mutual-TLS whitelisting; no OpenAPI/Swagger is publicly downloadable pre-login. Navy Federal also exposes member-permissioned data through aggregators (Plaid, Envestnet | Yodlee via a 2021 data access agreement, Flinks) rather than solely direct first-party integration.

**Areas:** Financial Services · Banking · United States · Credit Union · Open Finance · Open Banking · Payments

## Navy Federal Credit Union on APIs.io

Everything profiled for Navy Federal Credit Union is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/navy-federal-credit-union/](https://apis.io/providers/navy-federal-credit-union/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [Account Details API](https://apis.io/apis/navy-federal-credit-union/account-details/) — Details and summary information for member accounts, including name, status, activity dates, balances, and more. Part of Navy Federal's consumer-…
- [Account Holders API](https://apis.io/apis/navy-federal-credit-union/account-holders/) — Information on account ownership and member relationships for consented member accounts. Part of Navy Federal's consumer-permissioned Open Banking API Catalog.
- [Account Statements API](https://apis.io/apis/navy-federal-credit-union/account-statements/) — Statements for accounts over a given period, including statement names and images with details. Part of Navy Federal's consumer-permissioned Open Banking…
- [Account Transactions API](https://apis.io/apis/navy-federal-credit-union/account-transactions/) — Transactions for accounts over a given period, including amounts, description, running balance, status, and more. Part of Navy Federal's…
- [API Management API](https://apis.io/apis/navy-federal-credit-union/api-management/) — Client registration and OAuth authentication management used to onboard third parties and obtain member consent tokens for the Open Banking API Catalog.
- [Customer Accounts API](https://apis.io/apis/navy-federal-credit-union/customer-accounts/) — Listing of consented member accounts with basic details. Part of Navy Federal's consumer-permissioned Open Banking API Catalog.
- [Customer Details API](https://apis.io/apis/navy-federal-credit-union/customer-details/) — Member information independent of accounts, including name, address, date of birth, IDs, and other personal information. Part of Navy Federal's…
- [Gateway Connectivity API](https://apis.io/apis/navy-federal-credit-union/gateway-connectivity/) — Connection test to the API platform providing a basic message response, used to prove out a working request over mTLS with whitelisting. Part of Navy…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Navy Federal Credit Union Authentication](https://apis.io/security/navy-federal-credit-union/navy-federal-credit-union-authentication/)
- [Navy Federal Credit Union Domain Security](https://apis.io/security/navy-federal-credit-union/navy-federal-credit-union-domain-security/)
- [Navy Federal Credit Union Vulnerability Disclosure](https://apis.io/security/navy-federal-credit-union/navy-federal-credit-union-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.navyfederal.org/)
- [Documentation](https://developer.navyfederal.org/document-library.html)
- [API reference](https://developer.navyfederal.org/open-banking-api-catalog.html)
- [Sign up](https://developer.navyfederal.org/register.html)
- [Support](https://developer.navyfederal.org/support.html)
- [Blog](https://www.navyfederal.org/makingcents.html)
- [Security](https://navyfederal.responsibledisclosure.com/hc/en-us)
- [Terms of service](https://developer.navyfederal.org/terms-and-conditions.html)
- [Privacy policy](https://www.navyfederal.org/policy/privacy.html)

## API Evangelist rating

**Kin Score 28.5** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 69.6 |
| Contract quality | 0.0 |
| Contract governance | 18.2 |
| Operational transparency | 10.5 |
| Developer ergonomics | 45.2 |
| Access clarity | 34.2 |

**Agent readiness 2.5** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 34.6** — Banking & Open Finance

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/navy-federal-credit-union/](https://apis.io/providers/navy-federal-credit-union/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Navy Federal Credit Union: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/navy-federal-credit-union/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
