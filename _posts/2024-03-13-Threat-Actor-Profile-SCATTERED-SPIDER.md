---
date: 2024-03-13
layout: post
title: Threat Actor Profile SCATTERED SPIDER
subtitle: 'Exploring the depths of SCATTERED SPIDER activities and tactics.'
description: An in-depth look into SCATTERED SPIDER, a prominent eCrime group known for its diverse cybercriminal activities across various industries and countries, leveraging sophisticated techniques for financial gain.
image: /assets/img/1700719276274.png
optimized_image: /assets/img/APT/CS_Actor_Icons_ScatteredSpider.png
category: cybersecurity
tags:
  - cybersecurity
  - threat intelligence
  - eCrime
author: cybersecurityanalyst
paginate: true
---
SCATTERED SPIDER has marked its presence in the cybercrime world since March 2022, actively targeting industries such as Entertainment, Consumer Goods, Pharmaceutical, Cryptocurrency, and many others across 14 countries including Canada, Switzerland, Italy, and the United States. This actor is notorious for utilizing malware like CS-PARALYZER, Alphv, and CobaltStrike, among others, to infiltrate and exploit victim networks.

> SCATTERED SPIDER's operations are characterized by a blend of sophisticated social engineering tactics and advanced technical methods to bypass security measures, including multifactor authentication.

With criminal motivations, SCATTERED SPIDER's activities have evolved over time, showing adaptability and a keen focus on lucrative targets. Their tactics include smishing, vishing, and exploitation of IT helpdesks to perform actions such as self-service password resets for targeted accounts, directly impacting the security posture of affected organizations.

## Actor Profile

| Attribute            | Details                                                                                                                                                                                                                                     |
|----------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Actors**           | SCATTERED SPIDER
| **Last active**      | Mar 2024
| **Status**           | Active
| **Origin**           | Unknown
| **Actor type**       | eCrime
| **Motivation**       | Criminal
| **Community identifiers**| Octo Tempest, Roasted 0ktapus, Scatter Swine, UNC3944, Storm-0875, LUCR-3                                                                                                                                                                     
| **Target industries**| Entertainment, Consumer Goods, Pharmaceutical, Cryptocurrency, Telecommunications, Consulting and Professional Services, Architectural and Engineering, Insurance, Energy, Aerospace, Food and Beverage, Technology, Retail, Legal, Media, Manufacturing, Logistics, Real Estate, Hospitality, Travel, Financial Services
| **Target countries** | Canada, Switzerland, Italy, United States, Japan, United Kingdom, Brazil, Philippines, Singapore, India, Germany, Australia, Thailand, France
| **Malware developed**| CS-PARALYZER
| **Malware used**     | Alphv, rsocx, TightVNC, CS-PARALYZER, Kohgapy, AlphvSphynx, MHax, ScreenConnect, Nmap, CobaltStrike, Chisel, SorillusRAT
| **Actor activity**   | Sandbox reports: 0, Endpoint detections: 0, Vulnerabilities: 0
| **Intel reports**    | [cisa.gov](https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-320a)

### Detailed Analysis

SCATTERED SPIDER's campaign against high-revenue private sector organizations demonstrates their strategic shift towards ransomware as a primary means of extortion. Their initial focus on CRM and BPO firms, as well as telecommunication and technology companies, has expanded to include a broad array of sectors.

The group leverages identity abuse, targeting IT and security personnel for their access to critical systems and documentation, which facilitates lateral movement and account compromise within victim networks. C-suite executives and individuals with direct access to financial resources are also prime targets for SCATTERED SPIDER.

**Key Takeaways:**

- Sophisticated social-engineering techniques are central to gaining initial access.
- The group exploits single sign-on (SSO) dashboards, Microsoft Office 365/Azure, VPNs, and edge devices.
- SIM-swapping, MFA notification fatigue, and manipulation of helpdesk agents are common tactics to bypass multifactor authentication.

By understanding SCATTERED SPIDER's methods and motivations, organizations can better prepare and protect themselves against this and similar cybercriminal actors.