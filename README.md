# Zero Trust Policy Design - Last updated  2025

## Zero Trust Security Policy for Remote and Hybrid Workforces

### **Policy Statement**
This policy defines the responsibilities, standards and controls required to implement Zero Trust Architecture (ZTA) for securing remote and hybrid workforces. Following the principle *“Never trust, always verify”*, it mandates continuous authentication, strict access controls across users and devices, real-time threat assessment, and continuous security monitoring across all organisational digital resources.

---

## **Purpose**
This policy aims to:

i) Reduce insider threats and external attacks  
ii) Protect access to critical systems regardless of user location  
iii) Ensure compliance with GDPR and other regulatory requirements  
iv) Support scalability and performance without compromising security  

---

## **Scope**
This policy applies to:

i) All employees, contractors, and third-party users accessing enterprise systems  
ii) All devices (corporate-owned and BYOD), applications, and services used remotely or in hybrid roles  
iii) All digital assets, data repositories, and network infrastructure owned or managed by the organisation  

---

## **Guiding Principles of Zero Trust**

### **Table 1 – Main Principles of Zero Trust**

| **Principle**              | **Description** |
|---------------------------|-----------------|
| **Verify Explicitly**     | Authenticate and authorise using all available data points (identity, device, location, workload, etc.). |
| **Use Least Privilege**   | Grant only the minimum access required. Enforce RBAC and ABAC policies. |
| **Assume Breach**         | Architect systems as though a breach has already occurred. Minimise blast radius and lateral movement. |
| **Continuous Monitoring** | Use AI-driven tools (UEBA, ML anomaly detection) for real-time detection and response. |

---

# **5. Key Controls and Policy Directives**

## **5.1 Identity and Access Management (IAM)**
- Mandate MFA and Single Sign-On (SSO) for all sensitive systems  
- Implement federated IAM using cloud-native protocols and time-based RBAC (Alam et al., 2024)  
- Use context-aware access controls based on real-time risk (Krishnan & Sreeja, 2021)  
- Conduct access reviews every three months  

---

## **5.2 Network Segmentation & Micro-Segmentation**
- Implement micro-segmentation across all enterprise networks  
- Isolate sensitive assets (HR systems, financial records) using strict firewall policies  
- Use Software-Defined Networking (SDN) where possible  
- Survey data indicates 62.5% of organisations prefer phased segmentation for remote access and legacy systems  

---

## **5.3 Device Security & Endpoint Management**
- Enrol all devices in Mobile Device Management (MDM) with remote wipe capability  
- Enforce compliance checks before granting access  
- Deploy Endpoint Detection and Response (EDR) organisation-wide  

---

## **5.4 Continuous Monitoring & AI Integration**
- Use AI/ML-powered UEBA for user/entity behaviour monitoring  
- Detect insider threats and compromised accounts using anomaly detection  
- Enable centralised logging and 24/7 real-time alerting  
- Conduct periodic audits of ML models for fairness, bias and accuracy  

---

## **5.5 Data Protection & Encryption**
- Encrypt all data in transit and at rest (minimum TLS 1.3)  
- Use standard data classification frameworks to identify sensitive data  
- Enforce Data Loss Prevention (DLP) for cloud and endpoint systems  

---

## **5.6 Application Security**
- Apply Zero Trust principles to all applications  
- Use service mesh technologies such as **Istio** for cloud-native workloads (Rodigari et al., 2021)  
- Carry out regular penetration testing, vulnerability scanning and code reviews  
- For smart device environments, use adaptive access methods like HyBRCAC and HyBACRC (Ameer et al., 2023)  

---

## **5.7 Policy Enforcement & Governance**
- The **Policy Decision Point (PDP)** must determine all access decisions based on live context  
- The **Policy Enforcement Point (PEP)** must enforce PDP decisions consistently  
- Establish a **Zero Trust Governance Committee** for oversight and annual reviews  
- All staff must complete Zero Trust Awareness training annually  

---

# **6. Roles and Responsibilities**

### **Table 2 – Roles and Responsibilities**

| **Role**               | **Responsibility** |
|------------------------|--------------------|
| **CISO**               | Overall Zero Trust enforcement and regulatory compliance |
| **IT Security Team**   | Technical implementation of IAM, monitoring, segmentation |
| **HR & Training**      | Deliver awareness programmes and track training compliance |
| **Employees & Contractors** | Follow access control requirements and report anomalies |

---

# **7. Compliance and Monitoring**
- Compliance will be validated through internal audits  
- Regulatory assessments (e.g., GDPR) will be applied  
- Security performance will be measured using defined KPIs  
- Non-compliance may result in termination, access suspension or disciplinary action  

---

# **8. Exceptions**
Any exception to this policy must be formally approved by the CISO, justified, documented, and accompanied by a risk assessment.

---

# **9. Review Cycle**
This policy will be reviewed annually or sooner if:

- A major security incident occurs  
- Regulatory or technology changes take place  
- Audit findings identify gaps  

