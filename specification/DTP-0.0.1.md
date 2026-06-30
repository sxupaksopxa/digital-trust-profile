# Digital Trust Profile Standard
Version: 0.0.1
Status: Draft
License: Apache License 2.0
Author: BKlein Digital Labs

## About this Document

This document describes Version 0.0.1 of the Digital Trust Profile Standard.

It is published to encourage discussion, practical implementation, and community feedback.

The Digital Trust Profile is an open specification that will evolve based on implementation experience.

# 1. Introduction
More and more digital services use Artificial Intelligence (AI) to generate information, recommendations, and decisions. Users and organizations want to know how these services work and whether AI is involved.
Today, most digital services publish documents such as Privacy Policies and Terms of Use. These documents explain legal and privacy information, but they do not provide a simple and consistent description of AI usage, governance, or other trust-related information.
The Digital Trust Profile provides a standard way for digital services to publish this information. It is designed to be both human-readable and machine-readable, making it useful for people as well as AI agents and automated systems.
This document introduces the first draft of the Digital Trust Profile Standard. It is published to encourage discussion, practical implementation, and community feedback.

# 2. Goal
The goal of the Digital Trust Profile is to provide a simple and standard way for digital services to publish trust information.
The profile helps digital service providers:
	•	publish transparent information about their services;
	•	describe how AI is used;
	•	make trust information easy to find and understand;
	•	provide information that can be read by both people and software.
The Digital Trust Profile is a transparency standard.
It does not:
	•	certify that a service is trustworthy;
	•	replace legal or regulatory requirements;
	•	prove compliance with laws or regulations.
Instead, it provides structured information that helps people and automated systems make their own trust decisions.

# 3. Scope
The Digital Trust Profile can be used by any digital service that wants to publish transparent information about its operation.
Examples include:
	•	AI applications
	•	Web applications
	•	SaaS platforms
	•	APIs
	•	Digital assistants
	•	AI agents
	•	Enterprise services

The Digital Trust Profile is technology-independent.
It describes the behavior of a digital service, not the technology used to build it.

# 4. Target Audience
The Digital Trust Profile is designed primarily for software systems that automatically discover and evaluate digital services.
Examples include:
	•	AI agents
	•	Enterprise platforms
	•	Procurement systems
	•	Governance and compliance tools
	•	Browser extensions
	•	Security platforms

The profile is also useful for people who want more information about a digital service, including:
	•	software developers
	•	service providers
	•	auditors
	•	security professionals
	•	compliance professionals
	•	enterprise customers

Although the profile can be read by anyone, it is designed primarily to provide machine-readable transparency information.

# 5. Purpose of the Profile
The Digital Trust Profile provides a standard way for digital services to publish transparent information about how they operate.
It helps people and software understand:
	•	who provides the service;
	•	whether the service uses AI;
	•	the purpose of the AI;
	•	whether AI makes automated decisions;
	•	whether human oversight is required;
	•	how user information is handled;
	•	where to find additional information about the service.

The profile is designed to be easy to read by both people and software.

# 6. Regulatory Context
Many countries and organizations are introducing new rules and guidelines for the responsible use of Artificial Intelligence.
These developments increase the need for digital services to provide clear and transparent information about how AI is used.
The Digital Trust Profile supports this goal by providing a simple and standard way to publish transparency information.
The Digital Trust Profile is not a legal or regulatory framework.
It does not replace legal requirements or prove compliance with any law or regulation.
Future versions of the Digital Trust Profile may include optional mappings to regulations such as the EU AI Act, while remaining independent of any specific legal framework.

# 7. Design Principles
The Digital Trust Profile is based on the following principles.

## Transparency
The profile should provide clear and useful information about how a digital service operates. Users and software should be able to understand whether AI is used and how the service works from a trust perspective.

## Simplicity
The profile should be easy to understand and easy to implement. A digital service should be able to publish a basic Digital Trust Profile with only a small number of required fields.


## Machine Readability
The profile should be published in a format that software systems, AI agents, and automated tools can read and process.

## Human Readability
The information should also be easy for people to read and understand. Technical or legal language should be avoided whenever possible.

## Extensibility
The core profile should remain small and stable. New information should be added through optional extensions instead of increasing the number of required fields.

## Technology Independence
The profile describes how a digital service operates, not how it is built. It should work for any programming language, framework, cloud platform, or AI model.

## Backward Compatibility
Future versions of the standard should remain compatible with earlier versions whenever possible.

# 8. Minimum Required Fields (Version 0.0.1)
Version 0.0.1 defines only the minimum information required to publish a Digital Trust Profile.
The goal is to make the profile simple to implement while providing useful transparency information.

## Service
Describes the identity of the digital service.
Required fields:
	•	Service name
	•	Provider
	•	Purpose
	•	Website
	•	Domain

## Verification
Describes whether the published profile has been verified.
Required fields:
	•	Verification status

## Artificial Intelligence
Describes how Artificial Intelligence is used by the digital service.
Required fields:
	•	AI used
	•	Primary purpose
	•	AI capabilities
	•	Human oversight
	•	Explainability

## Governance
Describes how AI supports decisions within the service.
Required fields:
	•	Decision support
	•	Automated decisions
	•	Methodology published

## Privacy
Provides basic information about how user information is handled.
Required fields:
	•	Privacy Policy available

## Contact
Provides contact information for the digital service provider.
Required fields:
	•	Contact email


# 9. Machine-readable Format
The Digital Trust Profile is published as a JSON document.
The recommended location is:
/.well-known/digital-trust.json

This location allows software systems, AI agents, and other automated tools to discover the profile in a consistent way.
The profile should be encoded using UTF-8 and follow the Digital Trust Profile specification.
Future versions of the standard may define:
	•	a formal JSON Schema;
	•	validation rules;
	•	optional extensions.

# 10. Versioning Strategy
The Digital Trust Profile will evolve incrementally based on practical implementation and community feedback.

## Version 0.0.1
Draft Specification
Focus:
	•	vision
	•	goal
	•	scope
	•	design principles
	•	minimum required fields
	•	machine-readable publication
The purpose of this version is to introduce the Digital Trust Profile and collect implementation feedback.

## Version 0.1.0
Expanded Draft
Focus:
	•	detailed field definitions
	•	JSON Schema
	•	validation rules
	•	optional extensions
The purpose of this version is to improve the specification based on implementation experience.

## Version 1.0.0
Stable Standard
The Digital Trust Profile will become a stable standard after sufficient implementation experience and community feedback.
The goal is to provide a simple, understandable, and reusable transparency standard for digital services.

# 11. Reference Implementation
This draft specification already has a working reference implementation.
The first implementation is available in AI Governance Model Lab and demonstrates:
	•	a human-readable Digital Trust Profile;
	•	a machine-readable JSON profile;
	•	publication using the recommended endpoint:

/.well-known/digital-trust.json

Future implementations may extend the profile while remaining compatible with this specification.

# 12. Future Direction
The Digital Trust Profile is an early draft and will continue to evolve based on practical implementation and community feedback.
Future work may include:
	•	improving the core profile;
	•	clarifying field definitions;
	•	expanding the JSON Schema;
	•	adding optional profile extensions;
	•	publishing additional reference implementations.

The main goal is to keep the Digital Trust Profile simple, understandable, and easy to implement.
The scope of the Digital Trust Profile will grow only when practical implementation shows that additional information is needed.