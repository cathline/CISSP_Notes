## Threat modeling concepts and methodologies


### Objectives:

At the end of this episode, I will be able to:

Understand and apply the recommended guidance for threat modeling concepts and
methodologies through your daily practice as an information security professional.


### External Resources:

Understand and apply threat modeling concepts and methodologies

What is Threat Modeling? - a process by which potential threats, such as
structural vulnerabilities can be identified, enumerated, and prioritized – all
from a hypothetical attacker’s point of view.

The purpose of threat modeling is to provide defenders with a systematic analysis
of the probable attacker’s profile, the most likely attack vectors, and the assets
most desired by an attacker.

The threat risk modeling process has five steps:
	1. Identify Security Objectives
	2. Survey the Application / system
	3. Decompose it
	4. Identify Threats
	5. Identify Vulnerabilities


1. Threat modeling methodologies-

What are the most well known models:

STRIDE Methodology - characterizing known threats according to the kinds of
exploit that are used (or motivation of the attacker).


DREAD Methodology - quantifying, comparing and prioritizing the amount of risk
presented by each evaluated threat. The DREAD algorithm, shown below, is used to
compute a risk value, which is an average of all five categories.

Risk_DREAD = (DAMAGE + REPRODUCIBILITY + EXPLOITABILITY + AFFECTED USERS + DISCOVERABILITY) / 5

The calculation always produces a number between 0 and 10; the higher the number,
the more serious the risk.


P.A.S.T.A. - Process for Attack Simulation and Threat Analysis (PASTA). A seven-step
process for aligning business objectives and technical requirements, taking into
account compliance issues and business analysis. Provides a dynamic threat
identification, enumeration, and scoring process. Once the threat model is
completed security subject matter experts develop a detailed analysis of the
identified threats. Finally, appropriate security controls can be enumerated.

Provides an attacker-centric view of the application and infrastructure from which
defenders can develop an asset-centric mitigation strategy.


Trike - Threat models are used to satisfy the security auditing process. Threat
models are based on a “requirements model.” The requirements model establishes the
stakeholder-defined “acceptable” level of risk assigned to each asset class.
Analysis of the requirements model yields a threat model form which threats are
enumerated and assigned risk values. The completed threat model is used to
construct a risk model based on asset, roles, actions, and calculated risk exposure.

VAST - Visual, Agile, and Simple Threat modeling. Focuses on the necessity of
scaling the threat modeling process across the infrastructure and entire SDLC, and
integrating it seamlessly into an Agile software development methodology. The
methodology seeks to provide actionable outputs for the unique needs of various
stakeholders: application architects and developers, cybersecurity personnel, and
senior executives.

AS/NZS 4360:2004 Risk Management - the world’s first formal standard for
documenting and managing risk.

The five steps of the AS/NZS 4360 process are:

1. Establish Context: Establish the risk domain, i.e., which assets/systems are
important?

2. Identify the Risks: Within the risk domain, what specific risks are apparent?

3. Analyze the Risks: Look at the risks and determine if there are any supporting
controls in place.

4. Evaluate the Risks: Determine the residual risk.

5. Treat the Risks: Describe the method to treat the risks so that risks selected
by the business will be mitigated.

Note: AS/NZS 4360 assumes that risk will be managed by an operational risk group,
and that the organization has adequate skills and risk management resources in
house to identify, analyze, and treat the risks.

CVSS - The US Department of Homeland Security (DHS) established the NIAC
Vulnerability Disclosure Working Group, which incorporates input from Cisco
Systems, Symantec, ISS, Qualys, Microsoft, CERT/CC, and eBay.


2. Threat modeling concepts -

Visual Representations based on Data Flow Diagrams (PASTA | TRIKE)

Visual Representations based on Process Flow Diagrams (VAST)
