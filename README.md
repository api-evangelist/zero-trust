# Zero Trust (zero-trust)

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
