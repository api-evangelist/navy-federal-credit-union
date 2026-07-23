# Navy Federal Credit Union (navy-federal-credit-union)

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
