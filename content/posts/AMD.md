---
title: "Threat Intelligence Report: The AMD Data Breach"
date: 2024-06-19
description: "A comprehensive analysis of the AMD data breach, including details of the threat actor 'IntelBroker', the data stolen, and the attack techniques observed."
tags: ["Data Breach", "Cybersecurity", "AMD"]
author: "Zach Lemley"
image: "/images/amd-logo.png"
---
<p align="center">
  <img src="/images/amd-logo.png" alt="AMD Logo" class="standard-image"/>
</p>

## Introduction

In June 2024, AMD, one of the largest makers of personal computer processors, experienced a significant data breach. This report delves into the breach, detailing the methods employed by the attackers, the extent of the compromised data, and the broader implications for AMD and its stakeholders.


## Background

AMD (Advanced Micro Devices Inc.) is a global company that designs and produces high-performance computing and graphics products. The breach has raised considerable concerns about the security of AMD's systems and the integrity of its data.

## The Breach Details

### Discovery and Initial Response

The breach was first reported by AMD on June 18, 2024, following claims by a cybercriminal group called 'IntelBroker' on BreachForums. AMD's security team is currently investigating these claims in collaboration with law enforcement and a third-party hosting partner to ascertain the veracity and extent of the data theft.

### Data Compromised

The compromised data includes highly sensitive and proprietary information critical to AMD's operations and competitive advantage. Below is a detailed breakdown of the compromised data:

#### Future AMD Products
- **Specifications and Roadmaps**: Details about upcoming processors, GPUs, and other hardware products, including technical specifications, performance metrics, and release timelines.
  - Example: The attackers have listed specific details about future CPU models and their expected release dates, potentially impacting AMD's competitive positioning.

#### Spec Sheets
- **Product Specifications**: Detailed specifications of current and future AMD products, including hardware configurations, performance benchmarks, and compatibility information.
  - Example: Spec sheets for upcoming graphics cards were part of the compromised data, providing insight into AMD's next-generation graphics technologies.

#### Employee Databases
- **Personal Information**: Names, email addresses, phone numbers, job functions, and employment statuses of AMD employees.
- **Credential Information**: Potential exposure of login credentials that could be used to access AMD's internal systems.

##### Sample of Employee Database

| User ID  | First Name  | Last Name    | Job Function(s) | Business Phone | Email                 | Status   |
|----------|-------------|--------------|-----------------|----------------|-----------------------|----------|
| jotan    | JooMay      | Tan          | No Privilege    |                | JooMay.Tan@amd[.]com    | Inactive |
| akarunan | Arun        | Karunanithi  | No Privilege    | 8352085        | Arun.Karunanithi@amd[.]com | Inactive |
| royoun   | Roger       | Young        | No Privilege    |                | Roger.Young@amd[.]com   | Inactive |
| mrunals  | Mrunal      | Shah         | No Privilege    |                | Mrunal.Shah@amd[.]com   | Inactive |

#### Customer Databases
- **Client Information**: Names, contact details, and transaction histories of AMD's clients, including both individual consumers and enterprise customers.
  - Example: The stolen data includes customer names and purchase histories, exposing sensitive client relationships and transactions.
- **Order Details**: Records of orders placed by customers, including product details, quantities, and shipping information.
  - Example: Details of bulk orders from enterprise customers were among the compromised information, potentially revealing strategic business insights.

#### Property Files
- **Real Estate Information**: Documents related to AMD's property holdings, including office locations, lease agreements, and property management records.
  - Example: Lease agreements for AMD's office spaces and manufacturing facilities were part of the breach, exposing operational logistics.
- **Asset Inventories**: Lists of physical assets owned by AMD, such as office equipment, servers, and manufacturing tools.
  - Example: Detailed inventories of AMD's hardware and equipment, providing insight into their operational capacities.

#### ROMs and Source Code
- **Firmware and Software Code**: Source code for AMD's firmware, drivers, and software tools, which are essential for the functioning and security of AMD's hardware products.
  - Example: Source code for AMD's proprietary firmware and software was among the stolen data, potentially leading to security vulnerabilities if exploited.
- **Development Projects**: Code repositories and documentation for ongoing and future software development projects.
  - Example: Documentation and source code for upcoming software features and improvements were compromised, risking intellectual property theft.

#### Financial Records
- **Financial Statements**: Detailed financial records, including balance sheets, income statements, and cash flow statements.
  - Example: Internal financial statements revealing AMD's financial health and strategic investments were part of the breach.
- **Budget Reports**: Internal budgeting documents and forecasts that outline AMD's financial planning and resource allocation.
  - Example: Detailed budget reports, including future financial plans and resource allocations, were exposed, potentially affecting investor confidence.

### Attack Techniques

The specific attack techniques used by the threat actors have not been fully disclosed. However, the following advanced tactics and procedures are suspected:

1. **Credential Dumping**: The attackers likely used techniques to dump credentials, allowing them to access various parts of the AMD network.
2. **Lateral Movement**: Once inside, the attackers may have moved laterally across the network, using compromised credentials to access more systems.
3. **Data Exfiltration**: The data was likely exfiltrated using encrypted channels to avoid detection by AMD's security systems.
4. **Obfuscation**: The attackers probably used advanced evasion techniques, such as fileless malware and living-off-the-land binaries (LOLBins), to remain undetected.

### Potential Risks

1. **Intellectual Property Theft**: The stolen future product details and source code could be used by competitors or other malicious entities to undermine AMD's market position.
2. **Financial Loss**: The exposure of financial records could lead to financial losses and impact AMD's stock market performance.
3. **Operational Disruption**: The breach could disrupt AMD's operations, especially if the attackers inserted malicious code into AMD's systems or products.
4. **Reputation Damage**: The breach significantly undermines trust in AMD's ability to protect sensitive information.

## Implications of the Breach

### For Users

- **Exposure of Personal Information**: Customers whose data was compromised may face privacy risks, including identity theft and fraud.
- **Phishing and Social Engineering**: The stolen data could be used to launch targeted phishing campaigns against AMD customers and employees.

### For Organizations

- **Reassessment of Security Posture**: Organizations using AMD products must reassess their security measures to mitigate similar risks.
- **Compliance Challenges**: The breach could lead to compliance issues, especially if it involves data protected under regulations like GDPR or CCPA.
- **Supply Chain Security**: The breach highlights the importance of securing the supply chain to prevent similar incidents in the future.

## AMD's Response

AMD has responded to the breach with the following measures:

- **Immediate Investigation**: Collaborating with law enforcement and third-party experts to investigate the breach.
- **User Notifications**: Notifying affected parties and advising them on protective measures.
- **Security Enhancements**: Implementing additional security measures to prevent future breaches.

## Conclusion

The AMD data breach orchestrated by 'IntelBroker' is a stark reminder of the persistent cybersecurity threats facing organizations today. Both users and organizations must take proactive measures to secure their data and systems. AMD's ongoing investigation and response highlight the importance of vigilance and robust security practices.

*Stay Vigilant*