---
title: Principles
layout:  null
tab: true
order: 3
tags: fiasse
---

## Core Principles

- The Securable Principle:
The Securable Principle says that software is never in a final, fixed state of “secure”; instead, it must be built so it can be secured and kept secure over time. Security is treated as an ongoing property of the system's design, code, and operations.

- The Derived Integrity Principle:
The Derived Integrity Principle states that an application must not implicitly trust or adopt unmanaged external context, such as client-supplied data or other untrusted inputs, when making critical decisions. Instead, it should derive important facts (like identity, permissions, pricing, and state) from authoritative, controlled sources to preserve integrity.

- Canonical Input Handling:
The practice of converting all incoming data into a validated and well-defined state before it is used anywhere in the system. This supports the Securable and Derived Integrity principles by making sure that every decision is based on normalized, predictable input instead of raw, inconsistent, or attacker-shaped data.

- The Transparency Principle:
How the system works should be perceptible so engineers and stakeholders can see what it is doing, why it is doing it, and how. In software engineering terms, it pushes teams to design systems whose behavior is visible..

## Software Engineering Principles

- Boundary *Control Principle:
Flexibility within a system's interior is an engineering asset to be preserved; control at every trust boundary is a security requirement to be enforced. These objectives are complementary, not competing.
*Control in this principle refers to its software-engineering sense of the word.

- Request Surface Minimization:
The smaller and more intentional the surface that accepts external input, the fewer assumptions the rest of the system has to defend. Accept only what the operation needs, and reject everything else explicitly.

- Principle of Least Astonishment:
A system should behave the way a reasonable user, operator, or developer expects. Surprise is a source of defects, including security defects, because behavior that diverges from expectation is behavior that is not being reviewed or defended.

- Actionable Security Intelligence Principle
Security output becomes valuable only once it has been translated into prioritized, engineering-grounded direction calibrated to the developer's context. Raw tool output, exploit-centric narratives, and unfiltered vulnerability lists are information, not yet intelligence.

## Core Values

- Securable Attributes over Security Controls:
Rather than focusing on security controls, checklists, or gates, the emphasis is on building software with inherent qualities that make it easier to analyze, modify, test, and trust. Keeping the system defensible matters more than tests that will fail without preparation. Security controls remain valid where they are meant to work, which includes requirements and assurance. Building defensible software is a different job, and it needs performed with intention.

- Participation over Assessment:
Structured participation by the security team in the development process yields better results than security assessment alone, which tends to be late and expensive. This means security participation in architecture, design and requirements in whatever form that takes. This makes assessment part of an iterative and empirical process.

 > It is ok to give development the answers to the security test because they have to implement it functionally to pass. In software engineering terms this is called requirements.

- First Principle Alignment:
While the Security discipline works to 'reduce the probability of material impact', the Software Engineering discipline works to 'resiliently add computing value'. FIASSE provides the structure and knowledge to dovetail these two efforts.

- Business Alignment:
FIASSE facilitates Application Security's understanding of business needs as given to software development. This ensures that security concerns are addressed without disrupting development workflows. Structured alignment allows security to increase their impact on the security outcomes of development.
