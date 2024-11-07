---
layout: post
title:  "Open Source Compliance for Security"
date:   2024-09-03 08:00:00 -0800
description: Open Source Methods Essential for Modern System Security and Compliance
author: fen-labalme
categories: featured
image: card-power.png
---

**BLUF:** We must adopt open source methods (transparency, collaboration, and collective intelligence) and widen the community and visibility of contributors to effectively manage the security, compliance, monitoring and assessment of (FISMA reportable) information systems in the continuously evolving cybersecurity landscape.

There is [growing effort](https://openssf.org/) to ensure the [security of systems built with open source software](https://www.whitehouse.gov/oncd/briefing-room/2024/08/09/fact-sheet-biden-harris-administration-releases-end-of-year-report-on-open-source-software-security-initiative-2/) or a supply chain dependence upon open source software. Riding the open source wave increases the speed at which new technologies can be incorporated into the CI/CD pipeline, bringing new features, greater accessibility and enhanced security. But security compliance and authorizations to operate are stuck in a decades old, manual process that is getting slower and more cumbersome as new technologies are brought to bear. (ref: NIST’s [AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework) with 74 new controls released July 2024.)

The OpenATO community is creating a collection of open source digital public goods that provide an essential, flexible and eventually comprehensive baseline for ensuring the security of systems. An open source, collaboratively maintained library of implementation and assessment tools is necessary to manage systems security compliance in this modern era.

No single entity can stay abreast of the continuously evolving digital landscape, from document management to development environments and hosting platforms where bad actors are employing ever more sophisticated attack vectors, or may simply take advantage of improper configuration.

To manage the testing of systems for cybersecurity compliance, the Department of Defense (DoD) has developed a series of Security Technical Implementation Guides (STIGs) for different applications and systems. Automated scanners employing the Security Content Automation Protocol (SCAP) can read these STIGs and test system configuration to ensure it is in compliance with best practices. But STIGs and SCAP only test static configuration compliance, and often lag well behind real world best practices. There is a clear need to enhance cybersecurity collaboration, following the best practices of open source software communities.

Until now, such cooperation/collaboration would have been problematic, as there was no common language for expressing control implementation statements and assessment processes/evidence collection. Everything has been managed manually and ad hoc, using e.g. Word and Excel documents, often converted to (even more static) PDF format for delivery to assessment officers. Fortunately, NIST is proposing the Open Security Controls Assessment Language (OSCAL), a machine readable, data centric _lingua franca_ that can express existing as well as emerging security vulnerabilities and mitigations.
