---

layout: col-sidebar
title: OWASP FIASSE
tags: developer ssem fiasse resilience maintainability software-engineering trustworthiness reliability
level: 2
type: documentation
pitch: security that is relentlessly practical to software engineering

---

The Framework for Integrating Application Security into Software Engineering (FIASSE) is a vendor-neutral approach to embedding security directly into the software engineering discipline. FIASSE (pronounced /feiz/) addresses persistent challenges—such as slow progress in AppSec, friction between security and development, and the limitations of “shift left”. It does this by focusing on a developer-centric, collaborative model. With the rise of AI-generated code, it is more important than ever to develop a framework that ensures that new software is inherently securable. We need a set of behavioral principles that can govern developers and code assistants. Best practices alone are not enough; developers must be allowed the integrity of the timebox and security must have the 'paved roads' it needs to contribute effectively.

FIASSE introduces the Securable Software Engineering Model (SSEM, pronounced /si:m/), which uses established engineering terms to define the core attributes of securable software: Maintainability, Trustworthiness, and Reliability. This model enables developers to build software that is easier to analyze, modify, and test for security, without requiring them to have years of security experience or adopt an adversarial mindset. By aligning security with the realities of software development, FIASSE helps teams create systems that are resilient and adaptable, supporting both business objectives and security concerns.

## Fundamentals

While this framework attempts to give structure to the relationship between security and software engineering, the primary audience is Software Engineers. Therefore the fundamentals are framed from that perspective:

- Prefer securable attributes over security controls - security controls should be expressed through requirements.
- Prefer security participation over review, evaluation, or reporting after the fact - AppSec should be skilled enough to participate in product, architecture and designs processes.
- Prefer integration over assessment - where security traditionally perform assessments, it is more timely for them to be a part of those processes.
- Prefer alignment with business over imposing disruptive SLAs - arbitrarily shortening timelines for remediation is an illogical strategy.
- Prefer actionable security intelligence over 'Shoveling Left' - find-and-fix is an ineffective, unsustainable strategy.

### Scope

FIASSE does not intend to replace existing security assurance advice like OWASP SAMM, OWASP ASVS, etc. Instead it intends on cementing the Software Engineering discipline as the means by which code is secured. Thus reducing findings and turnaround time in order to reduce the probability of material impact.

## Road Map

- [x] Establishment of project governance and contribution guidelines.
- [ ] Formal publication of FIASSE and SSEM specifications, including their core attributes and integration strategies.
- [ ] Use feedback to refine the framework and its components.
- [ ] Development of an SSEM Primer/Introduction Guide to help software engineers understand the model and its application.
- [ ] For Application Security practitioners, create a guide on how to use and teach FIASSE.
- [ ] Collection of SSEM adoption use cases or patterns to illustrate practical applications and benefits.
