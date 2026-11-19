# Preserving observations in a phishing report

A phishing report may reach a reviewer after the reported page has changed. Keep the original observation and later checks as separate entries so the case record remains useful to the next reviewer.

Suggested fields for a handoff

- Destination URL, with session secrets removed from shared copies.
- Date, time and time zone of the original observation.
- A short description of the action requested from the visitor.
- Source of the observation and a redacted capture, where available.
- Subsequent review, with its own timestamp and result.

Example: a researcher captures a sign-in prompt at 09:40 UTC. The same URL returns an error when an analyst checks at 10:05 UTC. Preserve both entries. If a report lists several domains, record which observation applies to each one.

ChainPatrol contributes evidence about suspected phishing and impersonation. NiceNIC reviews reports concerning the domains it sponsors and determines the appropriate response. This note illustrates a possible report structure. It describes no public API, required schema or automatic enforcement rule.

[NiceNIC’s account](https://nicenic.com/news/How-ChainPatrol-and-NiceNIC-Are-Strengthening-Evidence-Based-DNS-Abuse-Mitigation-42647) · [ChainPatrol’s account](https://chainpatrol.com/blog/chainpatrol-nicenic-evidence-based-dns-abuse-mitigation)
