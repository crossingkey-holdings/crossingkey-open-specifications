# CrossingKey Open Specifications

**Public conventions and interoperability-oriented technical specifications from CrossingKey Intelligence.**

This repository is the standards layer of the CrossingKey public surface. It publishes interfaces, terminology, behavioral contracts, and governance patterns where openness improves review, portability, or interoperability.

It does **not** imply that every specification is deployed in production.

## Specification discipline

Every normative specification should state:

- status and version;
- scope and non-goals;
- normative requirements;
- security or authority boundaries where relevant;
- compatibility expectations;
- examples that are clearly identified as informative;
- change history.

## Versioning

Specifications use **MAJOR.MINOR**.

- **MAJOR** changes a normative requirement incompatibly.
- **MINOR** adds a backward-compatible requirement, clarification, or extension.

Normative language uses **MUST**, **MUST NOT**, **SHOULD**, **SHOULD NOT**, and **MAY** deliberately.

## Governing principle

> **Capability does not imply authority.**

Specifications involving tools, agents, external actions, money movement, data access, publication, or irreversible operations should distinguish technical capability from granted authority.

## Publication boundary

Open specifications may describe intended interfaces, data shapes, terminology, or exchange conventions. They do not expose credentials, production secrets, customer data, private source, or exploit-enabling operational detail.

## Start here

- [`docs/SPECIFICATION_STANDARD.md`](docs/SPECIFICATION_STANDARD.md)
- [`docs/AUTHORITY_BOUNDARY.md`](docs/AUTHORITY_BOUNDARY.md)

## Related public surfaces

- Professional evidence: https://github.com/crossingkey-holdings/experience
- Developer documentation: https://github.com/crossingkey-holdings/crossingkey-developer-documentation
- Public research: https://github.com/crossingkey-holdings/crossingkey-public-research
- Company: https://crossingkeyintelligence.com

## Contact

Technical, implementation, or standards inquiries: **founder@crossingkeyintelligence.com**
