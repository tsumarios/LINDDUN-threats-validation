# The SPADA Methodology for Privacy Threat Modelling

This folder contains the outcomes for the article "The SPADA Methodology for Privacy Threat Modelling"

It contains a comprehensive list of privacy threats organised into domain-independent and domain-dependent categories. The content is designed to facilitate privacy threat modelling and analysis in various domains, including smart cars and smart homes.

## Abstract

As individuals engage with innovative technologies, including smart cars and smart homes, a comprehensive treatment of the threats to their privacy becomes increasingly urgent. This article recognises the relevance of privacy threat modelling, especially under the umbrella of GDPR compliance, and addresses the challenge of the pursuit of completeness in eliciting privacy threats.
The core contribution is SPADA, a methodology for privacy threat modelling revolving around five key variables (whose initials form the acronym that names the methodology). These are: “Source of documentation”, “Property within privacy”, “Application domain”, “Detail (level of)” and “Agent(s) raising the threats”, and clarify the essential variable elements of the threat modelling activity.
SPADA requires the analyst to duly instantiate each variable but offers increased structure and automation in return.
The methodology is applied to the domains of smart cars and smart homes, considering both soft and hard privacy. This yields 23 domain-independent threats for soft privacy, and 29 domain-independent threats for hard privacy. Both these lists of threats are then tailored to the smart car domain by appropriate combination with the 43 identified assets, producing a total of 785 privacy threats for smart cars. Similarly, appropriate combination with the 127 assets identified in the smart home domain produces a total of 1502 privacy threats for smart homes.

## Prior to SPADA

*File: [pre-SPADA.xlsx](./pre-SPADA.xlsx)*

This file contains the list of threats gathered from the following document sources before applying the SPADA methodology: “ENISA TT” stands for the ENISA “Threat Taxonomy v2016” report, “ENISA SC” for the “Good practices for security of smart cars” report, “ENISA SH” for the “Threat Landscape and Good Practice Guide for Smart Home and Converged Media” report, “OWASP” for the “Calculation of the complete Privacy Risks list v2.0” document, with the remaining labels referring to the LINDDUN threat types.

## Domain-Independent Privacy Threats

*File: [privacy_threats.xlsx](./privacy_threats.xlsx)*

This file contains two tabs named "Soft Privacy" and "Hard Privacy". Each tab lists domain-independent privacy threats, along with the document source (S) for each threat.

For example, within the Soft Privacy tab, let us consider row 3: the threat "Unawareness as data subject" is retrieved from LINDDUN, in particular from the U(nawareness) threat type.

## Domain-Dependent Privacy Threats

Each domain-independent threat is instantiated appropriately, i.e., over each of the assets it affects, not necessarily all assets, ultimately producing a domain-dependent threat.

### Smart Cart

*[privacy_threats_smartcar.xlsx](./privacy_threats_smartcar.xlsx)*

This file contains three tabs named "Smart Car Assets", "Soft Privacy" and "Hard Privacy". The first tab includes the assets collected for the target domain (smart car), along with the document source (S) and category/group for each asset. The second and third tabs feature the domain-dependent threats for, respectively, soft and hard privacy, obtained by appropriate combinations with the target domain assets, along with the document source (S) for each threat.

For example, within the Soft Privacy tab, let us consider row 19: the threat "Failure to meet contractual requirements" sourced from ENISA can be associated with "All assets" (totalling 43 assets). Consequently, there are 43 instances of this threat or, in other words, 43 domain-dependent soft privacy threats arise from the combination of the domain-independent threat with each of the assets.

### Smart Home

*[privacy_threats_smarthome.xlsx](./privacy_threats_smarthome.xlsx)*

This file contains three tabs named "Smart Home Assets", "Soft Privacy" and "Hard Privacy". The first tab includes the assets collected for the target domain (smart home), along with the document source (S) and category/group for each asset. The second and third tabs feature the domain-dependent threats for, respectively, soft and hard privacy, obtained by appropriate combinations with the target domain assets, along with the document source (S) for each threat.

For example, within the Hard Privacy tab, let us consider row 26: the threat "Attributable action side-effect evidence" sourced from LINDDUN can be associated with "Users preferences" and "Behavioural patterns and trends" (totalling 2 assets). Consequently, there are 2 instances of this threat or, in other words, 2 domain-dependent hard privacy threats arise from the combination of the domain-independent threat with each of the assets.
