---
title: the_model
layout:  null
tab: true
order: 3
tags: fiasse, ssem, feedback
---

## The Model

The Securable Software Engineering Model (SSEM) is centered on providing a design language that uses established software engineering terms to define the core attributes that make software "securable". These attributes are:

- **Maintainability**: The ease with which software can be modified to correct defects, improve performance, or adapt to a changed environment. This includes the ability to **analyze**, **modify**, and **test** software for security vulnerabilities without requiring developers to adopt an adversarial mindset.
- **Trustworthiness**: The degree to which software can be trusted to behave as expected, particularly in the face of potential security threats. This includes the ability to ensure that software meets its security requirements and behaves predictably under various conditions.
- **Reliability**: The ability of software to perform its intended functions under specified conditions for a specified period of time. This includes resilience to failures and the ability to recover from errors without compromising security.

The detail and structure of the SSEM are designed to align with the realities of software development, enabling developers to create systems that are not only securable presently but also adaptable to future changes. By focusing on these core attributes, FIASSE aims to provide a design language that enhances security, maintains developer velocity, and improves software systems ability to adapt to a changing security landscape all while maintaining their usability and performance.

As with humans, Generative AI models can be trained to produce software that is securable. However, this requires a clear understanding of the attributes that make software securable and the ability to apply these attributes in practice. The SSEM provides a framework for this understanding, enabling developers and AI models to work together to create software that is inherently securable.

For more information on the Securable Software Engineering Model (SSEM), please refer to the [FIASSE RFC](https://github.com/Xcaciv/securable_software_engineering/blob/main/docs/FIASSE-RFC.md#3-the-securable-software-engineering-model-ssem).

## SSEM Usage

FIASSE is structured in a three pillar approach. Those pillars are:

- Security Requirements
- Securable Code
- Application Security Assurance

The model has various uses beyond being standard terms to clearly define intentional attributes in software engineering. They also form the basis for a set of behavioral principles that can govern developers and code assistants. They can also be used to ground security requirements making them more relevant and actionable. It can also give a clear context to assurance activities for more definitive impact on the overall application security posture.

This framework does not intend to go deep into requirements or assurance activities. There are standards and frameworks that generally guide these activities. There are existing high quality sources for security requirements and security feature guidance. There are also an abundance of sources for assurance guidance. FIASSE gives priority to software engineering level strategies and structured interactions with security teams in the context of requirements and assurance for long term success.
