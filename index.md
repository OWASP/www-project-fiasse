---

layout: col-sidebar
title: OWASP FIASSE
tags: developer ssem fiasse resilience maintainability software-engineering trustworthiness reliability
level: 2
type: documentation
pitch: security that is relentlessly practical to software engineering

---

The Framework for Integrating Application Security into Software Engineering (FIASSE) is a vendor-neutral approach to embedding security directly into the software engineering discipline. FIASSE (pronounced /feiz/) addresses persistent challenges—such as slow progress in AppSec, friction between security and development, and the limitations of “shift left”. The framework begins by establishing First Principles, which serve as the foundation for the engineering principles and attributes defined in the Securable Software Engineering Model. These principles and attributes guide the subsequent software engineering strategies for creating securable software. This creates a development-centric approach that enables developers to excel while ensuring securable outcomes.

With the rise of AI-generated code, which introduces new security challenges, it is more important than ever to develop a framework that ensures that new software is inherently securable. We need a set of behavioral principles that can govern developers and code assistants. Best practices alone are not enough; developers must have the integrity of the timebox, and security processes must be streamlined.

FIASSE introduces the Securable Software Engineering Model (SSEM, pronounced /si:m/), which uses established engineering terms to define the core attributes of securable software, focusing on how Maintainability, Trustworthiness, and Reliability contribute to security. This model enables developers to build software that is easier to analyze, modify, and test for security. It does not require them to have years of security experience or adopt an adversarial mindset. By aligning security with the realities of software development, FIASSE helps teams create systems that are resilient and adaptable, supporting both business objectives and security concerns.

## Fundamentals

While this framework attempts to give structure to the relationship between security and software engineering, the primary audience is Software Engineers. Therefore, the fundamentals are framed from that perspective:

- Prefer securable attributes over security controls; security controls should be expressed through requirements.
- Prefer security participation over review - AppSec should be skilled enough to participate in product, architecture, and design processes.
- Prefer integration over assessment - where security traditionally performs assessments, it is more timely for them to be a part of those processes.
- Prefer alignment with business over imposing disruptive SLAs - shortening timelines for remediation is an illogical strategy.
- Prefer actionable security intelligence over 'Shoveling Left' - find-and-fix is an ineffective, unsustainable strategy.

### Scope

FIASSE does not intend to replace existing security assurance advice like OWASP SAMM, OWASP ASVS, etc. Instead, it aims to integrate security more deeply into the Software Engineering discipline, providing a structured approach to securing code through engineering practices. This will reduce findings and turnaround time, thereby decreasing the probability of material impact.

## Road Map

- [x] Establishment of project governance and contribution guidelines.
- [ ] Use feedback to refine the framework and its components.
- [ ] Formal publication of FIASSE and SSEM specifications, including their core attributes and integration strategies.
- [ ] Development of an SSEM Primer/Introduction Guide to help software engineers understand the model and its application.
- [ ] Create a guide for Application Security practitioners on using and teaching FIASSE with relevant security requirements and code examples.
- [ ] Collection of SSEM adoption use cases or patterns to illustrate practical applications and benefits.
