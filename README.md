# CrossingKey Open Specifications

**Public conventions and interoperability-oriented technical specifications from CrossingKey Intelligence.**

This repository is the standards layer of the CrossingKey public surface. It publishes interfaces, terminology, behavioral contracts, and governance patterns where openness improves review, portability, or interoperability.

It does **not** imply that every specification is deployed in production.

## Governing principle

> **Capability does not imply authority.**

Specifications involving tools, agents, external actions, money movement, data access, publication, or irreversible operations should distinguish technical capability from granted authority.

## Execution evidence model

Specifications for consequential execution should make enough state explicit to answer:

1. What operation was requested?
2. What authority permitted it?
3. What relevant state existed before execution?
4. What side effect was attempted?
5. What external acknowledgement or settlement evidence exists?
6. What relevant state exists afterward?
7. Was the intended postcondition verified?
8. Is repeating the operation safe?
9. If the outcome is ambiguous, what stops or reconciliation rules apply?

This model is informed by CrossingKey's public [HAAR research](https://github.com/crossingkey-holdings/crossingkey-public-research/blob/main/research/HAAR.md). It is a specification pattern, not a claim that every CrossingKey system implements HAAR.

## Specification discipline

Every normative specification should state:

- status and version;
- scope and non-goals;
- normative requirements;
- security or authority boundaries where relevant;
- idempotency/retry expectations when side effects exist;
- compatibility expectations;
- verification or evidence expectations;
- examples that are clearly identified as informative;
- change history.

## Versioning

Specifications use **MAJOR.MINOR**.

- **MAJOR** changes a normative requirement incompatibly.
- **MINOR** adds a backward-compatible requirement, clarification, or extension.

Normative language uses **MUST**, **MUST NOT**, **SHOULD**, **SHOULD NOT**, and **MAY** deliberately.

## Production reference

CrossingKey MCP provides a separately versioned public implementation surface for governed machine commerce:

https://github.com/crossingkey-holdings/crossingkey-mcp

Its source/release state remains authoritative for what that runtime actually exposes.

## Publication boundary

Open specifications may describe intended interfaces, data shapes, terminology, or exchange conventions. They do not expose credentials, production secrets, customer data, private source, or exploit-enabling operational detail.

## Start here

- [docs/SPECIFICATION_STANDARD.md](docs/SPECIFICATION_STANDARD.md)
- [docs/AUTHORITY_BOUNDARY.md](docs/AUTHORITY_BOUNDARY.md)

## Related public surfaces

- Professional evidence: https://github.com/crossingkey-holdings/experience
- Developer documentation: https://github.com/crossingkey-holdings/crossingkey-developer-documentation
- Public research: https://github.com/crossingkey-holdings/crossingkey-public-research
- Company: https://crossingkeyintelligence.com

## Contact

Technical, implementation, or standards inquiries: **founder@crossingkeyintelligence.com**
