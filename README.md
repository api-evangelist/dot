# US Department of Transportation (DOT)

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

The U.S. Department of Transportation (DOT) oversees federal transportation policy and operates multiple agencies that publish public REST APIs covering trucking and motor carrier safety (FMCSA), vehicle product information and safety recalls (NHTSA), aviation data (FAA), transit statistics, and transportation data portals. DOT APIs are free public government services requiring API key registration via Login.gov or the relevant agency developer portal.

- Website: https://www.transportation.gov/
- Developer Resources: https://www.transportation.gov/developer
- Open Data Portal: https://data.transportation.gov/
- GitHub: https://github.com/usdot-jpo-ode
- Status: https://www.transportation.gov/status
- X: https://twitter.com/USDOT

## APIs

### FMCSA QCMobile API
Safety performance data for U.S. DOT-registered motor carriers — carrier search by name, DOT number, or MC docket number, plus BASIC safety scores, operating authority, licensing, and insurance records.
- Documentation: https://mobile.fmcsa.dot.gov/QCDevsite/docs/qcApi

### FMCSA SaferBus API
Safety performance data for U.S. DOT-registered bus companies enabling consumer-facing applications to check motorcoach operator safety records.
- Documentation: https://www.fmcsa.dot.gov/application-programming-interface-data-behind-saferbus

### NHTSA vPIC Vehicle API
Vehicle Product Information Catalog — VIN decoding (single and batch), manufacturer lookup, WMI decode, vehicle type and model data, and plant codes. No authentication required.
- Documentation: https://vpic.nhtsa.dot.gov/api/

### NHTSA Datasets and APIs
Vehicle safety complaints, recalls, safety ratings (NCAP), and defect investigations searchable by make, model, and year.
- Documentation: https://www.nhtsa.gov/nhtsa-datasets-and-apis

### DOT Open Data Portal
Aggregated transportation datasets from FMCSA, NHTSA, FTA, BTS, FAA, and PHMSA with REST API access via the Socrata/Tyler platform.
- Portal: https://data.transportation.gov/

## Authentication

FMCSA APIs require a free developer account and API webkey obtained through Login.gov. NHTSA vPIC and the DOT Open Data Portal are publicly accessible without authentication.

## Pricing

All DOT public APIs are free government services. No usage-based charges apply.
