# Digital Trust Profile (DTP)

> A simple transparency standard for digital services.

The Digital Trust Profile (DTP) is an open standard that allows digital services to publish transparent information about how they operate.

It provides a consistent, machine-readable format that helps people and software understand key characteristics of a digital service, including AI usage, governance, privacy, and verification status.

The Digital Trust Profile is designed to be:

- Simple to understand
- Easy to implement
- Machine-readable
- Human-readable
- Technology-independent

---

# Why Digital Trust Profile?

More and more digital services use Artificial Intelligence.

Users, organizations, and software systems increasingly need answers to simple questions such as:

- Who provides this service?
- Does it use AI?
- What is the AI used for?
- Does AI make automated decisions?
- Is there human oversight?
- Where can I find the Privacy Policy?

Today, this information is often scattered across multiple documents or is not available at all.

The Digital Trust Profile provides one standard place to publish this information.

---

# Goals

The Digital Trust Profile aims to:

- improve transparency;
- simplify trust information;
- support AI agents and automated systems;
- provide a common structure for digital services.

The profile is a transparency standard.

It does **not** certify trustworthiness and does **not** replace legal or regulatory compliance.

---

# Specification

Current version:

**Digital Trust Profile Standard 0.0.1 (Draft)**

The draft specification is available here:

```
specification/DTP-0.0.1.md
```

---

# Repository Structure

```
digital-trust-profile/

README.md

LICENSE

CHANGELOG.md

specification/
    DTP-0.0.1.md

schema/
    dtp-0.0.1.schema.json

examples/
    ai-governance-model-lab.json
```

---

# Reference Implementation

The first implementation of the Digital Trust Profile is available in:

- AI Governance Model Lab

It demonstrates:

- Human-readable Digital Trust Profile
- Machine-readable JSON profile
- Publication using:

```
/.well-known/digital-trust.json
```

---

# Current Status

Version: 0.0.1

Status: Draft

License: Apache License 2.0

---

# Roadmap

Version 0.0.1

- Draft specification
- Core profile
- JSON format
- First implementation

Version 0.1.0

- Expanded field definitions
- JSON Schema improvements
- Validation rules
- Optional extensions

Version 1.0.0

- Stable standard based on implementation experience and community feedback.

---

# Contributing

Feedback, ideas, and implementation experience are welcome.

The goal of the Digital Trust Profile is to develop a practical transparency standard that can be adopted by digital services of any size.

---

# License

Apache License 2.0

---

Maintained by **BKlein Digital Labs**.

Building practical AI solutions for a digital world.

contact@bkleindigital.com