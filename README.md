## AI Detection-Engine Idea for Security Operations Center(SOC)

Final project for the Building AI course

## Summary

AI as a Detection Engine in a Security Operations Centre: Using Artificial Intelligence for Security Data Aggregation, Parsing, Correlation, and Policy-Based Detection of Security Events and Incidents

## Background

This project explores the use of Artificial Intelligence as a detection engine within a Security Operations Centre (SOC).The propsed approach uses AI to aggregate, parse, normalize, and correlate security telemetry from multiple data sources and evaluate observed activities against predefined corporate security policies, security requirements, and approved behavioural conditions.

Instead of relying exclusively on static SIEM correlation rules, the AI Detection Engine(ADE) would analyse the context surrounding security activities and determine whether they represent normal behaviour, a policy violation, a suspicious security event, or a potential security incident requiring SOC investigation.

The objective is to investigate whether an AI-driven approach can improve detection accuracy, contextual understanding, and adaptability while reducing the manual effort required to create and maintain large numbers of traditional detection rules.


## How is it used?

The detection engine will be deployed exclusively within a defined enterprise IT and/or Operational Technology (OT) environment. It will operate inside the organization's controlled infrastructure and will not depend on external AI services or external connections for security-data analysis. This design helps ensure that sensitive security telemetry, asset information, and organizational policies remain within the enterprise security boundary.

The AI will be trained, adapted, and continuously contextualized using enterprise-specific data, including system and application logs, network telemetry, authentication events, endpoint information, IT/OT asset inventories, historical security events, and other relevant security data.


## Data sources and AI methods
The AI detection engine should derive its operational security evidence exclusively from enterprise event logs and network-flow telemetry

## Challenges

The effectiveness of the  engine will depend heavily on the quality, quantity, consistency, and representativeness of the enterprise event logs and network-flow data available to it. Key challenges include noise reduction, false-positive management, sufficient training data, data quality, behavioural change, and explainabilit
## What next?

The next stage of the project would be to evaluate whether the  AI detection engine can be transformed from a conceptual model into a controlled enterprise proof of concept (PoC).

Enterprise business units should consider the potential of AI not only as an additional SOC analysis tool, but as a possible future component of the security detection architecture itself. This would require collaboration between business stakeholders, cybersecurity specialists, AI specialists, and the teams responsible for the underlying IT and OT infrastructure.

A multidisciplinary expert review would therefore be an important next step.

Expertise required:

SOC analysts would be required to define realistic detection scenarios and determine what information is necessary for an AI-generated detection to be useful during investigation.

Detection and security engineers would be required to translate existing detection logic, attack patterns and security requirements into requirements that can be evaluated by the AI engine.

Security architects would assess how the AI engine could be securely integrated into the existing enterprise security architecture, including its interaction with SIEM, network monitoring, identity, endpoint and OT security systems.

AI/ML and data engineers would be required to develop the underlying models, data pipelines, feature engineering, behavioural baselines and mechanisms for processing large volumes of event and network-flow data.

IT and OT specialists would provide the operational knowledge required to understand assets, system dependencies and legitimate communication patterns, particularly where unusual behaviour may be perfectly normal for a specific industrial system.

Governance, risk and compliance specialists would help translate corporate security policies into controls that can be evaluated by the detection engine and ensure that the use of AI remains auditable and appropriately governed.

