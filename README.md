# Navy Federal Credit Union (navy-federal-credit-union)

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

Navy Federal Credit Union is a federally chartered, member-owned credit union headquartered in Vienna, Virginia — the largest credit union in the world by assets and membership, serving 14M+ members across the armed forces, DoD, veterans, and their families. It is a not-for-profit financial cooperative regulated by the National Credit Union Administration (NCUA).

On the open-finance front, Navy Federal runs a genuine first-party developer program — the **Navy Federal API Exchange** at [developer.navyfederal.org](https://developer.navyfederal.org/) — publishing a consumer-permissioned, open-banking-style API catalog. Access is partner-gated behind registration and a signed **Data Access Agreement**, secured with OAuth member consent and mutual-TLS whitelisting. No OpenAPI/Swagger is publicly downloadable pre-login. Members can also share permissioned data through aggregators (Plaid, Envestnet | Yodlee, Flinks).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/navy-federal-credit-union/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/navy-federal-credit-union/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- United States
- Credit Union
- Open Finance
- Open Banking
- Data Aggregation
- Payments

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

The Navy Federal API Exchange Open Banking API Catalog lists eight consumer-permissioned data-access products. Detailed per-API reference pages and specifications are login-gated behind registration and a signed Data Access Agreement; each entry below points to the publicly viewable catalog.

### Account Details API

Details and summary information for member accounts, including name, status, activity dates, balances, and more.

- **Human URL:** [https://developer.navyfederal.org/open-banking-api-catalog.html](https://developer.navyfederal.org/open-banking-api-catalog.html)

### Account Holders API

Information on account ownership and member relationships for consented member accounts.

- **Human URL:** [https://developer.navyfederal.org/open-banking-api-catalog.html](https://developer.navyfederal.org/open-banking-api-catalog.html)

### Account Statements API

Statements for accounts over a given period, including statement names and images with details.

- **Human URL:** [https://developer.navyfederal.org/open-banking-api-catalog.html](https://developer.navyfederal.org/open-banking-api-catalog.html)

### Account Transactions API

Transactions for accounts over a given period, including amounts, description, running balance, status, and more.

- **Human URL:** [https://developer.navyfederal.org/open-banking-api-catalog.html](https://developer.navyfederal.org/open-banking-api-catalog.html)

### API Management API

Client registration and OAuth authentication management used to onboard third parties and obtain member consent tokens.

- **Human URL:** [https://developer.navyfederal.org/open-banking-api-catalog.html](https://developer.navyfederal.org/open-banking-api-catalog.html)

### Customer Accounts API

Listing of consented member accounts with basic details.

- **Human URL:** [https://developer.navyfederal.org/open-banking-api-catalog.html](https://developer.navyfederal.org/open-banking-api-catalog.html)

### Customer Details API

Member information independent of accounts, including name, address, date of birth, IDs, and other personal information.

- **Human URL:** [https://developer.navyfederal.org/open-banking-api-catalog.html](https://developer.navyfederal.org/open-banking-api-catalog.html)

### Gateway Connectivity API

Connection test to the API platform providing a basic message response, used to prove out a working request over mTLS with whitelisting.

- **Human URL:** [https://developer.navyfederal.org/open-banking-api-catalog.html](https://developer.navyfederal.org/open-banking-api-catalog.html)

## Open Finance Posture

- **First-party developer portal:** Yes — Navy Federal API Exchange (`developer.navyfederal.org`, HTTP 200), an "Open Banking API Catalog" of consumer-permissioned data-access APIs.
- **Auth model:** OAuth member consent + mutual-TLS (mTLS) with IP whitelisting; onboarding requires a signed Data Access Agreement.
- **Downloadable specs:** None public — API reference and specifications are login-gated.
- **FDX / CFPB 1033:** Neither FDX membership nor a 1033 posture is explicitly named on the public portal; the catalog is a standardized, tokenized, consumer-permissioned data-sharing program in the open-banking spirit.
- **Aggregator access:** Members can share data via Plaid, Envestnet | Yodlee (2021 Data Access Agreement), and Flinks.

## Common Properties

- [Website](https://www.navyfederal.org/)
- [Developer Portal](https://developer.navyfederal.org/)
- [Documentation](https://developer.navyfederal.org/document-library.html)
- [Sign Up](https://developer.navyfederal.org/register.html)
- [Support](https://developer.navyfederal.org/support.html)
- [Terms of Service](https://developer.navyfederal.org/terms-and-conditions.html)
- [LinkedIn](https://www.linkedin.com/company/navy-federal-credit-union)
- [Blog](https://www.navyfederal.org/makingcents.html)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
