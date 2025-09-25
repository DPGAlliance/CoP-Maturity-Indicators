# Maturity Assessment Questionnaire
This document provides a comprehensive self-assessment framework for open-source project owners, maintainers, and Open Source Program Offices (OSPOs) to gain a deep, evidence-based understanding of their project's maturity.

### How to Use This Questionnaire

This questionnaire is designed as a reflective tool to evaluate the project's current, demonstrable state. For each indicator across the seven pillars, the assessment involves a three-step process:

1. **Select the Maturity Level:** Choose the overall maturity level (LOW, MED, or HIGH) that most accurately describes the project's current practices for that indicator.
2. **Select Detailed Practices:** From the checklist provided under the chosen maturity level, select all applicable practices that justify the selection. This provides the specific evidence for the assessment.
3. **Provide Context and Evidence:** Use the free-form text box to add crucial context, links to public evidence (e.g., governance documents, security policies, public roadmaps), or explain any unique circumstances that influence the project's approach.


## Pillar 1: Governance

This pillar assesses the transparency, structure, and effectiveness of the project's decision-making processes and community management. Mature governance fosters trust, encourages broad contribution, and ensures the long-term strategic viability of the project.

### 1.1: Governance
> [!IMPORTANT]
>
>Transparent governance of the product, including ownership and decision-making for new features/product roadmap. For open-source products, articulated and implemented governance​.

**1. Select Your Project's Level:**
- ![LOW](https://img.shields.io/badge/LOW-red) - There is no governance structure in place to direct continued development of the digital tool.
- ![LOW](https://img.shields.io/badge/MED-yellow) - Some informal processes for community management exist to direct continued development of the digital tool.
- ![LOW](https://img.shields.io/badge/HIGH-green) - Formal governance structures exist and are practiced with documented roles and responsibilities transparently, and are used to direct continued development of the digital tool.

**2. Select the Practices That Apply to Your Project:**

- [ ] There is no governance structure in place.
- [ ] We have some informal processes for community management and development.
- [ ] We have formal community structures (e.g., a technical advisory group, community representatives).
- [ ] Roles and responsibilities within our governance structure are documented and transparent.
- [ ] Our governance body actively directs the continued development of the solution.

**3. Additional Details on Governance:**
Please provide any other relevant details, such as links to governance documents or descriptions of your decision-making process.

> [!TIP]
>
>Think about how someone new would understand who runs the project. Is there a `GOVERNANCE.md` file in your repository? Are decisions announced publicly, and is there a clear way for community members to contribute to the product roadmap?

## Pillar 2: Data Protection and Security

This pillar evaluates the project's commitment to building secure software and respecting data privacy regulations. This includes both the project's internal development processes and the security features it provides to end-users.

### 2.1: Secure Development and Deployment
> [!IMPORTANT]
>
>Documented security policy, security assessments, security measures, timelines, and vulnerability testing. Software development lifecycle and release processes based on secure practices.

**1. Select Your Project's Level:**
- ![LOW](https://img.shields.io/badge/LOW-red) - Security by design and privacy by design and by default principles are taken into consideration, but not systematically applied. Security scans are occasionally performed.
- ![LOW](https://img.shields.io/badge/MED-yellow) - Security by design and privacy by design and by default principles are taken into consideration and systematically applied. Manual security scans are also systematically performed.
- ![LOW](https://img.shields.io/badge/HIGH-green) - Security by design and privacy by design and by default principles are taken into consideration and systematically applied. Automatic security scans (dynamic and static) are also systematically performed as part of the development processes. All developers and testers follow a secure coding checklist.

**2. Select the Practices That Apply to Your Project:**

- [ ] Security and privacy by design are considered but not applied systematically.
- [ ] We occasionally perform security scans.
- [ ] Security and privacy by design are systematically applied.
- [ ] We systematically perform manual security scans.
- [ ] We use automatic static and dynamic security scans as part of our CI/CD pipeline.
- [ ] All developers and testers follow a secure coding checklist. 

**3. Additional Details on Secure Development:**

> [!TIP]
>
>This is about making security a core part of your process, not an afterthought. Do you use tools like Dependabot or Snyk? Do you have a documented security policy for developers?

### 2.2: Regulatory Data Compliance

> [!IMPORTANT]
>
>Compliance support of the product with relevant data regulations such as GDPR.

**1. Select Your Project's Level:**
- ![LOW](https://img.shields.io/badge/LOW-red) - The product owner acknowledges some aspects of data regulations and does not prevent the implementer from adopting certain compliant practices. However, a comprehensive analysis of the applicable data regulations has not been performed, and its compliance support is basic.
- ![LOW](https://img.shields.io/badge/MED-yellow) - All data protection and privacy regulations applicable to the product have been analyzed for the target market. The product includes measures to facilitate and uphold compliance by the implementer, but it does not routinely monitor for updates or changes in regulations.
- ![LOW](https://img.shields.io/badge/HIGH-green) - The product has a robust compliance framework, including a complete analysis of all applicable data protection and privacy regulations for the target market. It actively supports the implementer in maintaining compliance and systematically tracks updates to requirements or regulations to ensure ongoing conformity.

**2. Select the Practices That Apply to Your Project:**

- [ ] We acknowledge some aspects of data regulations, but haven't performed a comprehensive analysis.
- [ ] We have analyzed all applicable data protection regulations for our target market.
- [ ] The product includes features that help implementers comply with regulations.
- [ ] We do not routinely monitor for changes in regulations.
- [ ] We have a robust compliance framework and systematically track updates to regulations to ensure the product stays compliant.

**3. Additional Details on Regulatory Data Compliance:**

> [!TIP]
>
>If your software handles personal data, this is crucial. Think about whether your software helps an organization that uses it to be, for example, GDPR or CCPA compliant. Does it have features for data deletion, export, or consent management?


### 2.3: Security Controls

> [!IMPORTANT]
>
>Security controls that are supported to protect data at rest and in transit, which include access controls, encryption, security architecture, libraries, and physical access, if applicable.

**1. Select Your Project's Level:**
- ![LOW](https://img.shields.io/badge/LOW-red) - No security controls or implementation guidance are in place.
- ![LOW](https://img.shields.io/badge/MED-yellow) - All data protection and privacy regulations applicable to the product have been analyzed for the target market. The product includes measures to facilitate and uphold compliance by the implementer, but it does not routinely monitor for updates or changes in regulations.Role-based authorization exists if appropriate. Guidance on encrypting all remote access (web interface, APIs) is available to implementors.
- ![LOW](https://img.shields.io/badge/HIGH-green) - Role-based authorization exists if appropriate. All remote access (web interface, APIs) are encrypted by default using current best practices. An independent security audit of the software has taken place within the last twelve months.

**2. Select the Practices That Apply to Your Project:**

- [ ] No specific security controls or implementation guidance are provided.
- [ ] Role-based authorization is implemented.
- [ ] Guidance on encrypting remote access (web, APIs) is available.
- [ ] All remote access is encrypted by default using current best practices.
- [ ] An independent security audit of the software has been completed within the last 12 months.

**3. Additional Details on Security Controls:**

> [!TIP]
>
>This refers to built-in features. For example, does your software enforce HTTPS? Does it manage user permissions based on roles (e.g., admin, editor, viewer)?

## Pillar 3: Open Standards

This pillar assesses the project's use of open standards and modular design to promote interoperability and prevent vendor lock-in.

### 3.1: Openness, Interoperability, and Data Standards

> [!IMPORTANT]
>
>Use of open standards and modular design. Data can be easily exported from the system.

**1. Select Your Project's Level:**
- ![LOW](https://img.shields.io/badge/LOW-red) - Extracting or importing data into the system usually requires looking at the source code and/or directly accessing the database.
- ![LOW](https://img.shields.io/badge/MED-yellow) - Some APIs are available to access and manage data. There are user-facing interfaces to export core data and metadata in the system (e.g., in CSV format) for further analysis and data transfer purposes.
- ![LOW](https://img.shields.io/badge/HIGH-green) - A robust API is available for key data and metadata exchange needs for the primary business domain, with functional requirements for the API having been developed in conjunction with appropriate country, regional, and global stakeholders. API endpoints exist for core data and metadata elements that adhere to standards developed by an appropriate Standards Development Organization relevant to the tool's business domain. Standards-based API endpoints are used in at least four jurisdictions (e.g., countries or states).

**2. Select the Practices That Apply to Your Project:**

- [ ] It requires looking at the source code or accessing the database directly.
- [ ] Some APIs are available to access and manage data.
- [ ] There are user interfaces for exporting core data (e.g., as a CSV file).
- [ ] A robust, well-documented API is available for key data exchange.
- [ ] Our API endpoints adhere to standards from a relevant Standards Development Organization (e.g., HL7 for healthcare, IETF for internet protocols).
- [ ] Our standards-based API is used in at least four different jurisdictions (e.g., countries or states).

**3. Additional Details on Interoperability:**

> [!TIP]
>
>Think about how your project "plays" with other software. Can another application easily pull data from your tool via an API? Is that API documented with something like Swagger or OpenAPI?

## Pillar 4: Product Strategy and Roadmap

This pillar evaluates the clarity and transparency of the project's future direction and the process for prioritizing new features.

### 4.1: Product Strategy and Roadmap

> [!IMPORTANT]
>
>Availability of a clearly articulated and public roadmap for the product. The prioritization process of new features and timelines involves the community in a structured manner and is based on the target impact of the product.

**1. Select Your Project's Level:**
- ![LOW](https://img.shields.io/badge/LOW-red) - No software roadmap exists, or there is no publicly accessible and routinely maintained platform for new feature requests.
- ![LOW](https://img.shields.io/badge/MED-yellow) - There is a publicly accessible and routinely maintained platform for new feature requests. A software roadmap exists describing currently planned and resourced development activities.
- ![LOW](https://img.shields.io/badge/HIGH-green) - New features and functionality are documented as part of a software roadmap as part of a release cycle. There are forums for community members to discuss new feature requests. A clear prioritization process exists and is utilized for the development of new features and functionality as part of a product backlog.

**2. Select the Practices That Apply to Your Project:**

- [ ] No software roadmap exists.
- [ ] There is no publicly accessible platform for new feature requests.
- [ ] We have a publicly accessible platform (e.g., GitHub Issues, Jira) for new feature requests.
- [ ] A software roadmap exists that describes planned development.
- [ ] We have forums (e.g., Discord, Discourse) for community members to discuss feature requests.
- [ ] We have a clear, documented process for prioritizing new features for the product backlog.

**3. Additional Details on Your Roadmap:**

> [!TIP]
>
>A good roadmap communicates the "why" behind your work and where the project is headed. You can use tools like GitHub Projects or a simple `ROADMAP.md` file in your repository.


## Pillar 5: Source Code Accessibility
This pillar assesses not only whether the source code is available, but how easy it is for a new developer to understand, contribute to, and extend the project. This is critical for building a vibrant contributor community.

### 5.1: Developer Documentation, Code Structure, and Readability

> [!IMPORTANT]
>
> The Extent to which the product is developer-friendly so that a technical person unfamiliar with the product can contribute. This includes the extent to which the source code is organized and documented and the extent to which other developer-focused documents ease the onboarding process.

**1. Select Your Project's Level:**
- ![LOW](https://img.shields.io/badge/LOW-red) - Source code not publicly available or not released under an open-source license.
- ![LOW](https://img.shields.io/badge/MED-yellow) - Source code exists on a publicly accessible repository and is licensed under an Open Source Initiative-approved license.
- ![LOW](https://img.shields.io/badge/HIGH-green) - Source code exists on a publicly accessible repository and is licensed under an Open Source Initiative-approved license. The software is structured to allow local customizations and new modules and functionality without requiring the forking of the main code.

**2. Select the Practices That Apply to Your Project:**

- [ ] A README.md file exists with a basic project description and installation instructions.
- [ ] A CONTRIBUTING.md file exists with basic guidelines for submitting issues and pull requests.
- [ ] The software is architected with a modular, plugin, or extension system that allows for adding new functionality without modifying or forking the core codebase.
- [ ] Comprehensive developer documentation is provided.
- [ ] The codebase is well-commented and follows a consistent, documented coding style enforced by a linter.

**3. Additional Details on Your Roadmap:**

> [!TIP]
>
>The highest level of maturity in source code accessibility is defined not by the license, but by the architecture. A project that is merely licensed as open source allows others to see and modify the code. However, a project with an extensible, modular architecture makes a deliberate and significant investment in its future ecosystem. 
