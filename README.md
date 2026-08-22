# Zero Trust (zero-trust)

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

Zero Trust is the umbrella cybersecurity strategy that eliminates implicit trust based on network location and requires continuous verification of every user, device, workload, and access request. This index aggregates the core specifications (NIST, CISA, DoD, NSA, NCSC), the leading vendor platforms that implement Zero Trust (Cloudflare, Zscaler, Netskope, Palo Alto Networks, Tailscale, Twingate, Microsoft, Google), and the CNCF-graduated open standards that the ecosystem depends on (SPIFFE, SPIRE, OPA). Three sister API Evangelist topics cover Zero Trust Architecture, Zero Trust Network Access (ZTNA), and the Zero Trust Security Model in greater depth.

**URL:** [https://www.nist.gov/publications/zero-trust-architecture](https://www.nist.gov/publications/zero-trust-architecture)

## Tags

- Access Control, Cloud Security, Cybersecurity, Federal, Identity and Access Management, Network Security, Security, Zero Trust

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-03

## APIs

### NIST SP 800-207 Zero Trust Architecture

The foundational US specification of Zero Trust.

- [Documentation](https://csrc.nist.gov/pubs/sp/800/207/final)
- [PDF](https://nvlpubs.nist.gov/nistpubs/specialpublications/NIST.SP.800-207.pdf)

### CISA Zero Trust Maturity Model v2

The federal-civilian Zero Trust roadmap from CISA.

- [Documentation](https://www.cisa.gov/zero-trust-maturity-model)
- [PDF](https://www.cisa.gov/sites/default/files/2023-04/zero_trust_maturity_model_v2_508.pdf)

### DoD Zero Trust Reference Architecture

The Department of Defense seven-pillar Zero Trust reference architecture.

- [Documentation](https://dodcio.defense.gov/Portals/0/Documents/Library/ZT-Reference-Architecture.pdf)

### Cloudflare Zero Trust API

Cloudflare's Zero Trust platform combining ZTNA, SWG, CASB, RBI, DLP and an REST API for managing all of it.

- [Documentation](https://developers.cloudflare.com/cloudflare-one/)
- [APIReference](https://developers.cloudflare.com/api/)

### Zscaler Zero Trust Exchange API

Zscaler's combined ZIA and ZPA Zero Trust platform.

- [Documentation](https://help.zscaler.com/)
- [APIReference](https://help.zscaler.com/zpa/api-reference)

### Microsoft Entra Zero Trust APIs

Microsoft Entra (formerly Azure AD), Conditional Access, Defender for Cloud Apps, and Microsoft Intune together implement Zero Trust on the Microsoft platform.

- [Documentation](https://learn.microsoft.com/en-us/security/zero-trust/)
- [APIReference](https://learn.microsoft.com/en-us/graph/api/overview)

### Google BeyondCorp Enterprise

Google's productized Zero Trust platform.

- [Documentation](https://cloud.google.com/beyondcorp-enterprise/docs)

### SPIFFE / SPIRE

CNCF-graduated workload identity standard and reference runtime.

- [Documentation](https://spiffe.io/docs/latest/)
- [GitHub](https://github.com/spiffe)

### Open Policy Agent (OPA)

CNCF-graduated general-purpose policy engine commonly deployed as the PDP in Zero Trust implementations.

- [Documentation](https://www.openpolicyagent.org/docs/latest/)
- [GitHub](https://github.com/open-policy-agent)

## Common Properties

- [NIST Zero Trust Architecture](https://www.nist.gov/publications/zero-trust-architecture)
- [NIST SP 800-207 PDF](https://nvlpubs.nist.gov/nistpubs/specialpublications/NIST.SP.800-207.pdf)
- [NIST SP 800-207A PDF](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-207A.pdf)
- [CISA Zero Trust Maturity Model v2](https://www.cisa.gov/zero-trust-maturity-model)
- [OMB M-22-09 Federal Zero Trust Strategy](https://www.whitehouse.gov/wp-content/uploads/2022/01/M-22-09.pdf)
- [DoD Zero Trust Reference Architecture](https://dodcio.defense.gov/Portals/0/Documents/Library/ZT-Reference-Architecture.pdf)
- [NSA Zero Trust Guidance](https://www.nsa.gov/Press-Room/News-Highlights/Article/Article/2899282/nsa-releases-guidance-on-zero-trust-security-model/)
- [UK NCSC Zero Trust Architecture](https://www.ncsc.gov.uk/collection/zero-trust-architecture)
- [Cloudflare Zero Trust](https://www.cloudflare.com/zero-trust/)
- [Zscaler Zero Trust Exchange](https://www.zscaler.com/products-and-solutions/zero-trust-exchange)
- [Netskope SASE](https://www.netskope.com/platform/sase)
- [Palo Alto Networks Prisma Access](https://www.paloaltonetworks.com/sase/access)
- [Microsoft Zero Trust Guidance Center](https://learn.microsoft.com/en-us/security/zero-trust/)
- [Google BeyondCorp](https://cloud.google.com/beyondcorp)
- [Tailscale](https://tailscale.com/)
- [Twingate](https://www.twingate.com/)
- [SPIFFE on GitHub](https://github.com/spiffe)
- [Open Policy Agent on GitHub](https://github.com/open-policy-agent)
- [Sister Topic - Zero Trust Architecture](https://github.com/api-evangelist/zero-trust-architecture)
- [Sister Topic - Zero Trust Network Access](https://github.com/api-evangelist/zero-trust-network-access)
- [Sister Topic - Zero Trust Security Model](https://github.com/api-evangelist/zero-trust-security-model)

## Artifacts

### JSON Schema

- [Zero Trust Access Decision Schema](json-schema/zero-trust-access-decision-schema.json)
- [Zero Trust Subject Schema](json-schema/zero-trust-subject-schema.json)

### JSON Structure

- [Zero Trust Access Decision Structure](json-structure/zero-trust-access-decision-structure.json)

### JSON-LD

- [Zero Trust JSON-LD Context](json-ld/zero-trust-context.jsonld)

### Examples

- [Zero Trust Access Decision Example](examples/zero-trust-access-decision-example.json)

## Vocabulary

- [Zero Trust Vocabulary](vocabulary/zero-trust-vocabulary.yaml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
