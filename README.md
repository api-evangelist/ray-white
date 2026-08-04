# Ray White (ray-white)

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

Ray White is Australasia's largest real estate group, a family-owned brokerage network founded in 1902 and headquartered in Brisbane, Australia, running 550+ Australian offices and roughly a thousand offices in total across Australia, New Zealand, Indonesia, Hong Kong, China, Papua New Guinea, the Middle East and Atlanta USA, spanning residential sales, auctions, commercial (Ray White Commercial / rwc.com.au), rural and livestock, property management, projects, marine, hotels, valuations, business sales, insurance and mortgage broking through sister brand Loan Market. In the Australian property value chain Ray White sits on the AGENCY side of a portal duopoly — it lists into REA Group's realestate.com.au and Domain rather than operating a portal or a registry of its own — and it is an API CONSUMER, not an API producer. In December 2025 Ray White named realestate.com.au and PropTrack its data partners explicitly for their "industry leading API architecture", piping that licensed market data into its proprietary OneSystem, NurtureCloud and Pulse platforms. Its API posture is therefore honestly stated as none-published — as of 2026-07-26 no developer portal, no public API documentation, no OpenAPI or OData `$metadata` contract, and no published partner-API application path could be found on raywhite.com or any developer/api/docs subdomain (all of which fail DNS resolution). RESO is absent — Ray White does not appear in the RESO certification directory, which is unsurprising because RESO is a North American, NAR-driven mandate with no Australian counterpart; Australia's closest thing to a required machine-readable property rail is PEXA electronic conveyancing, which Ray White transacts through as a participant rather than exposes.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ray-white/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ray-white/refs/heads/main/apis.yml)

## Tags

- Real Estate
- Australia
- Brokerage
- Property Listings
- Property Management
- Rentals
- Commercial Real Estate
- Auctions
- Valuation
- PropTech
- Conveyancing
- Mortgage

## Timestamps

- **Created:** 2026-07-26
- **Modified:** 2026-07-26

## APIs

No public APIs are listed. Ray White publishes no developer portal, no API documentation, and no machine-readable contract of any kind. Four developer subdomains (`developer.`, `developers.`, `api.`, `docs.raywhite.com`) do not resolve, and `/developers`, `/api`, `/docs`, `/openapi.json`, `/swagger.json`, `/api-docs`, `/$metadata` and `/.well-known/openid-configuration` all return HTTP 404 on www.raywhite.com. The site's own sitemap tree contains no developer, api, docs, integration or partner section. See [review.yml](review.yml) for every URL probed and its HTTP status.

## RESO Posture

**No RESO reference found. Not certified.**

The RESO certification directory at [https://www.reso.org/certificates/](https://www.reso.org/certificates/) was fetched anonymously on 2026-07-26 (HTTP 200, 416 KB, server-rendered, covering Data Providers, MLS, Pooled Platform, Technology Company and Commercial Brokerage sections). A case-insensitive search for "Ray White" returned zero matches; a search for "Australia" returned zero matches. Ray White holds no RESO Web API certification, no RESO Data Dictionary certification at any version, and has no RESO Universal Property Identifier (UPI).

This is the expected answer. RESO is mandated by the National Association of REALTORS for US MLSs; Australia has no MLS and no NAR. Listings flow agent → portal (realestate.com.au / Domain) under commercial agreements rather than through a certified, standardised Web API.

## Access Gate

**`none-published`.**

There is nothing to sign and nothing to join, because no access path is offered. Ray White operates no developer programme, no partner-API application form, no API terms of service and no data-licence page. The only evidenced route to Ray White data is a bilateral commercial arrangement negotiated company to company — the kind Ray White itself struck with REA Group / PropTrack. OneSystem, NurtureCloud and Pulse are franchise-network tooling for Ray White's own principals and agents; the public NurtureCloud site names no API, no developer documentation and no integration surface.

## Open Data

**None.** Ray White publishes no open-licensed, callable dataset. Australia's open-data counterweight in property sits with government land-registry and statistical products, not with brokerages.

## Auth Model

**None published.** No API key programme, no OAuth 2.0 authorization server, no SAML federation documented publicly. `https://www.raywhite.com/.well-known/openid-configuration` returns HTTP 404 — no OpenID Connect discovery document is served.

## Webhooks, Events, SDKs, Postman

None. Absence across the board is the finding. The GitHub organisation [https://github.com/raywhite](https://github.com/raywhite) (name "Ray White", location Australia, blog raywhite.com) holds 9 public repos — 6 forks of third-party projects and 3 generic utilities — with no first-party API artifacts.

## Common Properties

- [Website](https://www.raywhite.com/)
- [About](https://www.raywhite.com/about-us)
- [Blog](https://www.raywhite.com/news-and-market-insights/news-media)
- [LinkedIn](https://www.linkedin.com/company/raywhitegroup)
- [GitHub Organization](https://github.com/raywhite)
- [Documentation](https://www.raywhite.com/news-and-market-insights/news-media/ray-white-and-rea-group-announce-landmark-partnership)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
