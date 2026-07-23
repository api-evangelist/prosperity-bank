# Prosperity Bank (prosperity-bank)

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
