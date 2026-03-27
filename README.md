# NIST SP 800-37 Rev. 2: Risk Management Framework (RMF) Compliance Checklist

A comprehensive, actionable checklist and implementation guide for NIST Special Publication 800-37 Revision 2, "Risk Management Framework for Information Systems and Organizations: A System Life Cycle Approach for Security and Privacy." This resource is designed for federal agencies, defense contractors, and any organization that must achieve an Authorization to Operate (ATO) or maintain continuous authorization under the Risk Management Framework.

**Full compliance guide:** [https://petronellatech.com/compliance/nist-800-37-rmf/](https://petronellatech.com/compliance/nist-800-37-rmf/)

**Last Reviewed: March 2026**

---

## What Is NIST SP 800-37?

NIST SP 800-37 Rev. 2, published by the National Institute of Standards and Technology, defines the Risk Management Framework (RMF), a structured process for integrating security, privacy, and cyber supply chain risk management activities into the system development life cycle. Originally released in 2010 and significantly revised in December 2018, the RMF provides a disciplined, repeatable methodology for selecting, implementing, assessing, and monitoring security controls for federal information systems and organizations.

The RMF is the authoritative process by which federal agencies, Department of Defense (DoD) components, and government contractors achieve authorization to operate their information systems. Every federal system that processes, stores, or transmits government data must complete the RMF process before receiving an ATO from an Authorizing Official (AO). The framework applies equally to cloud environments, on-premise systems, industrial control systems, and hybrid architectures.

NIST SP 800-37 Rev. 2 introduced several critical updates to the original framework. It added a new "Prepare" step as the first phase of the RMF, emphasizing the importance of organization-level and system-level preparation before diving into control selection. It also integrated privacy risk management alongside security risk management throughout the entire lifecycle, aligning with the growing regulatory emphasis on privacy protection. The revision further emphasized the connection between the RMF and the NIST Cybersecurity Framework (CSF), making it easier for organizations to align their risk management activities across both publications.

The source document is available at [https://csrc.nist.gov/publications/detail/sp/800-37/rev-2/final](https://csrc.nist.gov/publications/detail/sp/800-37/rev-2/final).

## Relationship to NIST SP 800-53

NIST SP 800-37 and NIST SP 800-53 are companion publications that work together as the backbone of federal cybersecurity. While SP 800-53 Rev. 5 provides the master catalog of over 1,000 security and privacy controls organized into 20 control families, SP 800-37 provides the process framework for selecting, implementing, assessing, authorizing, and monitoring those controls within a specific system context.

Think of it this way: SP 800-53 answers the question "What controls exist?" while SP 800-37 answers "How do I apply those controls to my system and prove they work?" The RMF's Select step directly references SP 800-53 control baselines (defined in SP 800-53B) and requires organizations to tailor those baselines to their specific system categorization. The Assess step uses procedures defined in NIST SP 800-53A to evaluate whether controls are implemented correctly, operating as intended, and producing the desired outcome.

The RMF also connects to numerous other NIST publications. SP 800-60 guides system categorization (FIPS 199/200), SP 800-30 supports risk assessment activities, and SP 800-137 addresses the continuous monitoring phase. Together, these publications form an integrated risk management ecosystem.

## The Seven Steps of the Risk Management Framework

### Step 1: Prepare

The Prepare step, introduced in Rev. 2, establishes the context and priorities for managing security and privacy risk at both the organization level and the system level. This is the foundation upon which all subsequent RMF activities rest.

**Organization-Level Preparation:**
- Assign key risk management roles (Chief Information Officer, Senior Agency Information Security Officer, Authorizing Official, System Owner, Information System Security Officer)
- Establish a risk management strategy aligned with organizational mission and business objectives
- Conduct organization-wide risk assessments per NIST SP 800-30
- Define control baselines and organizational common controls
- Develop and maintain an organization-wide strategy for continuous monitoring
- Identify and prioritize stakeholder assets requiring protection

**System-Level Preparation:**
- Identify the system and document it within the system inventory
- Determine the authorization boundary for the system
- Identify stakeholders who have an interest in the system
- Identify assets that require protection (data, services, infrastructure)
- Conduct an initial system-level risk assessment
- Determine the system's information types per NIST SP 800-60

### Step 2: Categorize

System categorization determines the impact level (Low, Moderate, or High) for the information system based on the potential impact of a security breach on confidentiality, integrity, and availability. The categorization drives all subsequent control selection decisions.

- Identify the information types processed, stored, and transmitted by the system using NIST SP 800-60 Vol. 2
- Determine the security impact level for each information type across confidentiality, integrity, and availability (FIPS 199)
- Apply the high-water mark methodology to establish the overall system categorization
- Document the categorization decision in the System Security Plan (SSP)
- Obtain Authorizing Official approval of the categorization
- Register the system in the organization's system inventory with the approved categorization

### Step 3: Select

The Select step involves choosing, tailoring, and documenting the security and privacy controls for the system based on its categorization.

- Identify the initial control baseline from NIST SP 800-53B based on system categorization (Low, Moderate, or High)
- Tailor the baseline controls by applying scoping guidance, compensating controls, and organization-defined parameters
- Identify and allocate common controls provided by the organization or inherited from other systems
- Document system-specific, hybrid, and common controls in the System Security Plan
- Develop a continuous monitoring strategy specific to the system
- Review and approve the security and privacy plans

### Step 4: Implement

The Implement step puts the selected controls into operation within the system and its environment.

- Implement the security and privacy controls specified in the SSP
- Document the control implementation details in the SSP, including how each control is implemented, the mechanisms used, and the responsible parties
- Ensure implementation is consistent with the organization's architecture and engineering requirements
- Update the SSP with the actual implementation details for each control
- Document any planned deviations from the baseline in the Plan of Action and Milestones (POA&M)

### Step 5: Assess

The Assess step determines whether the controls are implemented correctly, operating as intended, and producing the desired outcome with respect to meeting the security and privacy requirements.

- Develop a Security Assessment Plan (SAP) defining the assessment procedures, scope, and schedule
- Select or engage qualified assessors (internal or third-party) per NIST SP 800-53A
- Conduct the security and privacy control assessment using appropriate methods (examine, interview, test)
- Document assessment findings in the Security Assessment Report (SAR)
- Identify deficiencies and create or update the POA&M for each finding
- Provide the assessment results to the Authorizing Official

### Step 6: Authorize

The Authorize step is the formal decision by the Authorizing Official to accept the risk associated with operating the system.

- Assemble the authorization package: SSP, SAR, and POA&M
- Conduct a risk determination based on the assessment results and any residual risks
- Present the authorization package to the Authorizing Official for review
- The Authorizing Official issues an Authorization to Operate (ATO), Denial of Authorization to Operate (DATO), or Interim Authorization to Test (IATT)
- Document the authorization decision, including any terms and conditions
- Communicate the authorization decision to relevant stakeholders

### Step 7: Monitor

The Monitor step maintains ongoing situational awareness of the security and privacy posture of the system and the organization.

- Monitor the system and its environment for changes that affect the security and privacy posture
- Conduct ongoing assessments of control effectiveness per the continuous monitoring strategy
- Analyze and respond to the output of continuous monitoring activities
- Report the security and privacy posture to the Authorizing Official and other stakeholders
- Review and update the SSP, SAR, and POA&M on an ongoing basis
- Conduct ongoing authorization activities to maintain the ATO

## Key RMF Artifacts

The RMF process produces several critical documents that form the authorization package:

| Artifact | Purpose | RMF Step |
|---|---|---|
| System Security Plan (SSP) | Documents system description, boundary, controls, and implementation details | Categorize through Monitor |
| Security Assessment Plan (SAP) | Defines assessment scope, procedures, methodology, and schedule | Assess |
| Security Assessment Report (SAR) | Records assessment findings, deficiencies, and recommendations | Assess |
| Plan of Action and Milestones (POA&M) | Tracks identified deficiencies and remediation timelines | Assess through Monitor |
| Authorization Decision Letter | Formal ATO, DATO, or IATT from the Authorizing Official | Authorize |
| Continuous Monitoring Strategy | Defines ongoing monitoring activities, frequency, and reporting | Select through Monitor |
| Risk Assessment Report | Documents identified risks, likelihood, impact, and risk responses | Prepare through Monitor |

## RMF Roles and Responsibilities

| Role | Primary Responsibility |
|---|---|
| Authorizing Official (AO) | Accepts risk and grants ATO |
| Chief Information Officer (CIO) | Oversees IT governance and risk management |
| Senior Agency Information Security Officer (SAISO) | Manages organization-wide security program |
| System Owner | Responsible for system operation and security |
| Information System Security Officer (ISSO) | Day-to-day security operations for the system |
| Security Control Assessor (SCA) | Conducts independent control assessments |
| Common Control Provider | Manages controls inherited by multiple systems |

## Common RMF Challenges and How to Address Them

**Challenge: Authorization boundary definition.** Many organizations struggle to define clear system boundaries, leading to scope creep and overlapping authorizations. Address this by using NIST SP 800-18 guidance and clearly documenting data flows, interconnections, and shared services during the Prepare step.

**Challenge: Inheriting common controls.** Organizations often fail to properly document and validate inherited common controls, creating gaps in their authorization packages. Establish a formal common control provider program with documented control inheritance agreements.

**Challenge: Continuous monitoring fatigue.** After achieving an initial ATO, teams often revert to a "set and forget" mentality. Implement automated continuous monitoring tools and establish clear triggers for reassessment, including changes to the threat landscape, system architecture, or operational environment.

**Challenge: POA&M management.** Plans of Action and Milestones frequently become stale documents rather than active remediation trackers. Integrate POA&M management into regular operational meetings and tie remediation milestones to resource allocation and budget planning.

## RMF vs. Other Frameworks

| Feature | RMF (800-37) | NIST CSF 2.0 | ISO 27001 | CMMC |
|---|---|---|---|---|
| Scope | Federal systems, contractors | All organizations (voluntary) | International (voluntary) | Defense industrial base |
| Control Source | SP 800-53 | References SP 800-53 | Annex A controls | SP 800-171/172 |
| Authorization | Formal ATO required | No formal authorization | Certification audit | Third-party assessment (L2+) |
| Continuous Monitoring | Required (Step 7) | Monitor function | Surveillance audits | Annual affirmation |
| Risk Approach | System-level categorization | Outcome-based tiers | Risk treatment plans | Practice maturity |
| Privacy Integration | Yes (Rev. 2) | Partial | Annex A.8 | Limited |

## How AI Changes the RMF Process

The traditional RMF process is notoriously document-heavy and labor-intensive. A single system authorization can require months of effort and hundreds of pages of documentation. AI-powered compliance tools are transforming how organizations execute the RMF by automating control mapping, generating SSP content from system configurations, continuously monitoring control effectiveness, and flagging deviations in real time.

Petronella Technology Group uses its private AI fleet, including on-premise large language models and custom GPU infrastructure, to accelerate every phase of the RMF. PTG's AI-powered compliance platform automates control inheritance mapping, generates assessment procedures, and monitors system configurations against SSP documentation continuously. This reduces the time to ATO from months to weeks while improving accuracy and reducing human error.

PTG's patented technology stack further differentiates its approach by automating what competitors do manually: control gap analysis, evidence collection, POA&M tracking, and continuous monitoring dashboards. Combined with PTG's licensed digital forensic expertise (Licensed Digital Forensic Examiner #604180), organizations get a complete lifecycle solution from initial authorization through incident investigation.

## Frequently Asked Questions

**Q: What is the difference between an ATO and an IATT?**
A: An Authorization to Operate (ATO) is a formal approval to operate a system in a production environment. An Interim Authorization to Test (IATT) is a temporary, limited authorization that allows an organization to test a system under specific conditions and for a defined period before seeking a full ATO. IATTs are commonly used for systems undergoing migration, major upgrades, or initial deployment where full assessment is not yet complete.

**Q: How long does the RMF process typically take?**
A: A traditional RMF process for a Moderate-impact system typically takes 6 to 18 months, depending on the system complexity, organizational maturity, and available resources. With AI-powered automation tools like those used by PTG, this timeline can be compressed to 8 to 12 weeks for well-prepared organizations.

**Q: Is the RMF only for federal agencies?**
A: While the RMF is mandatory for federal agencies under FISMA, it is also required for DoD contractors (via DFARS 252.204-7012), intelligence community systems, and any contractor system that processes federal data. Many private-sector organizations voluntarily adopt the RMF as a best-practice risk management methodology.

**Q: What is the relationship between FIPS 199, FIPS 200, and SP 800-37?**
A: FIPS 199 defines the methodology for categorizing information and systems. FIPS 200 establishes minimum security requirements for federal systems based on that categorization. SP 800-37 provides the process framework (the RMF) for applying those requirements through control selection, implementation, assessment, authorization, and monitoring.

**Q: How does the RMF relate to CMMC?**
A: CMMC Level 2 requires implementation of the 110 controls from NIST SP 800-171, which are themselves derived from the Moderate baseline of SP 800-53. The RMF process described in SP 800-37 is the authoritative methodology for implementing and assessing those controls. Organizations pursuing CMMC certification benefit from following the RMF's structured approach to control implementation and assessment.

**Q: What triggers a need for re-authorization?**
A: Significant changes to the system, its operating environment, or the threat landscape can trigger re-authorization. Examples include major architectural changes, migration to a new hosting environment, discovery of a critical vulnerability, changes to the system's authorization boundary, or changes in the types of information processed. The continuous monitoring strategy should define specific triggers.

**Q: Can multiple systems share a single ATO?**
A: While each system requires its own authorization decision, the RMF supports authorization of common controls that can be inherited by multiple systems. Additionally, type authorizations and facility authorizations can cover multiple instances of similar systems. The Authorizing Official determines the appropriate authorization scope.

**Q: What is reciprocity in the context of the RMF?**
A: Reciprocity refers to the practice of accepting an existing authorization from one organization or agency when making authorization decisions for the same system in a different context. While full reciprocity is the goal of policies like the Federal Risk and Authorization Management Program (FedRAMP), in practice, Authorizing Officials retain the right to request additional assessment evidence before accepting reciprocal authorizations.

## About the Author

This checklist was developed by **Craig Petronella**, founder and CEO of Petronella Technology Group, Inc. Craig brings over 23 years of cybersecurity experience and holds the following credentials:

- CMMC Registered Practitioner (RP)
- Licensed Digital Forensic Examiner #604180
- Cisco CCNA and CWNE certifications
- MIT Artificial Intelligence Certificate
- Amazon #1 Best-Selling Author of 14+ cybersecurity books

Craig has guided hundreds of organizations through the RMF process, from initial system categorization through continuous monitoring and re-authorization. His expertise spans federal agencies, defense contractors, healthcare organizations, and financial institutions.

## About Petronella Technology Group (PTG)

Petronella Technology Group, Inc. is a Raleigh, NC-based cybersecurity, compliance, and AI services firm that specializes in making enterprise-grade compliance accessible to small and mid-size businesses. PTG combines AI development (custom AI agents, private LLMs, GPU hosting) with deep cybersecurity and compliance expertise, a combination that no other firm in the Research Triangle offers.

**What sets PTG apart:**

- **AI-Powered Compliance:** PTG operates its own private AI fleet with on-premise large language models and custom GPU infrastructure to accelerate compliance assessments, automate control mapping, and continuously monitor security posture.
- **Patented Technology Stack:** PTG's proprietary, patented security and compliance tools automate what competitors do manually.
- **Licensed Digital Forensic Examiner:** When compliance fails and a breach occurs, PTG has the forensic expertise to investigate, preserve evidence, and support legal proceedings. Most compliance firms cannot do this.
- **Fleet Infrastructure:** PTG's on-premise AI infrastructure (GPU clusters, private cloud) proves PTG practices what it preaches about data sovereignty and private AI.

**Contact PTG:**

- **Phone:** 919-348-4912
- **Address:** 5540 Centerview Dr. Suite 200, Raleigh, NC 27606
- **Website:** [https://petronellatech.com](https://petronellatech.com)
- **Compliance Services:** [https://petronellatech.com/compliance/packages/](https://petronellatech.com/compliance/packages/)
- **RMF Guide:** [https://petronellatech.com/compliance/nist-800-37-rmf/](https://petronellatech.com/compliance/nist-800-37-rmf/)

**Ready to start your RMF journey?** Call 919-348-4912 or [schedule a free compliance assessment](https://petronellatech.com/compliance/packages/) to learn how PTG's AI-powered approach can cut your time to ATO in half.

## Related Resources

- [NIST SP 800-53 Compliance Guide](https://petronellatech.com/compliance/nist-800-53-compliance/)
- [NIST SP 800-171 Compliance Guide](https://petronellatech.com/compliance/nist-800-171-compliance/)
- [CMMC Compliance Guide](https://petronellatech.com/compliance/cmmc/)
- [DFARS Compliance Guide](https://petronellatech.com/compliance/more-compliance/dfars-compliance/)
- [PTG Cybersecurity Services](https://petronellatech.com/cybersecurity/)
- [PTG AI Services](https://petronellatech.com/ai/)
- [SPRS Calculator](https://petronellatech.com/tools/sprs-calculator/)

## License

This checklist is released under the MIT License. See [LICENSE](LICENSE) for details.
