# Universal Indicators for Software Maturity (Draft) 

## Introduction
This document presents a draft of universal indicators for assessing software maturity. 
Each indicator is categorized under a **pillar** and described with three levels of maturity: **LOW, MED, and HIGH**.

## Indicators
### **Pillar 1: Governance**
| Indicator | Description | LOW | MED | HIGH |
|-----------|------------|-----|--------|------|
| **Governance** | Transparent governance of the product, including ownership and decision-making for new features/product roadmap. For open-source products, articulated and implemented community governance​ | There is no community governance structure in place to direct continued development of the digital tool | Some informal processes for community management exist to direct continued development of the digital tool | Formal community structures (e.g. leadership, technical advisory group, community representatives) exist and are practiced with documented roles and responsibilities in a transparent fashion and are used to direct continued development of the digital tool |

### **Pillar 2: Data Protection and Security**
| Indicator | Description | LOW | MED | HIGH |
|-----------|------------|-----|--------|------|
| **Secure development and deployment** | Documented security policy, security assessments, security measures, timelines, and vulnerability testing. Software development lifecycle and release processes based on secure practices. | Security by design and privacy by design and by default principles are taken into consideration but not systematically applied. Security scans are occasionally performed. | Security by design and privacy by design and by default principles are taken into consideration and systematically applied. Manual security scans are also systematically performed. | Security by design and privacy by design and by default principles are taken into consideration and systematically applied. Automatic security scans (dynamic and static) are also systematically performed as part of the development processes. All developers and testers follow a secure coding checklist. |
| **Regulatory data compliance** | Compliance support of the product with relevant data regulations such as GDPR | The product owner acknowledges some aspects of data regulations and does not prevent the implementer from adopting certain compliant practices. However, a comprehensive analysis of the applicable data regulations has not been performed, and its compliance support is basic. | All data protection and privacy regulations applicable to the product have been analyzed for the target market. The product includes measures to facilitate and uphold compliance by the implementer, but it does not routinely monitor for updates or changes in regulations. | The product has a robust compliance framework, including a complete analysis of all applicable data protection and privacy regulations for the target market. It actively supports the implementer in maintaining compliance and systematically tracks updates to requirements or regulations to ensure ongoing conformity. |
| **Security controls** | Security controls that are supported to protect data at rest and in transit, which include access controls, encryption, security architecture, libraries, and physical access, if applicable. | No security controls or implementation guidance are in place. | Role-based authorization exists if appropriate. Guidance on encrypting all remote access (web interface, APIs) is available to implementors. | Role-based authorization exists if appropriate. All remote access (web interface, APIs) are encrypted by default using current best practices. An independent security audit of the software has taken place within the last twelve months. |

### **Pillar 3: Open Standards**
| Indicator | Description | LOW | MED | HIGH |
|-----------|------------|-----|--------|------|
| **Openness, interoperability, and data standards** | Use of open standards and modular design. Data can be easily exported from the system. | Extracting or importing data into the system usually requires looking at the source code and/or directly accessing the database. | Some APIs are available to access and manage data. There are user-facing interfaces to export core data and metadata in the system (e.g., in CSV format) for further analysis and data transfer purposes. | A robust API is available for key data and metadata exchange needs for the primary business domain, with functional requirements for the API having been developed in conjunction with appropriate country, regional, and global stakeholders. API endpoints exist for core data and metadata elements that adhere to standards developed by an appropriate Standards Development Organization relevant to the tool's business domain. Standards-based API endpoints are used in at least four jurisdictions (e.g., countries or states). |

### **Pillar 4: Product Strategy and Roadmap**
| Indicator | Description | LOW | MED | HIGH |
|-----------|------------|-----|--------|------|
| **Product strategy and roadmap** | Availability of a clearly articulated and public roadmap for the product. The prioritization process of new features and timelines involves the community in a structured manner and is based on the target impact of the product. | No software roadmap exists or there is no publicly accessible and routinely maintained platform for new feature requests. | There is a publicly accessible and routinely maintained platform for new feature requests. A software roadmap exists describing currently planned and resourced development activities. | New features and functionality are documented as part of a software roadmap as part of a release cycle. There are forums for community members to discuss new feature requests. A clear prioritization process exists and is utilized for the development of new features and functionality as part of a product backlog. |

### **Pillar 5: Source Code Accessibility**
| Indicator | Description | LOW | MED | HIGH |
|-----------|------------|-----|--------|------|
| **Developer documentation, code structure, and readability** | The Extent to which the product is developer-friendly so that a technical person unfamiliar with the product can contribute. This includes the extent to which the source code is organized and documented and the extent to which other developer-focused documents ease the onboarding process. | Source code not publicly available or not released under an open-source license. | Source code exists on a publicly accessible repository and is licensed under an Open Source Initiative-approved license. | Source code exists on a publicly accessible repository and is licensed under an Open Source Initiative-approved license. The software is structured to allow local customizations and new modules and functionality without requiring the forking of the main code. |

### **Pillar 6: Total Cost of Ownership**
| Indicator | Description | LOW | MED | HIGH |
|-----------|------------|-----|--------|------|
| **Total cost of ownership (TCO)** | Calculations/information on TCO, for example, based on active deployments. The total cost of ownership covers the cost of operating the product over its lifespan, including initial deployments, training, customizations, etc. | Some information on costs is provided but does not cover all aspects of ownership. | High-level budgeting guidance for the tool is available and based on active deployments. | Detailed budget guidance is available covering, for example, cost estimates for a pilot (including capacity building, infrastructure, human resources), annual maintenance, and calculations for end-user capacity building. |

### **Pillar 7: Composability (Suggestion)**
| Indicator | Description | LOW | MED | HIGH |
|-----------|------------|-----|--------|------|
| **Flexible architecture** | The Extent to which the solution's architecture fosters modularity, flexibility, and adaptability. By embracing standardization and interoperability, composability fosters creating and reusing scalable building blocks. This approach drives agility and cost efficiency, empowering teams to respond swiftly to evolving challenges. |The solution's architecture is closer to a monolith than a modular and extensible set of components. Local customizations require forking or direct modification of the main codebase. |A base level of modularity exists and the architecture permits some plug-and-play flexibility.  | Solution has been designed with composability from the start.  Architecture is composed of modern, flexible, and independent microservices.| 


## How to Contribute
