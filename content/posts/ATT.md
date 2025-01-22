---
title: "Threat Intelligence Report: The AT&T Data Breach"
date: 2024-07-12
description: "An in-depth analysis of the AT&T data breach, including details of past compromises and how they aggregate to yield higher risk."
tags: ["Data Breach", "Cybersecurity", "AT&T"]
author: "Zach Lemley"
image: "/images/att-logo.png"
---
<p align="center">
  <img src="/images/att-logo.png" alt="AT&T Logo" class="standard-image"/>
</p>

### What Happened
On July 12, 2024, AT&T disclosed a breach where threat actors illicitly downloaded customer records, affecting "nearly all" customers using its wireless services. The compromised data includes call records from May 1 to October 31, 2022, and a small number on January 2, 2023. These call logs were copied from AT&T's workspace on a third-party cloud platform, reportedly Snowflake.

### Data Compromised
- Source and destination numbers
- Cell site information for a subset of the data (provides rough geolocation of AT&T wireless customers)

### Timeline
- **April 9, 2024**: AT&T learned about the incident.
- **May 9 & June 5, 2024**: DOJ approved delays in public disclosure.
- **July 12, 2024**: AT&T filed an 8-K with the SEC, stating the incident was not deemed material despite shares dropping 2%.

### Use of Compromised Data
- Threat actors could use call data records (CDR) for intelligence analysis, mapping phone numbers to identities.
- Potential to identify SMS-based MFA users and the services they use.
- Encourages migration away from SMS-based MFA.

### Breach Notification Requirements
- Unclear what breach notification requirements this may trigger.
- International call records to Canada were included, potentially implicating GDPR.

### Potential Vulnerabilities
- Snowflake has received criticism for not enforcing stronger security settings, though these were available.
- Comparison to 1980s cars with seat belts but no alarms highlights user responsibility for security configuration.

### Executive Communication Points
1. Possible impact even for non-AT&T customers.
2. Only call and SMS metadata were compromised.
3. Metadata is powerful for intelligence analysis.
4. Potential risk if threat actors connect organizations using the data.
5. Need to migrate away from SMS-based MFA.
6. Consult privacy counsel for breach notification requirements.
7. Threat actors may combine data from previous incidents to exacerbate impacts.
8. Evaluate exposure in Snowflake and other platforms, enabling MFA and best security practices.
9. Potential exposure for MVNOs piggybacking on AT&T’s network.

## Additional Details from Recent Findings

### Larger Scale of the Breach
Further investigation revealed that the breach impacted nearly 73 million current and former AT&T customers. The data set appears to be from 2019 or earlier and includes sensitive personal information such as full names, email addresses, phone numbers, social security numbers, and AT&T account numbers.

### Dark Web Activity
The breached data appeared on the dark web, initially offered for sale in 2021 and later leaked in its entirety in 2024. This raises concerns about the long-term exposure and potential misuse of the data by various threat actors.

### AT&T's Response
AT&T has reset account passcodes for all active accounts and is offering credit monitoring services to the affected customers. They have also launched a robust investigation with the help of internal and external cybersecurity experts to assess the source and impact of the breach.

## Correlation with the April Incident

### April 2024 Breach Details
In April 2024, AT&T disclosed a significant data breach impacting approximately 51 million current and former customers. This breach included personal information such as full names, email addresses, mailing addresses, phone numbers, social security numbers, and AT&T account numbers. The data appeared to be from 2019 or earlier.

### Relationship Between the Incidents
Both incidents involve the exposure of sensitive customer data, and the April breach seems to be a precursor to the larger-scale exposure revealed in July. The compromised data in both instances includes similar types of personal information, indicating a possible connection between the data sets leaked over time. The long-term exposure and subsequent dark web activity suggest that the data from the April incident may have been part of the broader dataset leaked in July.

## Aggregation of Data from Past Breaches

### Overview of Past Breaches (2019-2024)
- **July 2024 Breach**: Exposed nearly 73 million current and former customer records, including social security numbers, passcodes, email, and mailing addresses.
- **April 2024 Breach**: Impacted 51 million customers, with personal information such as full names, email addresses, and social security numbers compromised.
- **March 2023 Breach**: Affected 9 million customers due to a third-party vendor's breach, exposing Customer Proprietary Network Information (CPNI).
- **August 2021 Incident**: Data for over 70 million customers was put up for sale, though AT&T denied this data came from its systems.
- **2014 Breach**: Affected 280,000 customers due to insider threats and third-party vendor issues.

### Aggregated Data for Future Attacks
The various types of data stolen in past breaches can be aggregated to create a comprehensive profile of individuals, which can be exploited for future attacks:
- **Personal Identification Information (PII)**: Full names, social security numbers, and birth dates can be used for identity theft and fraudulent activities.
- **Contact Information**: Email addresses, phone numbers, and mailing addresses can facilitate phishing attacks, scams, and targeted social engineering.
- **Account Details**: AT&T account numbers, passcodes, and Customer Proprietary Network Information (CPNI) can be used to gain unauthorized access to accounts and services.
- **Metadata**: Call and SMS metadata can be used for intelligence analysis, mapping relationships, and identifying patterns of communication.

### Implications of Aggregated Data
Aggregated data from multiple breaches enhances the ability of threat actors to:
- Execute more sophisticated and targeted phishing and social engineering attacks.
- Carry out identity theft and financial fraud with higher success rates.
- Exploit call and SMS metadata to understand communication networks and potentially blackmail or manipulate individuals.
- Use compromised account details to gain unauthorized access to services and carry out further attacks.

## Conclusion
This incident underlines the importance of securing call and SMS metadata and the need for stringent security measures on third-party platforms like Snowflake. Organizations must assess their exposure and take proactive steps to mitigate risks, including migrating from SMS-based MFA and consulting privacy counsel for potential breach notifications.

The correlation between the April and July incidents highlights the need for continuous monitoring and rapid response to data breaches to minimize long-term impacts and prevent further exploitation of compromised data.

*Stay Vigilant*