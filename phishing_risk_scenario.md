# 📋 IT Risk Scenario Evaluation: Phishing Attack
**Framework Reference:** 10H | **Source Standard Mappings:** COBIT & ISO/IEC 27001:2022

---

## 📌 A. Risk Scenario Description

| Attribute | Specification |
| :--- | :--- |
| **Risk Scenario Title** | Enterprise data are stolen through unauthorized access gained by a phishing attack |
| **Risk Type** | 3 - Data and System Protection |
| **Risk Scenario Category** | **Internal and External Security Threats (e.g., hacker, malware):** Malicious access to and compromise or misuse of technology systems, impacting the confidentiality, integrity, or availability of technology systems and business information |
| **Risk Statement** | A malicious actor launches a cyberattack via phishing emails, affecting the confidentiality, integrity, and availability of assets |
| **Risk Owner** | CISO, Business Process Owner, Risk Oversight |

---

## 🏗️ B. Risk Scenario Components

* **Actor / Threat Community:** Cybercriminals, hacktivists, untrained/accidental insiders, malicious insiders, and malicious accidental insiders.
* **Intent / Motivation:** Phishing attacks are generally launched by external malicious actors with the intention of financial gain, causing reputational harm, or committing cyber espionage. They are typically enabled by accidental actions by untrained internal employees.
* **Threat Event:** Possible threat events mainly include the exploitation of the human factor with the use of social engineering methods combined with the distribution of malicious software.
* **Assets / Resources:** Any organization system or asset, any data stored on affected systems, and general system availability.
* **Consequence:** Response costs and reputation issues; under certain circumstances, significant costs may include productivity loss, competitive advantage loss, and regulatory fines.

### 📉 Impact Dimensions (Potential Forms of Loss)
* **✓ Productivity:** Productivity losses are relevant in cases where the organization did not maintain backup files of the stolen data and, hence, data are not available and need to be re-created.
* **✓ Cost of Response:** Response costs are present as incident responders, communications, PR, management meetings, forensics, etc., work on the incident depending on severity.
* **☐ Replacement Cost:** Usually, there is no need for capital assets replacement in this scenario.
* **✓ Competitive Advantage:** Competitive advantage should be seriously considered because data lost may include confidential enterprise information (e.g., innovative ideas, strategic plans, source code, intellectual property).
* **✓ Reputation:** If the incident affects customers and is severe enough, reputation may be impacted.
* **✓ Fines and Judgments:** If enterprise data include personal data, then regulatory fines may be imposed (e.g., GDPR, CCPA, FTC).
* **⏱️ Timing & Duration:** The duration of the incident can be very short or prolonged. Early detection of the data loss is key to minimizing the impact.

---

## 🔭 C. Risk Scenario Scope & Extent

### Scenario Severity Thresholds
* **Worst Case:** The attacker resides within the enterprise network for months, and data are leaked gradually to avoid detection. A worst-case scenario includes confidential enterprise data and customers' personal and sensitive data.
* **Typical or Most Likely Case:** The attacker obtains confidential information that does not include detailed intellectual property information or a subset of customers' personal data.
* **Best Case:** A compromised user account or workstation infection is detected and contained. Bits of enterprise information may be leaked but with no value for the adversary.

### Underlying Assumptions
1. The organization has systems or data critical to business processes.
2. The organization uses email to communicate.

---

## 🛡️ D. Controls to Mitigate the Risk Scenario

| # | Mitigating Control Description | Control Type | Impact Effect | Frequency Effect | Essential Control? | Framework References |
| :-: | :--- | :-: | :-: | :-: | :-: | :--- |
| **1** | **Define and communicate policies and procedures.** Put in place procedures to maintain compliance with and performance measurement of policies and other components of the control framework. Enforce the consequences of noncompliance. | Preventive | Yes | Yes | **Yes** | COBIT APO01.09 <br> ISO 27001:2022 5.1 |
| **2** | **Analyze risk.** Periodical risk assessment and risk management in general are essential to identify potential risk, its impact and probability. This control is needed to identify others properly. | Preventive | Yes | Yes | **Yes** | COBIT APO12.02 <br> ISO 27001:2022 6.1.2 |
| **3** | **Monitor I&T infrastructure.** The proper continuous monitoring of the I&T infrastructure ensures that lack of compliance or new types of events are identified swiftly. Monitor for anomalous behavior. | Preventive | Yes | Yes | **Yes** | COBIT DSS01.03 <br> ISO 27001:2022 8.16 |
| **4** | **Manage endpoint security.** Ensure that endpoints (laptops, desktops, servers, mobile devices) are secured at a level equal to or greater than defined requirements. | Preventive | Yes | Yes | **Yes** | COBIT DSS05.03 <br> ISO 27001:2022 8.1 |
| **5** | **Manage user identity and logical access.** Ensure that all users have information access rights in accordance with business requirements. Full identity lifecycle management. | Preventive | Yes | Yes | **Yes** | COBIT DSS05.04 <br> ISO 27001:2022 5.16 |
| **6** | **Manage roles, privileges, and authority segregation.** Manage business roles, privileges, and levels of authority needed to support process objectives. Segregate conflicting duties. | Preventive | Yes | Yes | **Yes** | COBIT DSS06.03 <br> ISO 27001:2022 5.3 |
| **7** | **Define business continuity policy, objectives, and scope.** Define continuity policy and scope aligned with enterprise objectives to improve business resilience and security during disruptions. | Preventive | Yes | Yes | **Yes** | COBIT DSS04.01 <br> ISO 27001:2022 5.29 |
| **8** | **Maintain business resilience.** Evaluate business resilience options and choose cost-effective strategies for continuity, disaster recovery, and incident response. | Preventive | Yes | Yes | **Yes** | COBIT DSS04.02 <br> ISO 27001:2022 5.30 |

---

## 📈 E. Key Risk Indicators (KRIs)

The following metrics serve as **Leading Indicators** to proactively gauge risk exposure:

1. **Organizational Communications Frequency:** Frequency of communication on management objectives and direction for I&T.
2. **Requirement Communication Distribution:** Percentage of customer requirements and expectations communicated throughout the business and IT organization.
3. **Endpoint Awareness Training Coverage:** Percentage of individuals receiving awareness training relating to use of endpoint devices.
4. **Policy Competency Baseline:** Percentage of staff aware and able to demonstrate competency with respect to policies and procedures.
5. **Account Discrepancy Audits:** Number of accounts vs. number of authorized users/staff.
6. **Simulation Success Ratios:** Percentage of successful security risk scenario simulations.
7. **Profile Scope Mapping:** Percentage of key business processes included in the risk profile.
8. **Stakeholder BIA Engagement:** Percentage of key stakeholders involved in business impact analyses evaluating the impact over time of a disruption to critical business functions.
9. **Continuity Strategy Consensus:** Percentage of key stakeholders participating, defining, and agreeing on continuity policy and scope.
10. **Privilege Mapping Matrix:** Percentage of business process roles with assigned access rights and levels of authority.
