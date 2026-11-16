# NiceNIC Abuse Handling Manual

## 1. Purpose

NiceNIC maintains this Abuse Handling Manual to ensure that abuse complaints involving [domain names](https://nicenic.com/domain/) sponsored by NiceNIC are received, assessed, tracked, investigated, and addressed in a consistent, documented, and risk-based manner.

This manual is designed to achieve four outcomes at the same time:

1.protect Internet users and affected parties from ongoing harm;

2.meet NiceNIC's contractual obligations as an ICANN-accredited registrar;

3.provide fair, predictable, and documented handling for registrants and resellers;

4.demonstrate a clear, defensible, and auditable abuse response process.

NiceNIC will investigate abuse reports promptly and will take mitigation actions that are reasonably necessary based on the quality of the evidence, the nature of the reported activity, the likelihood of ongoing harm, and the risk of collateral damage to legitimate services. This approach is aligned with Section 3.18 of the 2013 RAA and ICANN's 2024 DNS Abuse Advisory.

## 2. Scope

This manual applies to:

- domain names sponsored by NiceNIC; 
- abuse reports submitted by individuals, companies, security researchers, trusted reporters, registries, law enforcement, or other authorities; 
- retail customers and reseller-managed names; 
- both DNS Abuse and non-DNS abuse or illegal-activity complaints. 

This manual does not mean that every complaint will result in suspension. NiceNIC will act according to the applicable contractual framework, registry rules, NiceNIC's Acceptable Use / Abuse Policy, and the evidence available in each case.

## 3. Definitions

## 3.1 ICANN Contractual DNS Abuse

For NiceNIC's contractual compliance purposes, DNS Abuse means:

- malware 
- botnets 
- phishing 
- pharming 

spam only when used as a delivery mechanism for one of the four categories above.

## 3.2 NiceNIC Expanded High-Risk Abuse Categories

NiceNIC may also classify certain matters as Expanded High-Risk Abuse Categories under its own abuse and risk rules, even where they are not automatically ICANN-defined DNS Abuse. These may include:

- child sexual abuse material (CSAM) or child exploitation content; 
- illicit drug sales or high-risk narcotics content; 
- crypto fraud schemes; 
- content creating imminent risk of serious harm; 
- other illegal activity where urgent action is justified by law, registry policy, competent authority request, or clear risk evidence. 

These categories must be assessed carefully. They are not automatically treated as ICANN DNS Abuse unless the evidence also shows phishing, malware, botnet activity, pharming, or qualifying spam. Tucows publicly describes a similar distinction between core DNS Abuse and broader content abuses it may act on at the DNS level.

## 3.3 Non-DNS Abuse / Other Complaints

These commonly include:

- trademark disputes; 
- DMCA / copyright claims; 
- adult content; 
- gambling or gaming content; 
- misleading or fraudulent content without technical DNS-abuse evidence; 
- pharmacy / drug content without qualifying DNS-abuse indicators; 
- general policy violations. 

These complaints may still be investigated and handled, but they do not automatically justify DNS-level suspension.

## 4. Guiding Principles

NiceNIC handles abuse reports according to the following principles:

- Evidence first. NiceNIC does not take DNS-level action based on keywords, assumptions, or unsupported allegations alone. 
- Risk-based response. Faster and stronger action applies where the evidence is actionable and the harm is ongoing or severe. 
- Least necessary disruption. NiceNIC may choose a mitigation method other than immediate suspension where the evidence indicates a compromise scenario and a full hold would create disproportionate collateral damage. 
- Consistency and documentation. Every case must be categorized, tracked, and recorded. 
- Clear separation of roles. NiceNIC is a registrar. In many cases, the hosting provider, platform operator, payment processor, or law enforcement may also be a relevant or more effective action point. 

This risk-based and collateral-damage-aware model matches ICANN's advisory, which states that the appropriate mitigation action may vary by circumstances and that suspension is not the only possible response.

## 5. Reporting Channels

NiceNIC shall maintain:

- a public abuse contact [email](https://nicenic.com/email/) on its website homepage or designated abuse page; 
- a published description of how abuse reports are received, handled, and tracked; 
- a dedicated 24/7 monitored abuse contact point for law enforcement and similar authorities as required under the RAA. 

NiceNIC may accept abuse reports through:

- abuse mailbox; 
- support ticket system; 
- webform; 
- trusted-reporter channel; 
- registry escalation; 
- law-enforcement / government channel. 

## 6. Minimum Information Required in a Complaint

To be processed efficiently, a complaint should include:

- the reported domain name; 
- the specific abusive URL, if any; 
- a clear description of the alleged abuse; 
- screenshots showing the content and the full URL; 
- full email headers where email abuse, phishing, or fraud is involved; 
- supporting evidence such as invoices, logs, malware analysis, blocklist results, or impersonation details; 
- complainant contact information; 
- proof of authorization where the complainant acts on behalf of a brand or victim entity. 

This matches both ICANN's recent complaint guidance and market practice published by registrars such as Namecheap.

## 7. Evidence Standards

## 7.1 Actionable Evidence

Evidence is actionable when the information reasonably available to NiceNIC is sufficient to determine that the sponsored domain name is being used for DNS Abuse or other enforceable abuse activity.

Examples include:

- a phishing page screenshot showing the full URL and impersonated brand; 
- a phishing email with full headers and linked malicious URL; 
- malware or exploit delivery from the reported domain or URL; 
- reputation/blocklist data that supports the reported conduct; 
- evidence of wallet-drainer code, seed-phrase theft, fake login harvesting, or credential capture; 
- multiple consistent signals from trusted or recognized sources. 

ICANN's current guidance uses this same "actionable evidence" standard and makes clear that registrars may also consider information they can reasonably access themselves.

## 7.2 Insufficient Evidence

Evidence is insufficient where the complaint contains only:

- a domain name with no abusive URL; 
- keywords only; 
- allegations without screenshots, headers, logs, or other support; 
- general statements that a name "looks suspicious"; 
- pure brand conflict allegations without abuse evidence. 

When evidence is insufficient, NiceNIC will request more information rather than taking immediate DNS-level action, unless independent internal review or trusted-source data supplies the missing basis.

## 7.3 Third-Party Intelligence

NiceNIC may consider third-party signals such as:

- reputable blocklists / RBLs; 
- malware or phishing feeds; 
- reputation services; 
- prior internal case history. 

Such signals are supporting factors, not a substitute for judgment. ICANN's enforcement materials expressly note that screenshots, RBL information, prior case history, EPP status changes, MX records, and the registrar's own investigation can all be relevant to compliance review.

## 8. Case Priority and Internal SLA

NiceNIC adopts the following internal operating targets. These are NiceNIC internal SLAs, not statements of ICANN-mandated fixed deadlines.

## Priority 0 - Emergency / Active Harm

Examples:

- active phishing harvesting credentials or payment data; 
- malware delivery; 
- botnet / command-and-control use; 
- CSAM; 
- law-enforcement emergency notice; 
- wallet-drainer or seed-phrase theft infrastructure. 

Target:

- first review immediately; 
- decision as fast as reasonably possible; 
- where actionable, mitigation normally within 24 hours, and no later than 48 hours absent exceptional facts. 

## Priority 1 - High-Risk Actionable Abuse

Examples:

- clear impersonation fraud; 
- repeat abuse linked to the same registrant/account; 
- domains already flagged by reliable third-party sources with corroborating evidence. 

Target:

- review within 1 business day; 
- mitigation or documented next step within 48 hours. 

## Priority 2 - Non-DNS Abuse with Sufficient Evidence

Examples:

- DMCA with proper notice; 
- trademark complaints; 
- illegal pharmacy or content complaints lacking qualifying DNS-abuse indicators. 

Target:

- acknowledge promptly; 
- notify registrant/[reseller](https://nicenic.com/reseller/) where appropriate; 
- request remediation or additional documentation. 

## Priority 3 - Incomplete / Low-Quality Reports

Target:

- acknowledgment and request for additional evidence; 
- no suspension solely on this basis. 

For reports from law enforcement or similar authorities covered by RAA 3.18.3, NiceNIC must ensure review within 24 hours by empowered personnel.

## 9. Workflow

## 9.1 Intake

Every report receives:

- case ID; 
- timestamp; 
- source classification; 
- domain linkage; 
- abuse category; 
- evidence status. 

If the domain is already on clientHold, serverHold, or on an approved pending-hold list, the system should automatically return a status notice to the complainant and suppress duplicate manual handling.

## 9.2 Triage

The case is classified by:

- DNS Abuse vs non-DNS abuse; 
- evidence sufficient vs insufficient; 
- authority / trusted-reporter status; 
- reseller vs retail account; 
- current domain status; 
- repeat-offender / repeat-case history. 

## 9.3 Investigation

The reviewer checks:

- reported URL or content; 
- RDAP / [WHOIS](https://nicenic.com/whois/) / creation timing / nameservers / MX; 
- internal account history; 
- prior complaints; 
- blocklists / third-party intelligence; 
- whether the issue appears intentional or caused by compromise; 
- whether the abuse is occurring at second-level domain, subdomain, web content, or email layer. 

## 9.4 Decision

Possible outcomes:

- no action / insufficient evidence; 
- request more evidence from complainant; 
- notify registrant or reseller for remediation; 
- clientHold; 
- transfer lock in conjunction with mitigation where appropriate; 
- referral to registry, host, law enforcement, payment provider, or other relevant party; 
- maintain existing hold; 
- deny reactivation. 

## 9.5 Notifications

For clear, actionable, ongoing DNS Abuse, NiceNIC may suspend first and notify after action.

For likely compromise scenarios or non-DNS matters, NiceNIC may notify first where that is consistent with risk control and does not materially increase harm.

This distinction is consistent with ICANN's position that mitigation may vary depending on the harm and the risk of collateral damage.

## 10. Category-Specific Rules

## 10.1 Drugs / kra / slon / mega Keywords

Keyword presence alone is not enough for DNS-Abuse classification.

Treat as:

- non-DNS illegal activity review if only keywords or product content are present; 
- DNS Abuse / urgent abuse if the evidence shows fake login, fake payment collection, credential theft, malicious redirection, malware, or other qualifying technical abuse. 

## 10.2 Crypto Scam

Treat as:

- non-DNS fraud review where the site is only a dubious investment or false-profit promotion; 
- DNS Abuse / urgent abuse where the evidence shows wallet connection theft, seed phrase collection, private key theft, drainer code, impersonated exchange login, or malicious scripts. 

## 10.3 CSAM / Child Exploitation

Treat as immediate high-risk abuse. Escalate internally without delay. Preserve records, avoid unnecessary customer back-and-forth, and escalate to the appropriate authority or registry if required.

## 10.4 DMCA / Copyright

Do not auto-suspend purely on large content lists or unsupported bulk allegations.

Forward proper notices where appropriate, require a compliant notice format, and allow the domain holder to address the claim unless a court order, registry rule, or other stronger basis requires more immediate action.

This is also broadly consistent with how major registrars separate copyright/trademark processing from phishing/malware handling.

## 10.5 Trademark / Brand Complaints

Trademark disputes are not automatically DNS Abuse.

Where the issue is a domain-name rights dispute, complainants should generally be directed toward UDRP, URS, or court process as appropriate, unless the evidence also shows phishing, impersonation, or other abuse. Namecheap publicly distinguishes abuse handling from UDRP/URS handling in the same way.

## 11. Registrant / Reseller Communication Rules

## 11.1 Retail Customers

For clear DNS Abuse with sufficient evidence:

- domain may be suspended immediately; 
- the first customer-facing reply should state the basis, the self-service path to view the case summary, and the evidence standard required for reconsideration. 

## 11.2 Resellers

NiceNIC may choose to notify the reseller rather than any downstream sub-user.

However, reseller status does not delay urgent mitigation where actionable evidence exists.

## 11.3 Reconsideration / Reactivation

NiceNIC will not lift a hold based on unsupported denials such as "content removed" or "it was already deleted" alone.

Reconsideration requires new, verifiable evidence such as:

- false-positive proof; 
- evidence of compromise and remediation; 
- clean current review results; 
- third-party reputation recovery where applicable. 

If reliable third-party security sources still show the domain as actively risky, NiceNIC may keep the hold in place pending further validation.

## 12. Complainant Communication Rules

NiceNIC should always send:

- acknowledgment of receipt; 
- case ID or equivalent reference; 
- request for more evidence if needed; 
- status update when action is taken or declined; 
- no unnecessary substantive discussion where the domain is already suspended or pending suspension and the key outcome is final. 

This reflects common registrar practice. GoDaddy offers formal claim submission and status checking, while Tucows explicitly states it responds with a case number and tracks category, date, and resolution internally.

## 13. Trusted Reporter Program

NiceNIC may maintain a trusted-reporter list for sources that consistently provide accurate, well-formed, and actionable reports.

Trusted-reporter status may provide:

- priority intake; 
- structured data submission; 
- simplified evidence formatting; 
- API or fast-lane handling. 

Trusted status does not eliminate independent review. Namecheap publicly operates this kind of trusted-provider phishing API model.

## 14. Recordkeeping and Audit Readiness

NiceNIC must document:

- complaint receipt; 
- evidence received; 
- internal classification; 
- investigation steps; 
- decision; 
- action taken; 
- notifications sent; 
- follow-up and final disposition. 

Records should be retained for the shorter of two years or the longest period allowed by applicable law, and be available for ICANN upon reasonable notice.

## 15. Compliance Controls

NiceNIC should perform:

- periodic QA review of case decisions; 
- staff training on DNS Abuse definitions and evidence thresholds; 
- testing of abuse mailbox and webform operability; 
- review of template accuracy; 
- monitoring of repeat errors and reopened cases; 
- monthly review of domains with repeated complaints. 

This is practical and important because ICANN has already reported remediation plans tied to broken abuse contacts, weak intake confirmations, and insufficient staff knowledge, and has noted that repeated failures can trigger expedited compliance action.

## 16. Metrics

NiceNIC should track at least:

- total complaints received; 
- DNS Abuse vs non-DNS abuse split; 
- sufficient vs insufficient evidence rate; 
- time to first acknowledgment; 
- time to first human review; 
- time to mitigation for actionable DNS Abuse; 
- number of holds issued; 
- number of reconsiderations granted or denied; 
- repeat-abuse domains; 
- repeat-abuse accounts; 
- trusted-reporter accuracy rate; 
- complaints already resolved before manual review. 

## 17. External-Facing Positioning

NiceNIC should describe its abuse system publicly in language like this:

- NiceNIC investigates abuse reports promptly. 
- NiceNIC distinguishes between ICANN-defined DNS Abuse and other types of complaints. 
- NiceNIC acts based on evidence, risk, and applicable policy. 
- NiceNIC may suspend immediately where there is clear actionable evidence of ongoing DNS Abuse. 
- NiceNIC may request more information or direct the complainant to a more appropriate action point where the registrar is not the sole effective responder. 
- NiceNIC keeps case records and can demonstrate its handling process if reviewed by ICANN or registry partners.

Originally published on NiceNIC: https://nicenic.com/support/NiceNIC-Abuse-Handling-Manual-4734
