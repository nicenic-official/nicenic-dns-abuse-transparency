# Domain Abuse Report Triage Playbook

Use this playbook when a project receives a report about a suspicious page, message, download, or redirect involving one of its domains. The aim is to assign an owner, preserve relevant observations, and verify the response.

Project maintainers can adapt the following workflow to their team and reporting channels.

## 1. Handle sensitive evidence privately

Provide a private channel for evidence containing credentials, personal information, or exploit details. Keep sensitive material out of public issue threads, and preserve a reference to the report in the appropriate incident record. A private evidence channel protects people and systems; it does not require removing legitimate public feedback or a reasonable public discussion of the concern.

Record the original report, receipt time, affected service, and the owner of the next action. Acknowledge receipt without treating the allegation as already confirmed.

## 2. Capture the reported behavior

Ask for the domain, exact URL or hostname, observation time with time zone, and a short description of what happened. Screenshots and original messages may be useful. Request additional material only when it helps answer a specific question.

Do not require a reporter to interact with a suspected phishing form, run an attachment, or expose a secret to demonstrate the issue.

## 3. Separate the observation from the assessment

For example:

- Observation: the reported page displays a copied account sign-in form.
- Assessment: possible phishing; the destination and behavior require review.
- Next action: assign an authorized investigator to examine the reported location safely.

Keep the initial observation even if the assessment changes. A report can involve more than one issue, such as brand impersonation and credential theft.

For relevant gTLD cases, ICANN’s DNS Abuse definition can inform the assessment. It does not replace investigation of other reported security or abuse concerns.

## 4. Contact the party that can make the change

An application maintainer can remove an affected route. A hosting operator can help contain a compromised environment. A registrar can investigate the domain's involvement and take relevant domain-level measures. Some incidents need several parties working at once.

State what each party is being asked to investigate. Record the handoff, acknowledgement, and follow-up owner so that the case retains its context.

## 5. Record containment and recovery separately

Removing a malicious page may interrupt the current attack. Recovery can also require patching software, securing administrative access, and checking for persistence. Preserve relevant evidence while taking urgent steps to limit harm.

Use distinct entries for the action, its time, and the observation used to verify it. Record uncertainty if the reported behavior cannot be reproduced.

## Closure checklist

- The affected locations were reviewed through an authorized process.
- The record explains what was found and what remains uncertain.
- The response and its observed result are documented.
- Any continuing work has an owner and a review time.
- The reporter received an appropriate update without private operational data.

Keep enough context for another maintainer to understand the response and reopen the investigation if related evidence emerges.
