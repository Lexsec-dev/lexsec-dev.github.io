---
title: "Peacetime Architecture: Why the ISMS Fails in a Geopolitical Threat Environment"
date: 2026-04-01
description: "An assessment of the governance gap between certification-grade ISMS implementations and the operational resilience the current threat environment demands."
categories: [Assessment]
tags: [ISO 27001, NIS2, ISMS, geopolitics, governance, critical infrastructure]
image:
  path: /assets/img/posts/peacetime-architecture.jpg
  alt: "Aerial view of a dam releasing water, water flowing downstream in Finland. Drone view. Credit: wmaster890 / iStock"
---

## Key Assessments

- The ISO 27001 risk assessment methodology does not model geopolitical targeting logic. Most implementations treat threats as technical and apolitical, an assumption invalidated by a threat environment in which targeting decisions follow foreign policy, not vulnerability scans.
- Rotational internal audit cycles are a peacetime construct. When threat profiles shift on geopolitical timelines (sanctions packages, trade realignments, alliance commitments), a three-year rotation cannot respond. Event-driven reassessment is not optional; it is a structural requirement the standard does not enforce.
- NIS2, in force in Germany since December 2025 with no transition period, exposes the gap between certification-grade ISMS implementations and the operational resilience the regulation demands. Management faces personal liability. Nearly 30,000 German organizations are now in scope.
- The World Economic Forum's 2026 Global Cybersecurity Outlook finds that only nineteen percent of organizations exceed minimum resilience requirements. The gap between resilient and insufficiently resilient organizations is a governance gap, not a technology gap.
- The operational model proposed in this assessment defines a trigger protocol, response timelines, and decision requirements that the standard permits but the market has not adopted.

---

The security of European infrastructure is no longer shaped primarily by criminal actors seeking profit. It is shaped by geopolitical positioning: by where an organization sits relative to active conflicts, trade alignments, and sanctions regimes. This shift invalidates the foundational assumption behind most Information Security Management Systems: that threats are slow-moving, apolitical, and predictable enough to assess on an annual cycle. The standard does not require organizations to fail at this. But it does not require them to succeed, and the result, across most implementations, is predictable.

In April 2025, in an incident formally attributed by Norway's Police Security Service to pro-Russian actors, hackers gained unauthorized access to the control systems of a dam facility at Lake Risevatnet in Bremanger and manipulated its water discharge. Water flowed undetected for four hours. The targeting was not opportunistic. Norway's support for Ukraine made its critical infrastructure a target in a hybrid conflict that does not distinguish between military and civilian systems.[^1]

Somewhere in the governance chain behind that facility, whether formalized as an ISMS or not, there was a risk register. An audit schedule. A set of assumptions about what threats looked like and how fast they moved. Those assumptions are now obsolete across European critical infrastructure, and no management system built on them can produce the outcomes the current threat environment demands.

## I. The Governance Gap

The World Economic Forum's 2026 Global Cybersecurity Outlook offers the clearest available dataset on the state of organizational cyber resilience. Of the 804 executives surveyed, only nineteen percent exceed minimum resilience requirements. Sixty-four percent meet the minimum. Seventeen percent fall below even that.[^2] The European data confirms the pattern: ENISA's 2025 Threat Landscape report analysed 4,875 incidents across the EU and found sustained, diversified pressure across multiple vectors simultaneously, not single high-impact events but campaigns that collectively erode resilience.[^3] The BSI's 2025 annual report is more direct: Germany remains "too easily attackable," with 119 new vulnerabilities documented per day during the reporting period, a twenty-four percent increase year over year.[^4]

The governance failure is visible in the divergence between executive and operational priorities. CEOs now rank cyber-enabled fraud as their primary concern. CISOs rank ransomware first, with supply chain disruption second.[^5] The ISMS management review under clause 9.3 is the mechanism designed to reconcile these views into a coherent risk posture. In most organizations, that reconciliation never happens. The management review produces a slide deck, not a decision.

Among highly resilient organizations, ninety-nine percent report board involvement in cybersecurity. Among insufficiently resilient organizations, thirteen percent report that the board is not engaged at all.[^6] These are self-reported figures and likely overstate actual governance engagement. But even with that bias, the gap between the top and bottom of the resilience spectrum is too wide to attribute to survey distortion alone. The gap is organizational, not technical. Among highly resilient organizations, thirty percent of board members hold personal liability for cybersecurity outcomes, compared to nine percent in insufficiently resilient organizations. Forty-four percent simulate cyber incidents with ecosystem partners, compared to sixteen percent.[^7] What separates the organizations that exceed resilience requirements is how their management system operates, not their security tooling.

An organization can hold a valid ISO 27001 certificate, pass its surveillance audit, maintain a current Statement of Applicability, and still operate with a risk register that has not been meaningfully updated since certification. The standard requires continual improvement. It does not enforce it. The auditor checks that the process exists. Whether the process produces accurate risk awareness is outside the audit scope.

## II. The Geopolitical Blind Spot

ISO 27001 clause 4.1 requires organizations to identify external issues relevant to their purpose that affect the intended outcome of the ISMS. Clause 6.1 requires that risk assessments consider these issues. In practice, most organizations interpret "external issues" as regulatory changes, technology shifts, or market conditions. Almost none interpret it as geopolitical positioning.

This is a design gap with operational consequences. A German manufacturer in the defense supply chain faces a completely different threat environment than a German manufacturer producing consumer electronics. Their IT architectures may be comparable. What differs is where their output sits in an alliance structure. The former is a target for Russian and Chinese intelligence collection. The latter, in most scenarios, is not. No field in a standard risk assessment template captures this distinction.

Ninety-one percent of the largest organizations surveyed by the World Economic Forum have changed their cybersecurity strategies due to geopolitical volatility.[^8] But the shift is happening above the ISMS, not through it. Strategy changes at the executive level (new threat briefings, revised vendor policies, accelerated investment) rarely translate into updated risk registers, revised Statements of Applicability, or event-driven management reviews. The result is a two-track system: executives responding to geopolitical reality in real time, and an ISMS still operating on the assumptions of the last certification audit.

Executives are aware. The issue is that their awareness never reaches the ISMS. The people making the decisions and the system designed to govern them are operating on different timelines, and the gap between those timelines is where exposure accumulates unrecorded.

ENISA's assessment confirms the convergence on the ground: state-aligned threat groups intensified long-term cyberespionage campaigns against EU telecommunications, logistics, and manufacturing sectors, while hacktivist operations, many aligned with nation-state agendas, accounted for nearly eighty percent of all recorded incidents by volume.[^9] The BSI reports that twenty-five percent of advanced persistent threat activity is directed specifically against Germany.[^10] The rotational audit cycle cannot absorb this. When Poland reported coordinated destructive cyberattacks against more than thirty wind and solar farms, a manufacturing company, and a combined heat and power plant serving nearly half a million customers on 29 December 2025, attacks attributed by CERT Polska to a Russian state-linked threat cluster and independently linked to Sandworm by multiple vendors, the relevant policy areas required immediate reassessment, not a scheduled review in eighteen months.[^11]

The supply chain dimension makes this acute. The World Economic Forum identifies inheritance risk (the inability to assure the integrity of third-party software, hardware, and services) as the top supply chain cyber risk in 2026, followed by lack of visibility into the extended supply chain.[^12] A third-party ransomware attack on a single check-in software provider disrupted operations at several major European airports in September 2025, including Heathrow, Brussels, and Berlin: a single vendor dependency cascading across an entire sector.[^13] When trade policy shifts reorder supply chains, cyber due diligence on new suppliers must happen at the speed of the realignment, not at the speed of the audit calendar. The rush to establish alternative suppliers, logistics channels, or data-hosting arrangements often outpaces that diligence, expanding the attack surface across less-secure networks and third parties.[^14]

## III. NIS2 as the Forcing Function

The security concepts in NIS2 are not new. ISO 27001 has recommended them for two decades. What NIS2 adds is consequences for their absence: enforcement, and personal liability.

On 6 December 2025, Germany's NIS2 implementation entered into force with no transition period. Nearly 30,000 German organizations across essential and important sectors are now in scope: any entity with more than 50 employees or more than EUR 10 million in annual turnover operating in designated sectors.[^15][^16] The pressure does not stop at EU borders. Switzerland, a non-member but economically inseparable from the EU and home to some of Europe's most critical financial and international infrastructure, now operates in a procurement environment where its trading partners are subject to NIS2. Compliance expectations flow through supply chains regardless of jurisdiction.

Early legal commentary suggests substantial overlap between ISO 27001 and NIS2 requirements, though no systematic regulatory mapping has been published.[^17] Where the peacetime ISMS fails is in the gap. NIS2 requires incident reporting within twenty-four hours of becoming aware of a significant event, not within the next audit cycle. It requires management to be directly accountable for cybersecurity measures. Members of the management body may be held personally liable for damages caused by culpable conduct. Fines reach EUR 10 million or two percent of annual turnover.[^18]

The scope problem is immediately consequential. Many organizations certified their ISMS around a narrow scope: a single department, a specific system, a defined business process. NIS2 does not recognize partial coverage. In Belgium, the Centre for Cybersecurity Belgium (CCB) requires that ISO 27001 certification cover "the relevant scope of application" for it to qualify as a conformity assessment route under the Belgian NIS2 transposition.[^19] Not every narrow-scope certification is a governance failure; some reflect genuine architectural segmentation. But NIS2 does not evaluate architectural intent. It evaluates whether the management body can demonstrate oversight across the entity's operations.

The failure mode is predictable. A ransomware incident enters through a subsidiary's unmonitored network segment, outside the certification boundary but inside the NIS2 scope. The board is asked what controls were in place. The answer is: none that we governed. The certificate covered something else. Under NIS2, that is a governance failure with personal consequences. The BSI's own 2025 assessment makes the scale of this exposure concrete: forty-eight percent of critical infrastructure operators in Germany had not met minimum maturity requirements for attack detection.[^20]

NIS2 does not require ISO 27001 certification. It requires the functional equivalent: systematic risk management, incident response capability, supply chain security, management accountability, and continual improvement. An organization can meet these requirements without a certificate. But a certificate that represents a documentation exercise rather than an operational governance system will not satisfy them.

## IV. An Operational Model for Event-Driven Governance

The preceding sections diagnose a management system operating at the wrong tempo. The standard permits the governance this environment demands: event-driven reassessment, living risk documentation, board-level engagement with operational security. What has been absent is a model for operationalizing it. What follows is derived from what the standard permits but the market has not adopted.

**Geopolitical trigger protocol.** The CISO or risk owner defines a shortlist of external events that mandate an out-of-cycle risk reassessment. The triggers, response thresholds, and timelines should be documented and approved by management as part of the ISMS governance framework:

![Geopolitical trigger protocol](/assets/img/posts/trigger-protocol-table.png)

**Versioned Statement of Applicability.** The SoA becomes a living document with a change log. Every modification (a control reclassified, a risk acceptance revised, a supplier control downgraded) is timestamped, justified, and traceable to the triggering event. Under NIS2, management must demonstrate that cybersecurity measures were implemented and overseen. A static SoA cannot satisfy this requirement. Versioning it with a decision trail can. Read this way, the SoA is a strategic decision register, not an audit artifact. Every control marked "not applicable" is a risk acceptance. Every control marked "applicable" is a resource allocation decision. Read together, it is a map of where the organization defends and where it accepts exposure.

**Supply chain risk as a standing agenda item.** Supply chain risk enters the management review quarterly, not annually. Organizations that assess supplier security maturity only at onboarding or renewal are operating blind between cycles. The management review should receive a quarterly update on supplier risk posture changes (new vendors, jurisdiction shifts, incident disclosures) and document the board's response. Among highly resilient organizations, seventy-four percent assess the security maturity of their suppliers. Among insufficiently resilient organizations, forty-eight percent do. Only twenty-seven percent of all organizations simulate cyber incidents with ecosystem partners.[^21]

**Decision-producing management reviews.** The output of each review should be a documented list of risk acceptances approved, risk treatments authorized, resource allocations changed, and escalations to the board. If the review produces no decisions, it has failed its purpose under clause 9.3 regardless of whether it occurred on schedule.

The risk of operating at this tempo is real. Trigger protocols that fire too broadly produce decision fatigue and dilute management attention. The shortlist must be short. The threshold for convening an out-of-cycle review must be high enough to preserve the signal: a regional conflict escalation, not a news headline. But the alternative, a management system that cannot respond to a sanctions package until the next scheduled review, is no longer a defensible governance posture.

The framework already exists. What is missing is the willingness to operate it at the tempo the threat environment demands.

The architecture is there. So is the urgency and the legal compulsion. The majority of organizations that have not exceeded minimum resilience thresholds are not lacking a framework. They are lacking the decision, and the resourcing, to operate the one they already have. NIS2 has made the cost of that inaction personal. The people who approved the budget now carry the liability.

Everything this article recommends is permitted by the standard. So is everything it diagnoses. That permissiveness is the structural condition that allowed an entire market to build governance systems for a threat environment that no longer exists. The decision to operate in peacetime mode was always available under the standard. It is no longer available under the threat landscape. And it is no longer available under the law.

---

[^1]: PST (Norwegian Police Security Service) Chief Beate Gangås, public attribution at Arendalsuka national policy forum, August 2025. Investigation by Kripos and NSM. Incident date: 7 April 2025, Lake Risevatnet dam, Bremanger municipality. Reported in VG, Aftenposten, Associated Press, Politico. Referenced in World Economic Forum, Global Cybersecurity Outlook 2026, Section 3.2.
[^2]: World Economic Forum, Global Cybersecurity Outlook 2026, January 2026, Figure 24. Published in collaboration with Accenture. Survey: 804 respondents across 92 countries.
[^3]: European Union Agency for Cybersecurity (ENISA), Threat Landscape 2025, October 2025. Analysis of 4,875 incidents, reporting period July 2024 – June 2025.
[^4]: Bundesamt für Sicherheit in der Informationstechnik (BSI), Die Lage der IT-Sicherheit in Deutschland 2025, November 2025. Reporting period July 2024 – June 2025.
[^5]: WEF GCO 2026, Table 1: Ranking of CEOs' and CISOs' cyber risk concerns, 2025 vs. 2026.
[^6]: WEF GCO 2026, Figure 32: Board engagement gaps across organizational resilience levels.
[^7]: WEF GCO 2026, Table 4: Hallmarks of cyber-resilient companies (Cyber Resilience Compass data).
[^8]: WEF GCO 2026, Figure 18: Strategy shifts due to geopolitical volatility among organizations with >100,000 employees.
[^9]: ENISA, Threat Landscape 2025: state-nexus cyberespionage campaigns against EU telecommunications, logistics, and manufacturing; hacktivist operations accounting for approximately 80% of recorded incidents by volume.
[^10]: BSI, Lagebericht 2025: 25% of APT activity directed against Germany, targeting government institutions, research facilities, and technology-oriented companies.
[^11]: CERT Polska, Energy Sector Incident Report, 29 December 2025, published 30 January 2026. Attribution to Static Tundra (FSB Center 16). Independent attribution to Sandworm/ELECTRUM by ESET (WeLiveSecurity, January 2026) and Dragos (ELECTRUM: CyberAttack on Poland's Electric System 2025, 28 January 2026). Polish PM Donald Tusk briefed government leaders 14 January 2026. Digital Affairs Minister Krzysztof Gawkowski stated the attack came "very close to a blackout." CISA amplified CERT Polska's findings in a February 2026 advisory to US critical infrastructure operators.
[^12]: WEF GCO 2026, Table 6: Ranking of top supply chain cyber risk.
[^13]: ENISA, Threat Landscape 2025: September 2025 cyberattack on Collins Aerospace MUSE check-in and boarding software disrupting operations at Heathrow, Brussels, Berlin, and other European airports.
[^14]: WEF GCO 2026, Section 3.2: Geopolitics is a defining feature of cybersecurity.
[^15]: Reed Smith LLP, "Germany Implements NIS2: Immediate Effect, Broad Scope, Near-Term Registration," January 2026.
[^16]: German NIS2 Implementation Act (NIS2UmsuCG), effective 6 December 2025. Entity thresholds per §28 BSIG.
[^17]: Reed Smith LLP, January 2026. Estimate based on legal commentary; no formal regulatory mapping published by BSI or ENISA at time of writing.
[^18]: German NIS2 Implementation Act, penalty provisions. Management liability per general principles of corporate law as specified in the Act.
[^19]: Centre for Cybersecurity Belgium (CCB), "The NIS2 Law," atwork.safeonweb.be/nis2. ISO 27001 certification must cover "the relevant scope of application" to qualify as a conformity assessment route under the Belgian NIS2 transposition (Law of 26 April 2024).
[^20]: BSI, Lagebericht 2025: 48% of critical infrastructure operators had not reached maturity level 3 for attack detection systems.
[^21]: WEF GCO 2026, Figure 38: How organizations address supply chain risk.
