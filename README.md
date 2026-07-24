# NPP Australia (AP+)

NPP Australia operates the **New Payments Platform (NPP)** — Australia's national
real-time, data-rich, account-to-account payments infrastructure that clears and
settles 24 hours a day, 365 days a year across more than 100 connected banks,
credit unions, fintechs and government agencies. Since 2021 NPP Australia has been
a wholly owned subsidiary of **Australian Payments Plus (AP+)**, the entity formed
by amalgamating NPP Australia, BPAY Group and eftpos.

Home market: **Australia**. Tier: **rails / scheme operator**.

## What NPP does

- **NPP core rail** — real-time (near-instant) account-to-account clearing and
  settlement, aligned to the **ISO 20022** messaging standard.
- **PayID** — an addressing overlay that maps a mobile number, email, ABN or
  organisation ID to a bank account so payers don't need a BSB and account number.
- **PayTo** — a real-time digital mandated-debit overlay giving consumers
  visibility and control over recurring and one-off account debits, and letting
  businesses initiate real-time pull payments under a pre-authorised agreement.

## API posture (honest)

NPP Australia is a **scheme and rail operator, not a self-serve PSP**. In its own
words on the developer page, *"NPP Australia does not offer APIs, but many NPP
Participants do."* What NPP Australia publishes is:

- the **NPP API Framework** (v5.0), an ISO 20022-aligned specification that defines
  the mandatory technical approach and data attributes for NPP-based APIs;
- an AP+ **developer portal** at
  [developers.auspayplus.com.au](https://www.developers.auspayplus.com.au/)
  (registration-gated; unified across the former NPP, BPAY and eftpos portals);
- a **SWIFT-hosted API sandbox** at
  [nppa-developer.swift.com](https://nppa-developer.swift.com/user/register) for
  building and testing NPP-based solutions;
- **PayID** and **PayTo** service documentation and messaging toolkits.

There is **no downloadable public OpenAPI/Swagger specification** — the consumable
NPP/PayID/PayTo APIs are implemented and offered by NPP Participants (banks and
connected fintechs), governed by the framework above.

## Links

- Website (NPP): https://www.auspayplus.com.au/solutions/npp
- For developers: https://www.auspayplus.com.au/solutions/npp-for-developers
- Developer portal (AP+): https://www.developers.auspayplus.com.au/
- API sandbox (SWIFT): https://nppa-developer.swift.com/user/register
- NPP API Framework v5.0 (PDF): https://www.auspayplus.com.au/wp-content/uploads/2024/06/NPP-API-Framework-v5.0.pdf
- PayTo: https://www.auspayplus.com.au/solutions/payto
- PayID: https://www.auspayplus.com.au/solutions/payid
- News: https://www.auspayplus.com.au/news
- LinkedIn: https://www.linkedin.com/company/auspayplus/

---

Part of the [API Evangelist](https://apievangelist.com) network. Maintained by
Kin Lane · kin@apievangelist.com
