## Data security controls & compliance requirements


### Objectives:

At the end of this episode, I will be able to:

Understand and apply the recommended guidance pertinent to how to align data
security controls & compliance requirements through your daily practice as an
information security professional.


### External Resources:

Determine data security controls and compliance requirements

1. Data states (e.g., in use, in transit, at rest)
2. Scoping and tailoring
3. Standards selection
4. Data protection methods (e.g., Digital Rights Management (DRM), Data Loss Prevention (DLP), Cloud Access Security Broker (CASB))

=====================================================

 1. Understand data states

	Baseline - establishes a minimum set of safeguards that can be standardized,
	documented, implemented, monitored and maintained

	Data exists in 3 well defined states:

	a. at rest (storage)
	b. in motion (transit / on the wire)
	c. in use (application)


Link vs End-to-End encryption:

	Link encryption encrypts all the data along a specific communication path, as
	in a satellite link, T3 line, or telephone circuit. Not only is the user
	information encrypted, but the header, trailers, addresses, and routing data
	that are part of the packets are also encrypted. The only traffic not encrypted
	is the data link control messaging information, which includes instructions
	and parameters that the different link devices use to synchronize communication
	methods. Link encryption provides protection against packet sniffers and
	eavesdroppers.


	In end-to-end encryption, only the data or payload is encrypted. Metadata like
	headers, addresses, etc. are unencrypted and remain visible.


 2. Scoping and tailoring

	Scoping provides an enterprise with specific terms and conditions on the
	applicability and implementation of individual security controls

	Tailoring is how organizations interpret what they need to do to protect
	information based on scoping

	Supplementation involves adding assessment procedures or assessment details to
	adequately meet the risk management needs of the organization


 3. Standards selection - One size ? (hybrid)

	NIST - http://csrc.nist.gov/index.html

	National Checklist Program Repository (NCP) - defined by SP 800-70, is the U.S.
	government repository of publicly available security checklists (or benchmarks)
	that provide detailed low level guidance on setting the security configuration
	of operating systems and applications

	https://nvd.nist.gov/ncp/repository


	European Union (EU) Digital Cybersecurity Package -
https://ec.europa.eu/digital-single-market/en/policies/cybersecurity


	European Union Agency for Network & Information Security (ENISA) -
http://www.enisa.europa.eu


	International Organization for Standardization (ISO) -
https://www.iso.org/home.html


	 International Telecommunication Union-Telecommunication (ITU-T) Standardization -
	 https://www.itu.int/en/ITU-T/Pages/default.aspx


	Recommendations X.800 – X.849: The X.800 series of ITU-T Recommendations
	defines a security baseline against which network operators can assess their
	network and information security status in terms of readiness and ability to
	collaborate with other entities to counteract information security threats.

http://www.itu.int/rec/T-REC-X/e


	Recommendation X.1205: provides a definition for cybersecurity and taxonomy of
	security threats from an organization point of view.

www.itu.int/rec/T-REC-X.1205-200804-I/en


	NATO Cooperative Cyber Defence Centre of Excellence - www.ccdcoe.org/index.html


	Center for Internet Security (CIS) Controls - https://www.cisecurity.org/controls/

	3 categories:
	a. Basic (1-6)
	b. Foundational (7-16)
	c. Organizational (17-20)

NIST Security Content Automation Protocol (SCAP) -
https://csrc.nist.gov/Projects/Security-Content-Automation-Protocol

SCAP is a multi-purpose framework of specifications that supports automated
configuration, vulnerability and patch checking, technical control compliance
activities, and security measurement.


  4. Data protection methods (e.g., Digital Rights Management (DRM), Data Loss
	Prevention (DLP), Cloud Access Security Broker (CASB))


	Digital Rights Management (DRM) - the processes by which the author or
	publisher of a work exerts their rights to control what the purchaser of the
	work is entitled to do.

DRM represents the controls by which you can prevent someone from copying or
printing or editing or otherwise making available your privileged information to
other people.

Such controls include:

	Preventing editing and saving
	Preventing forwarding and sharing
	Preventing printing (or limiting the number of prints available)
	Preventing screen grabbing
	Document expiry
	Document revocation
	Locking documents to devices, IP addresses, and country locations
	Watermarking documents with unique user information to establish an identity



	Data Loss Prevention (DLP) - Enables businesses to detect data loss, as well as
	prevent the illicit transfer of data outside the organization and the unwanted
	destruction of sensitive or personally identifiable data (PII).

It is also used to help organizations with data security and ensure they comply
with regulations like the California Consumer Privacy Act (CCPA), EU General Data
Protection Regulation (GDPR), and Health Insurance Portability and
Accountability Act (HIPAA).


NOTE: The terms "data loss" and "data leakage prevention" are often used
interchangeably, but DLP security enables organizations to defend themselves
against both.


DLP allows businesses to:

	Identify sensitive information across multiple on-premises & cloud-based systems
	Prevent the accidental sharing of data
	Monitor and protect data
	Educate users on how to stay compliant




	Cloud Access Security Broker (CASB) - Cloud-hosted or on-premises software or
	hardware that act as an intermediary between users and cloud service providers.

The ability of a CASB to address gaps in security extends across
software-as-a-service (SaaS), platform-as-a-service (PaaS), and
infrastructure-as-a-service (IaaS) environments.

In addition to providing visibility, a CASB also allows organizations to extend
the reach of their security policies from their existing on-premises infrastructure
to the cloud and create new policies for cloud-specific context.

The CASB serves as a policy enforcement center, consolidating multiple types of
security policy enforcement and applying them to everything your business utilizes
in the cloud—regardless of what sort of device is attempting to access it,
including unmanaged smartphones, IoT devices, or personal laptops.


	a. at rest (storage) -
		encryption
		obfuscation / tokenization
		archive / dispose / destruct
		mobile device protection
		physical media control

	b. in motion (transit) -
		encryption
		perimeter security
		web content filtering
		network traffic monitoring
		VPN's

	c. in use (application) -
		encryption
		user monitoring
		workstation restrictions
		application controls (whitelist / blacklist)
		data labeling
