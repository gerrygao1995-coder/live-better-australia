# 38. Websites, apps and online projects

Build something maintainable, useful and clear about its responsibilities. These checks also help volunteer groups running a small online service.

[All chapters](../README.md#the-full-playbook) · [Start here](../START-HERE.md) · [How to use the evidence labels](../EDITORIAL-POLICY.md)

- [Start with one task a visitor can complete](#au-0667)
- [Keep the domain under accountable ownership](#au-0668)
- [Collect only data you need](#au-0669)
- [Explain the service and its limits plainly](#au-0670)
- [Show the real price before checkout](#au-0671)
- [Make the remedy process easy to find](#au-0672)
- [Test the unsubscribe journey yourself](#au-0673)
- [Use a payment flow you can operate safely](#au-0674)
- [Give collaborators only the access needed](#au-0675)
- [Keep secrets out of a public repository](#au-0676)
- [Prove you can restore the project](#au-0677)
- [Test keyboard and small-screen access](#au-0678)
- [Get written scope before security testing](#au-0679)
- [Check dependencies and licences before release](#au-0680)
- [Plan moderation before inviting public submissions](#au-0681)
- [Create a useful problem-report form](#au-0682)
- [Set spending alerts and a service limit](#au-0683)
- [Plan an orderly closure](#au-0684)

---

<a id="au-0667"></a>

## AU-0667 · Start with one task a visitor can complete

Write the main thing the service should help someone do and test that journey with a real person. Remove optional features that obscure it. A modest useful service is easier to maintain than a broad unfinished one.

| At a glance | Details |
| --- | --- |
| Cost / effort | A prototype and feedback time. |
| Potential value | A clearer first release. |
| Applies to | Websites, apps and community tools. |
| Basis | Practical suggestion |
| Editorial review | 2026-10-09 |

*Editorial suggestion; no external evidence claim is made.*

---

<a id="au-0668"></a>

## AU-0668 · Keep the domain under accountable ownership

Record who owns the domain, billing account and hosting. Use an address and authorised backup arrangement that can survive a contractor or volunteer leaving. Keep renewal reminders where the responsible person will see them.

| At a glance | Details |
| --- | --- |
| Cost / effort | Registration fees and administration. |
| Potential value | Less risk of losing the service through an ownership gap. |
| Applies to | Online projects and small organisations. |
| Basis | Practical suggestion |
| Editorial review | 2026-10-09 |

*Editorial suggestion; no external evidence claim is made.*

---

<a id="au-0669"></a>

## AU-0669 · Collect only data you need

For every form field, state what it is for and how long you need it. Remove fields without a defensible purpose. Check applicable privacy obligations before collecting personal information.

| At a glance | Details |
| --- | --- |
| Cost / effort | Design and review time. |
| Potential value | Less unnecessary information to protect. |
| Applies to | Forms, bookings and accounts. |
| Basis | Official / professional guidance |
| Editorial review | 2026-10-09 |

**Read the source:** [OAIC — Small business privacy obligations](https://www.oaic.gov.au/privacy/privacy-guidance-for-organisations-and-government-agencies/organisations/small-business)

---

<a id="au-0670"></a>

## AU-0670 · Explain the service and its limits plainly

Tell visitors who operates it, what it does, what it costs and how to get help. If a tool offers suggestions, make the limits visible at the decision point. Avoid claiming qualifications or guarantees the project does not have.

| At a glance | Details |
| --- | --- |
| Cost / effort | Clear copy and review. |
| Potential value | Users can make a more informed choice. |
| Applies to | Public digital services. |
| Basis | Practical suggestion |
| Editorial review | 2026-10-09 |

*Editorial suggestion; no external evidence claim is made.*

---

<a id="au-0671"></a>

## AU-0671 · Show the real price before checkout

Review the complete consumer price display, including unavoidable or preselected fees and taxes. Check the ACCC’s current guidance for the situation. Do not rely on a late checkout surprise to make the advertised price look cheaper.

| At a glance | Details |
| --- | --- |
| Cost / effort | A pricing and checkout review. |
| Potential value | Clearer purchases and fewer avoidable disputes. |
| Applies to | Consumer-facing sales. |
| Basis | Official rule |
| Editorial review | 2026-10-09 |

**Read the source:** [ACCC — Price displays](https://www.accc.gov.au/business/pricing/price-displays)

---

<a id="au-0672"></a>

## AU-0672 · Make the remedy process easy to find

Publish a contact route and a process for problems with products or services. Ensure the wording preserves Australian Consumer Law rights. A blanket no-refunds statement is not a substitute for understanding consumer guarantees.

| At a glance | Details |
| --- | --- |
| Cost / effort | Support planning and legal review if needed. |
| Potential value | A workable process when a sale goes wrong. |
| Applies to | Businesses selling to Australian consumers. |
| Basis | Official rule |
| Editorial review | 2026-10-09 |

**Read the source:** [ACCC — Small business rights and responsibilities](https://www.accc.gov.au/business/small-business/small-business-toolkit/rights-and-responsibilities-of-your-small-business/small-business-rights-and-responsibilities)

---

<a id="au-0673"></a>

## AU-0673 · Test the unsubscribe journey yourself

Send a test marketing message to your own account and complete the unsubscribe process. Confirm suppression works before the next campaign. Keep the process aligned with ACMA’s consent and unsubscribe requirements.

| At a glance | Details |
| --- | --- |
| Cost / effort | A short end-to-end check. |
| Potential value | A consent process that works in practice. |
| Applies to | Email and SMS marketing. |
| Basis | Official rule |
| Editorial review | 2026-10-09 |

**Read the source:** [ACMA — Avoid sending spam](https://www.acma.gov.au/avoid-sending-spam)

---

<a id="au-0674"></a>

## AU-0674 · Use a payment flow you can operate safely

Before accepting payments, understand the provider’s fees, disputes, refunds and access controls. Avoid collecting payment details yourself without the required expertise and compliance arrangements. Test a permitted low-risk flow before launch.

| At a glance | Details |
| --- | --- |
| Cost / effort | Provider fees and setup work. |
| Potential value | A clearer operational responsibility. |
| Applies to | Projects taking payments. |
| Basis | Practical suggestion |
| Editorial review | 2026-10-09 |

*Editorial suggestion; no external evidence claim is made.*

---

<a id="au-0675"></a>

## AU-0675 · Give collaborators only the access needed

Use separate authorised accounts and limit permissions by role. Keep a process for removing access when someone leaves. Check that a backup administrator can recover the service through the provider’s legitimate process.

| At a glance | Details |
| --- | --- |
| Cost / effort | Initial access setup. |
| Potential value | Less reliance on shared credentials. |
| Applies to | Teams and volunteer projects. |
| Basis | Practical suggestion |
| Editorial review | 2026-10-09 |

*Editorial suggestion; no external evidence claim is made.*

---

<a id="au-0676"></a>

## AU-0676 · Keep secrets out of a public repository

Before publishing, inspect files for access tokens, passwords, private keys and personal records. Use an appropriate secret store for deployed services. If a real secret was exposed, revoke or rotate it; deleting a visible line alone is insufficient.

| At a glance | Details |
| --- | --- |
| Cost / effort | A pre-publication review. |
| Potential value | Lower risk of publishing live access. |
| Applies to | Open-source and hosted projects. |
| Basis | Practical suggestion |
| Editorial review | 2026-10-09 |

*Editorial suggestion; no external evidence claim is made.*

---

<a id="au-0677"></a>

## AU-0677 · Prove you can restore the project

Back up the content and configuration needed to rebuild. Try restoring a copy in a safe environment and document the missing steps. Include who is authorised to access any protected data.

| At a glance | Details |
| --- | --- |
| Cost / effort | Backup storage and a rehearsal. |
| Potential value | A recovery plan based on a real attempt. |
| Applies to | Services others rely on. |
| Basis | Practical suggestion |
| Editorial review | 2026-10-09 |

*Editorial suggestion; no external evidence claim is made.*

---

<a id="au-0678"></a>

## AU-0678 · Test keyboard and small-screen access

Check the main journey without a mouse and on a small screen. Use readable contrast, descriptive labels and meaningful link text. Ask users about barriers and prioritise fixes to essential tasks.

| At a glance | Details |
| --- | --- |
| Cost / effort | A focused usability review. |
| Potential value | More people can use the service. |
| Applies to | Public websites and apps. |
| Basis | Practical suggestion |
| Editorial review | 2026-10-09 |

*Editorial suggestion; no external evidence claim is made.*

---

<a id="au-0679"></a>

## AU-0679 · Get written scope before security testing

Before testing a system you do not own, obtain authorisation that defines targets, methods and limits. Stay within that scope and use the agreed reporting route. Stop when the activity goes beyond what was authorised.

| At a glance | Details |
| --- | --- |
| Cost / effort | Written agreement and careful scoping. |
| Potential value | A clearer boundary for technical work. |
| Applies to | Security researchers and contractors. |
| Basis | Practical suggestion |
| Editorial review | 2026-10-09 |

*Editorial suggestion; no external evidence claim is made.*

---

<a id="au-0680"></a>

## AU-0680 · Check dependencies and licences before release

List the software and assets the project uses. Check their licences, support status and source. Preserve required notices and make a plan for updates rather than treating the first working build as finished.

| At a glance | Details |
| --- | --- |
| Cost / effort | A dependency review. |
| Potential value | A project you can maintain and share responsibly. |
| Applies to | Software and digital publishing. |
| Basis | Practical suggestion |
| Editorial review | 2026-10-09 |

**Read the source:** [business.gov.au — Intellectual property](https://business.gov.au/planning/protect-your-brand-idea-or-creation/intellectual-property)

---

<a id="au-0681"></a>

## AU-0681 · Plan moderation before inviting public submissions

Decide what content is allowed, how users report a problem and who can respond. Consider the people likely to use the service and the foreseeable harms. Use eSafety’s Safety by Design resources as a starting point.

| At a glance | Details |
| --- | --- |
| Cost / effort | Ongoing moderation capacity. |
| Potential value | A clearer response when harmful content appears. |
| Applies to | Communities, marketplaces and user-generated content. |
| Basis | Official / professional guidance |
| Editorial review | 2026-10-09 |

**Read the source:** [eSafety — Safety by Design](https://www.esafety.gov.au/industry/safety-by-design/faq)

---

<a id="au-0682"></a>

## AU-0682 · Create a useful problem-report form

Ask for the minimum information needed to reproduce an issue and a contact route if a reply is necessary. Tell users not to send passwords or unrelated personal information. Separate urgent safety reports from routine suggestions.

| At a glance | Details |
| --- | --- |
| Cost / effort | Form design and triage time. |
| Potential value | Reports are easier to handle appropriately. |
| Applies to | Services accepting feedback. |
| Basis | Practical suggestion |
| Editorial review | 2026-10-09 |

*Editorial suggestion; no external evidence claim is made.*

---

<a id="au-0683"></a>

## AU-0683 · Set spending alerts and a service limit

Check hosting and API billing, quotas and what happens when a limit is reached. Choose a graceful failure mode for a small project. Review usage after launch instead of assuming a free tier stays sufficient.

| At a glance | Details |
| --- | --- |
| Cost / effort | Monitoring setup and possible hosting costs. |
| Potential value | Earlier notice of unexpected bills. |
| Applies to | Metered online services. |
| Basis | Practical suggestion |
| Editorial review | 2026-10-09 |

*Editorial suggestion; no external evidence claim is made.*

---

<a id="au-0684"></a>

## AU-0684 · Plan an orderly closure

Keep a process for notifying users, exporting eligible data, settling outstanding commitments and removing data lawfully when a service closes. Check retention obligations before deletion. Do not let a forgotten project continue charging people.

| At a glance | Details |
| --- | --- |
| Cost / effort | Closure planning. |
| Potential value | A more responsible end to a project. |
| Applies to | Subscriptions and ongoing digital services. |
| Basis | Practical suggestion |
| Editorial review | 2026-10-09 |

*Editorial suggestion; no external evidence claim is made.*

---

[← Working and studying overseas](37-overseas-work-study.md) · [Relationships, community and recreation →](39-relationships-community.md)
