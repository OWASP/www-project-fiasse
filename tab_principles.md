---
title: Principles
layout:  null
tab: true
order: 3
tags: fiasse
---

## Core Principles

- The Securable Principle:
The Securable Principle in FIASSE says that software is never in a final, fixed state of “secure”; instead, it must be built so it can be secured and kept secure over time. Security is treated as an ongoing property of the system’s design, code, and operations rather than a checkbox reached after tests or reviews.

- The Derived Integrity Principle:
The Derived Integrity Principle states that an application must not implicitly trust or adopt unmanaged external context, such as client-supplied data or other untrusted inputs, when making critical decisions. Instead, it should derive important facts (like identity, permissions, pricing, and state) from authoritative, controlled sources to preserve integrity and reduce the risk of security breaches.

- Actionable Security Intelligence:
Instead of forcing development to decode testing terminology, security should analyze results and collaborate with Software Engineering on systemic flaw reductions.

- The Transparency Principle:
Transparency is about showing clear, contextualized visibility into how the system operates, makes decisions, and handles data. This includes clear intent in architecture reflected in the implementation.

- Canonical Input Handling
The practice of converting all incoming data into a well-defined, validated form before it is used anywhere in the system. This supports the Securable and Derived Integrity principles by making sure that every decision is based on normalized, predictable input instead of raw, inconsistent, or attacker-shaped data.

## Core Values

- Securable Attributes over Security Controls:
Rather than focusing on security controls, checklists, or gates, the emphasis is on building software with inherent qualities that make it easier to analyze, modify, test, and trust.

- Participation over Assessment:
Prefer active participation in the development process rather than assessment, review, or reporting. This means security participation in architecture, design and requirements in whatever form that takes. This makes assessment part of an iterative and empirical process.

- First Principle Alignment:
While the Security discipline works to 'reduce the probability of material impact', the Software Engineering discipline works to 'resiliently add computing value'. FIASSE provides the structure and knowledge to dovetail these two efforts.

- Business Alignment:
FIASSE facilitates Application Security's understanding of business needs as given to software development. This ensures that security concerns are addressed without disrupting development workflows. Structured alignment allows security to increase their impact on the security outcomes of development.
