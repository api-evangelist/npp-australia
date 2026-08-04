# NPP Australia (AP+)

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
