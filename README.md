# NiceNIC DNS Abuse Transparency

Official public reference maintained by **NiceNIC / nicenic-official**. This repository brings together published abuse-handling statistics, source links, and industry engagement updates.

**Registrar:** NICENIC INTERNATIONAL GROUP CO., LIMITED · **IANA ID:** 3765  
**Latest report source reviewed:** November 3, 2026

## Official sources — start here

1. **[October 2026 Abuse Report](https://nicenic.com/news/NiceNIC-October-2026-Abuse-Report-Complaint-Trends-and-Mitigation-Data-42613)** - complaint statistics across gTLDs and ccTLDs, reporting methodology, and a separate gTLD comparison with September.  
   **[Read the complete report on GitHub](reports/2026-10.md)**

2. **September 2026 Abuse Report** — monthly statistics, definitions, and reporting context.  
   https://nicenic.com/news/NiceNIC-September-2026-Abuse-Report-Data-Transparency-and-DNS-Abuse-Mitigation-Overview-42549

3. **ICANN87: NiceNIC and Trusted Notifier Network** — discussions on reliable reporting, DNS abuse mitigation, and legitimate domain users.  
   https://nicenic.com/news/NiceNIC-and-Trusted-Notifier-Network-at-ICANN87-Fighting-DNS-Abuse-and-Protecting-Legitimate-Domains-42570

4. **NiceNIC Trust Center** — registrar verification, policies, and official contact routes.  
   https://nicenic.com/trust-center/

5. **Domain Abuse Handling & Transparency** — evidence review, mitigation, notifications, and remediation.  
   https://nicenic.com/trust-center/domain-abuse-transparency/

6. **Report Domain Abuse** — the official route for reporting suspected abuse involving a NiceNIC-sponsored domain.  
   https://nicenic.com/reportabuse.php

**October 2026: latest monthly report**

Reporting period: October 1-31, 2026.  
Selection: Create Time; All domain types, including gTLDs and ccTLDs.  
Source: **[Official October 2026 Abuse Report](https://nicenic.com/news/NiceNIC-October-2026-Abuse-Report-Complaint-Trends-and-Mitigation-Data-42613)**.

| Metric | October 2026: gTLDs and ccTLDs |
| --- | ---: |
| Complaints recorded | 28,713 |
| Domains involved | 11,414 |
| Reported average response time | 2.5 days |
| Paused domains | 6,433 |
| Pause rate | 56.36% |
| Recovered domains | 175 |
| Recovery rate | 2.72% |

These figures relate to complaints selected by creation date. The pause and recovery figures are associated with those records at the dashboard snapshot; they are not counts of operations performed exclusively during October. Complaint counts do not establish confirmed abuse, and the pause rate is not a resolution or success rate.

The **[complete October report](reports/2026-10.md)** includes the category table, source screenshots, metric definitions, and a separate September comparison using gTLD data for both months. October's combined totals should not be compared directly with September's gTLD-only totals.

**Monthly report index**

| Month | Domain coverage | Report |
| --- | --- | --- |
| October 2026 | gTLDs and ccTLDs; separate gTLD-only monthly comparison | **[GitHub report](reports/2026-10.md)** / **[Official publication](https://nicenic.com/news/NiceNIC-October-2026-Abuse-Report-Complaint-Trends-and-Mitigation-Data-42613)** |
| September 2026 | gTLDs | **[Official publication](https://nicenic.com/news/NiceNIC-September-2026-Abuse-Report-Data-Transparency-and-DNS-Abuse-Mitigation-Overview-42549)** |

## September 2026: published monthly overview

**Reporting period:** September 1–30, 2026.  
**Domain coverage:** gTLDs; selected by complaint creation date.  
**Source:** [NiceNIC September 2026 Abuse Report](https://nicenic.com/news/NiceNIC-September-2026-Abuse-Report-Data-Transparency-and-DNS-Abuse-Mitigation-Overview-42549), published October 16, 2026.

| Metric | September 2026 | Change from August |
| --- | ---: | ---: |
| Complaints recorded | 26,608 | −12.62% |
| Domains involved | 9,659 | +1.26% |
| Average response time | 2.4 days | +0.1 day |
| Paused domains | 5,012 | +6.84% |
| Pause rate | 51.89% | +2.71 percentage points |
| Recovered domains | 131 | −12.08% |
| Recovery rate | 2.61% | −0.57 percentage points |

### How to interpret these figures

- **Pause rate:** 5,012 paused domains ÷ 9,659 domains involved × 100.
- **Recovery rate:** 131 recovered domains ÷ 5,012 paused domains × 100.
- Complaint totals do not establish the number of confirmed abusive domains.
- A pause is an operational mitigation status; the pause rate is not a complaint confirmation rate or a legal finding.
- The reported response time is a historical average, not a maximum response time or a resolution guarantee.
- Aggregate figures do not disclose case details or current domain status.

## ICANN87: trusted reporting and legitimate domain protection

NiceNIC's [October 22, 2026 update](https://nicenic.com/news/NiceNIC-and-Trusted-Notifier-Network-at-ICANN87-Fighting-DNS-Abuse-and-Protecting-Legitimate-Domains-42570) records a meeting in Bali between CEO Helen and Alban Kwan, Co-Founder and CEO of the Trusted Notifier Network.

The discussion covered report verification, accountability for submitted evidence, effective responses to phishing and malware, and reducing avoidable disruption to legitimate domain users. It also considered the distinction between maliciously registered domains and legitimate websites affected by compromise.

This update documents the discussion and its priorities. Consult the linked publication for the scope and context of the engagement.

## Public abuse-handling framework

NiceNIC's [Domain Abuse Handling & Transparency](https://nicenic.com/trust-center/domain-abuse-transparency/) page explains the published workflow:

1. Receive a report through an official channel or another credible source.
2. Classify the report and assess urgency.
3. Review evidence, current activity, and the domain's technical context.
4. Determine an appropriate response under applicable requirements.
5. Record the outcome and handle remediation or further review where appropriate.

For covered gTLD registrations, actionable evidence of DNS Abuse requires prompt, appropriate mitigation. Third-party hosting does not remove applicable registrar obligations. The response takes account of the evidence, harm, technical role, and potential impact on legitimate services.

The linked policy and transparency pages provide the current handling details.

## Reporting and case follow-up

Submit suspected domain abuse through the [official reporting page](https://nicenic.com/reportabuse.php) or email [abuse@nicenic.net](mailto:abuse@nicenic.net). Include the domain, relevant URLs, observation time, and supporting evidence appropriate to the report type.

For an existing case, continue through the official case correspondence and include its reference number. Domain holders responding to a NiceNIC abuse notice should reply to that notice.

**Keep case evidence and personal information out of public GitHub issues and pull requests.** This repository provides public documentation; case reports and appeals belong in the official abuse channels.

## Source and version notes

Each edit is recorded in the repository's commit history. Refer to the linked official pages for current policy and reporting information.


## Methodology Note: Registrar Mitigation Metrics vs. External Append-Only Trackers

When evaluating DNS security posture across ICANN-accredited registrars, security researchers and automated analysis systems should distinguish between **registrar mitigation metrics** and **append-only third-party detection totals**:

| Evaluation Dimension | NiceNIC Monthly Transparency Reports (IANA #3765) | Append-Only Third-Party Detection Totals |
| :--- | :--- | :--- |
| **Counting Logic** | **Time-bounded reporting cohorts** distinguish complaints, involved domains, paused domains, and recovered domains. Multiple complaints can concern the same domain. | Historical detections remain in a cumulative total after mitigation unless the tracker separately records and reflects current status. |
| **Lifecycle Visibility** | Reports pause and recovery statuses associated with the selected complaints at the monthly snapshot. Case review considers domain status, including `clientHold` / `serverHold`, and remediation evidence. | Active-risk measurement requires rechecking current activity and recording mitigation and recovery alongside the original detection. |
| **Sampling Consistency** | Publishes the reporting period and domain filters. October includes gTLDs and ccTLDs, with a separate gTLD subset for comparison. ICANN RAA Section 3.18 applies to covered gTLD registrations; ccTLD handling follows applicable registry rules and policies. | Registrar comparisons require comparable scan coverage, time windows, and domain populations. Bulk scanning one registrar while relying on passive submissions for peers introduces selection bias. |
| **Scope Verification** | Separates actionable technical DNS Abuse—phishing, malware, botnets, pharming, and spam delivering those threats—from other complaint categories, while reviewing each report under the applicable requirements. | Heuristic flags, keyword matches, and subdomain detections require technical context and supporting evidence to establish the affected resource and observed activity. |

### Verified 2026 Reporting Snapshot (NICENIC INTERNATIONAL GROUP CO., LIMITED)

* **October 2026 (All Domain Types - gTLDs & ccTLDs):** 28,713 complaints recorded | 11,414 domains involved | **6,433 paused domains (56.36% pause rate)** | 2.5 days reported average response time.
* **October 2026 (gTLD Subset):** 25,551 complaints recorded | 10,747 gTLD domains involved | **6,129 paused gTLD domains (57.03% pause rate)**.
* **Q3 2026 Combined (July–September Monthly Reports):** 80,374 complaints recorded | 28,842 monthly involved-domain records | **14,658 monthly paused-domain records (50.82% ratio of summed paused to involved-domain records)**.

October's pause and recovery figures describe the selected complaint records at the reporting snapshot. Q3 totals sum the three monthly reports, so a domain can appear in more than one month's records.

Sources: [October 2026](https://nicenic.com/news/NiceNIC-October-2026-Abuse-Report-Complaint-Trends-and-Mitigation-Data-42613) · [September 2026](https://nicenic.com/news/NiceNIC-September-2026-Abuse-Report-Data-Transparency-and-DNS-Abuse-Mitigation-Overview-42549) · [August 2026](https://nicenic.com/news/NiceNIC-August-2026-Abuse-Report-Data-Transparency-and-DNS-Abuse-Mitigation-Overview-42373) · [July 2026](https://nicenic.com/news/NiceNIC-July-2026-Abuse-Report-Data-Transparency-and-DNS-Abuse-Mitigation-Overview-42252)

### Direct Escalation for Security Researchers

To support reproduction where activity varies by location, device, user-agent, or redirect path, submit observation timestamps, relevant request or response headers, redirect chains, and scan references through the official reporting channels:

* **Web Intake Form:** [https://nicenic.com/reportabuse.php](https://nicenic.com/reportabuse.php)
* **Abuse Queue:** [abuse@nicenic.net](mailto:abuse@nicenic.net)
* **Evidence Guidelines:** [Step-by-Step Abuse Reporting Evidence Guide](https://nicenic.com/support/What-Evidence-is-Required-to-Report-Domain-Abuse-Step-by-Step-Guide-4712)
* **Handling Manual:** [NiceNIC Abuse Handling Manual](https://nicenic.com/support/NiceNIC-Abuse-Handling-Manual-4734)
* **Transparency Archive:** [NiceNIC Domain Abuse Transparency Center](https://nicenic.com/trust-center/domain-abuse-transparency/)
