## Engineering processes using secure design principles


### Objectives:

At the end of this episode, I will be able to:

Understand and apply the recommended guidance pertinent to applying engineering
processes using secure design principles through your daily practice as an
information security professional.


### External Resources:

Research, Implement and manage engineering processes using secure design principles

» Threat modeling
» Least privilege
» Defense in depth
» Secure defaults
» Fail securely
» Separation of Duties (SoD)
» Keep it simple
» Zero Trust
» Privacy by design
» Trust but verify
» Shared responsibility

================================================================================

It's VOCABULARY TIME !!!!

	What is Threat Modeling?

A process by which potential threats, such as structural vulnerabilities can be
identified, enumerated, and prioritized – all from a hypothetical attacker’s point of view.

The purpose of threat modeling is to provide defenders with a systematic analysis
of the probable attacker’s profile, the most likely attack vectors, and the
assets most desired by an attacker.

The threat risk modeling process has five steps:

	1. Identify Security Objectives
	2. Survey the Application / system
	3. Decompose it
	4. Identify Threats
	5. Identify Vulnerabilities


Threat modeling methodologies:

	STRIDE Methodology
	DREAD Methodology

Risk_DREAD = (DAMAGE + REPRODUCIBILITY + EXPLOITABILITY + AFFECTED USERS + DISCOVERABILITY) / 5

	P.A.S.T.A. - Process for Attack Simulation and Threat Analysis (PASTA)
	Trike
	VAST - Visual, Agile, and Simple Threat modeling


What is Least Privilege?

	Level of access (permissions) required to execute job


What is Defense in Depth?

	The use of overlapping layers of controls / countermeasures to create a series
  of defensive layers of physical / technical / administrative types to secure assets


What are Secure defaults?

	One or more settings that when enabled singly, or jointly make a system
  secured to the defined/required baseline. These settings may be implemented/managed
  by a vendor on behalf of a customer, or by the system administrator. These vary
  widely, and are vendor specific.

	The Secure Controls Framework:  https://www.securecontrolsframework.com/secure-by-default


What is Failing securely?

	This typically involves several things:

    Secure defaults (default is to deny access)

    On failure undo changes and restore to a secure state; always check return
    values for failure

    In conditional code/filters make sure that there is a default case that does
    the right thing

    The confidentiality and integrity of a system should remain even though
    availability has been lost

    Attackers must not be permitted to gain access to privileged objects that are
    normally inaccessible


What is Separation of Duties (SoD)?

	Prevent one person from having ALL the power


What is Keep it simple?

	DO NOT MAKE THINGS MORE COMPLICATED THAN NECESSARY !!!


What is Zero Trust (ZT)?

	The term for an evolving set of cybersecurity paradigms that move defenses from
  static, network- based perimeters to focus on users, assets, and resources.

	Zero trust assumes there is no implicit trust granted to assets or user accounts
  based solely on their physical or network location (i.e., local area networks
  versus the internet) or based on asset ownership (enterprise or personally
  owned).

	Authentication and authorization (both subject and device) are discrete
  functions performed before a session to an enterprise resource is established.

	Zero trust focus on protecting resources (assets, services, workflows, network
  accounts, etc.), not network segments, as the network location is no longer
  seen as the prime component to the security posture of the resource.


	NIST Special Publication 800-207: Zero Trust Architecture


What is Privacy by design?

	A framework based on proactively embedding privacy into the design and
  operation of IT systems, networked infrastructure, and business practices, with
  the goal of establishing the strongest protection of privacy.

	Based on adherence with the 7 Foundational Principles of Privacy by Design:

	1. Proactive not reactive (preventative not remedial) - Anticipate, identify,
  and prevent invasive events before they happen; this means taking action before
  the fact, not afterward.

	2. Privacy as the default setting - Ensure personal data is automatically
  protected in all IT systems or business practices, with no added action
  required by any individual.

	3. Embed privacy into design - Privacy measures should not be add-ons, but
  fully integrated components of the system.

	4. Retain full functionality (positive-sum, not zero-sum) - Privacy by Design
  employs a “win-win” approach to all legitimate system design goals; that is,
  both privacy and security are important, and no unnecessary trade-offs need to
  be made to achieve both.

	5. Ensure end-to-end security - Data lifecycle security means all data should
  be securely retained as needed and destroyed when no longer needed.

	6. Maintain visibility and transparency - Assure stakeholders that business
  practices and technologies are operating according to objectives and subject
  to independent verification.

	7. Respect user privacy - Keep things user-centric; individual privacy interests
  must be supported by strong privacy defaults, appropriate notice, and
  user-friendly options.


What is Trust but verify?

	EXACTLY THAT !!!


What is Shared responsibility?

	Cloud service providers adhere to a shared security responsibility model, which
  means your security team maintains some responsibilities for security as you
  move applications, data, containers, and workloads to the cloud, while the
  provider takes some responsibility, but not all. Defining the line between your
  responsibilities and those of your providers is imperative for reducing the
  risk of introducing vulnerabilities into your public, hybrid, and multi-cloud
  environments.

	In the AWS Shared Security model, AWS claims responsibility for “protecting the
  hardware, software, networking, and facilities that run AWS Cloud services.”

	Microsoft Azure claims security ownership of “physical hosts, networks, and
  data centers.”

Both AWS and Azure state that your retained security responsibilities depend upon
which services you select.


CSPs’ Common Security Responsibilities:

	 Physical security of the infrastructure, including but not limited to: equipment
  room location selection; power supply assurance; cooling facilities; protection
  against fire, water, shock, and theft; and surveillance
	 Security of computing, storage, and network hardware
	 Security of basic networks, such as anti-distributed denial of service and firewalls
	 Cloud storage security, such as backup and recovery
	 Security of cloud infrastructure virtualization, such as tenant resource
  isolation and virtualization resource management
	 Tenant identity management and access control
	 Secure access to cloud resources by tenant
	 Security management, operating monitoring, and emergency response of infrastructure
	 Formulating and rehearsing service continuity assurance plans and disaster
  recovery plans for infrastructure


Cloud Customers’ Common Security Responsibilities:

	 User identity management and access control of service systems
	 Data security (in the European General Data Protection Regulation (GDPR) mode,
  cloud customers control the data and should be responsible for data security
  while CSPs only process the data and should take security responsibilities
  granted by data controllers.)
	 Security management and control of terminals that access cloud services,
  including hardware, software, application systems, and device rights


General Concepts to be aware of:

	a. Subjects (users) & Objects (data)

	b. Closed (vendor specific) & Open Systems (industry standard)

	c. Confinement (sandboxing) - ability to control read / write activity as
  software executes in a system and accesses memory

	d. Bounds - limits set on the memory addresses and resources a process can
  access in a system

	e. Isolation - the ability to use bounds and confinement to control the impact
  process behavior has on a system

	f. Controls (in the context of access) - use of access rules to limit
  subject / object interaction

	g. Trusted System - one where all protection mechanisms work together to
  process sensitive data for many types of users while maintaining a stable,
  secure environment

	h. Assurance - the degree of confidence or certainty in a system's ability to
  satisfy the defined security requirements
