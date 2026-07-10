# Dealer.com (dealer-com)

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

### Dealer.com Website Integration API

Partner-gated interface that lets approved third parties place and control their own experiences on the Dealer.com website platform without custom per-dealer integrations, while Dealer.com monitors performance and protects dealer data. Onboarding contact: `Website.Integration.API@coxautoinc.com`. No public endpoints, base URL, or authentication scheme are documented.

- **Human URL:** [Integrated Partner Program](https://www.dealer.com/products/integrated-partner-program)
- `endpointsModeled: true`

### Dealer.com Inventory and Imagery API

Vehicle inventory and imagery integrations for certified partners — photography, 360-degree spins, video, and image optimization tools that read and enrich dealer inventory. Inventory feed and market pricing data is also reachable through the Cox Automotive Integration Platform. Partner-gated.

- **Human URL:** [Dealer.com Integrations](https://www.dealer.com/integrations/)
- `endpointsModeled: true`

### Dealer.com Leads API

Lead generation and management — pre-qualification, messaging, and customer-engagement tools that capture website leads and route them into dealer CRM and Cox Automotive systems (Dealertrack, VinSolutions). The Cox Automotive Integration Platform documents Lead Management operations (view, create, update leads; trade-ins; vehicles of interest) behind OAuth and a partner agreement.

- **Human URL:** [Cox Automotive Integration Platform](https://developer.coxautoinc.com/)
- `endpointsModeled: true`

### Dealer.com Website Personalization API

Website Experience Optimization capability that personalizes inventory, content, specials, and assets on dealer sites using cross-platform shopper behavior from Autotrader and Kelley Blue Book. Delivered as a managed product, not a documented public API.

- **Human URL:** [Data Integration press release](https://www.dealer.com/company-news/data-integration-unlocks-website-personalization-press-release/)
- `endpointsModeled: true`

### Dealer.com Digital Advertising API

Digital advertising and marketing integration — paid search, display, social, and video advertising plus analytics tied to Dealer.com sites and the Cox Automotive advertising stack. Available to certified partners through the Integrated Partner Program.

- **Human URL:** [Integrated Partner Program](https://www.dealer.com/products/integrated-partner-program)
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
