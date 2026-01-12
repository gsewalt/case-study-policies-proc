# Case Study: Information Security Policy Program – Small Real Estate Brokerage

**Organization:** Independent Real Estate Brokerage (Name Redacted)  
**Location:** Victorville, CA  
**Employees:** 4  
**Author:** Gregory Sewalt 
**Document Type:** Security Policies, Standards, and Procedures  
**Framework Alignment:** NIST CSF 2.0, NIST SP 800-53, NIST SP 800-37  

---

## 1. Purpose

This case study documents the development and implementation of a lightweight but effective **information security policy program** for a small real estate brokerage handling sensitive client and financial data.

The objective was to:
- Establish clear security expectations
- Reduce operational and cybersecurity risk
- Align day-to-day practices with NIST guidance
- Ensure policies are understandable, actionable, and adopted by staff

This program was intentionally scoped and written to be **maintainable by a small business** without dedicated security personnel.

---

## 2. Policy Development Approach

Policy development followed a structured but pragmatic approach:

1. **Risk-Driven Design**  
   Policies were prioritized based on findings from the brokerage’s cybersecurity risk assessment (email compromise, ransomware, data exposure).

2. **Framework Alignment**  
   Each policy maps to NIST CSF 2.0 functions and relevant NIST 800-53 control families.

3. **Plain-Language Writing**  
   Policies were written in clear, non-technical language to ensure staff comprehension and adoption.

4. **Scalability**  
   Policies were designed to evolve as the business grows or adopts new technologies.

---

## 3. Security Policy Structure

The security program is composed of three layers:

| Layer | Description |
|-----|-------------|
| **Policies** | High-level rules and expectations |
| **Standards** | Minimum security requirements |
| **Procedures** | Step-by-step implementation guidance |

---

## 4. Core Security Policies

### 4.1 Information Security Policy

**Purpose:**  
Define management’s commitment to protecting client, employee, and business information.

**Key Statements:**  
- Information security is a shared responsibility.  
- Client data must be protected against unauthorized access, disclosure, or loss.  
- Security controls must balance protection with business usability.

**Owner:** Broker / Office Owner  
**Review Cycle:** Annual

---

### 4.2 Access Control Policy

**Purpose:**  
Ensure systems and data are accessible only to authorized individuals.

**Policy Requirements:**  
- Unique user accounts for all staff  
- Role-based access aligned to job responsibilities  
- Multi-factor authentication (MFA) for cloud services and email  
- Immediate access removal upon termination or role change  

**NIST Alignment:** AC-2, AC-3, IA-2

---

### 4.3 Acceptable Use Policy

**Purpose:**  
Define appropriate use of company devices, systems, and data.

**Policy Requirements:**  
- Company systems are for business use only  
- Prohibited activities include unauthorized software installation and data sharing  
- Devices must be secured when unattended  

---

### 4.4 Data Protection & Privacy Policy

**Purpose:**  
Protect sensitive client and transaction data.

**Policy Requirements:**  
- Client data must be stored only in approved systems  
- Encryption required for laptops and shared storage  
- Data sharing limited to authorized parties  
- Secure disposal of electronic and physical records  

**Data Types Covered:**  
- Client PII  
- Financial records  
- Contracts and transaction documents  

---

### 4.5 Incident Response Policy

**Purpose:**  
Ensure timely and effective response to cybersecurity incidents.

**Policy Requirements:**  
- All suspected incidents must be reported immediately  
- Incident response roles and escalation paths defined  
- Incidents documented and reviewed for improvement  

**Examples of Incidents:**  
- Phishing emails  
- Malware infections  
- Lost or stolen devices  
- Unauthorized account access  

**NIST Alignment:** IR-1, IR-4, IR-6

---

## 5. Security Standards (Minimum Requirements)

Standards define **how policies are enforced in practice**.

### 5.1 Identity & Authentication Standard

| Requirement | Standard |
|------------|----------|
| Password Length | Minimum 12 characters |
| MFA | Required for email and cloud platforms |
| Account Sharing | Prohibited |
| Privileged Access | Limited to business owner and IT support |

---

### 5.2 Endpoint Security Standard

| Requirement | Standard |
|------------|----------|
| Encryption | Full-disk encryption required |
| Patching | Monthly OS and application updates |
| Antivirus | Enabled and monitored |
| Device Lock | Auto-lock after inactivity |

---

### 5.3 Backup Standard

| Requirement | Standard |
|------------|----------|
| Backup Frequency | Daily |
| Storage Location | Encrypted local or cloud backup |
| Testing | Monthly restore verification |

---

## 6. Procedures

### 6.1 User Onboarding Procedure

1. Create unique user account  
2. Assign role-based access  
3. Enable MFA  
4. Provide security awareness briefing  
5. Document access granted  

---

### 6.2 User Offboarding Procedure

1. Disable user accounts immediately  
2. Revoke access to cloud and shared systems  
3. Retrieve company devices  
4. Transfer ownership of files  
5. Document completion  

---

### 6.3 Incident Reporting Procedure

1. Employee identifies suspicious activity  
2. Employee notifies designated security contact  
3. Initial containment actions taken  
4. Incident documented  
5. Lessons learned reviewed  

---

## 7. Policy Socialization & Adoption

To ensure policies were not just written but **understood and followed**, the following steps were taken:

| Activity | Description |
|-------|-------------|
| Leadership Briefing | Policies reviewed with owner and office manager |
| Staff Walkthrough | Plain-language overview provided to all employees |
| Acknowledgment | Employees acknowledged understanding |
| Integration | Policies referenced during onboarding and training |
| Reinforcement | Security reminders incorporated into staff meetings |

---

## 8. Maintenance & Review

| Activity | Frequency |
|--------|-----------|
| Policy Review | Annually |
| Risk Review | Annually or after major changes |
| Incident Review | After each incident |
| Training Refresh | Annually |

Policy updates are triggered by:
- New technology adoption
- Security incidents
- Business growth
- Regulatory or contractual changes

---

## 9. Outcomes & Metrics

| Metric | Before | After |
|------|--------|-------|
| Written Security Policies | 0 | 6 |
| Documented Procedures | 0 | 4 |
| MFA Adoption | Partial | 100% |
| Staff Awareness | Informal | Formalized |
| Access Reviews | None | Annual |

---

## 10. Conclusion

This deliverable demonstrates how a **formal security policy program can be designed, implemented, and socialized in a small business environment** without excessive complexity.

By grounding policies in risk, aligning to NIST frameworks, and focusing on staff understanding, the brokerage established a sustainable security foundation that supports both business operations and client trust.

This case study reflects hands-on experience developing security governance artifacts that are practical, adopted, and maintainable.

---

**Framework References**
- NIST Cybersecurity Framework (CSF) 2.0  
- NIST SP 800-53 – Security and Privacy Controls  
- NIST SP 800-37 – Risk Management Framework  
