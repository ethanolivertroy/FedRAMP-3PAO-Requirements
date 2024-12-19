

# FedRAMP Training Program - RFC 0002 Breakout

**Reference:** [RFC 0002](https://github.com/FedRAMP/rfc0002-a2la-r311-recommendations/blob/main/rfc/0002.md)

## FedRAMP Control Assessors

### 1. FedRAMP Authorization Boundary, Dataflow, and Network Diagrams

- **FedRAMP Authorization Boundary Guidance**
- Security controls relating to the authorization boundary, dataflow, and network diagrams (including all relevant enhancements):  
  - AC-20, CA-3, CM-12, SA-9, SC-7, SI-4
- Essential elements of authorization boundary, dataflow, and network diagrams, including:  
  - Subnets  
  - Alternate processing/storage sites  
  - Mobile applications  
  - Development/test environments  
  - FIPS 140 validated encryption  
  - Multi-factor authentication methods

### 2. FedRAMP FIPS 140-Validated Encryption

- NIST Cryptographic Module Validation Program (CMVP)
- FedRAMP SSP Template - Section 10
- FedRAMP SSP Template Appendix Q - Cryptographic Modules Table
- Security controls relating to encryption requirements (including all relevant enhancements):  
  - AC-17, AC-18, AC-19, IA-5, MP-5, SC-7, SC-8, SC-13, SC-28
- NIST SP 800-63-3 Digital Identity Guidelines

### 3. FedRAMP NIST SP 800-53 and 800-53A Security Control Interpretation Methods

- Differences between leveraged and inherited security controls in a CSP’s SSP
- Identifying applicable vs. not applicable controls in a CSP’s SSP
- Documenting security controls in the CIS/CRM
- Recognizing errors concerning “Configuration Settings”
- Differentiating between Control Implementation Summary (CIS) designations
- Recognizing inconsistencies among related security controls
- Identifying effective policies and procedures for a given control
- Determining if a control adequately describes who, what, when, where, why, and how in the SSP implementation
- Validating customer responsibilities (ensuring at least one required option/solution meets FedRAMP requirements)

### 4. FedRAMP Multi-Factor Authentication Requirements

1. **NIST SP 800-63 (current revision)**  
   - **Identity Assurance Levels (IAL1, IAL2, IAL3)**  
     - Importance of IAL information  
     - Identity proofing user journey  
     - IAL requirements summary
   - **Authentication Assurance Levels (AAL1, AAL2, AAL3)**  
     - Importance of AAL information  
     - AAL2 permitted authenticators, and verifier requirements  
     - AAL3 permitted authenticators, and verifier requirements  
     - AAL requirements summary
   - **Federation Assurance Levels (FAL1, FAL2, FAL3)**  
     - Importance of FAL information  
     - Federation threats and attacks  
     - Federation threat mitigation strategies  
     - SAML, Kerberos, OpenID Connect and their relation to the FAL paradigm

2. FedRAMP security control baselines (including all relevant enhancements) related to MFA:  
   - IA-2, IA-2(1), IA-2(2), IA-2(6), IA-5, IA-8

3. Overview of NIST SP 800-63 Digital Identity Guidelines FAQs:  
   - Identity proofing  
   - Authentication  
   - Federation and assertions

---

## FedRAMP Pentesters

All personnel in the “penetration tester” role must receive focused internal training on four (4) FedRAMP focus areas:

### 1. Vulnerability Scanning vs. Penetration Testing

- **Penetration Testing**  
  - Scope of penetration testing  
  - Threat models applicable to a particular system  
  - Alignment with FedRAMP security control baselines and associated controls
- **Vulnerability Scanning**  
  - Scope of vulnerability scanning

### 2. MITRE ATT&CK® Matrix for Enterprise

- Definition and purpose of the MITRE ATT&CK® Matrix for Enterprise  
  - When it is used  
  - Why it is used  
  - How it is used

### 3. FedRAMP Mandatory Attack Vectors and Applicability

- Attack Vector 1: External to Corporate
- Attack Vector 2: External to CSP Target System
- Attack Vector 3: Tenant to CSP Management System
- Attack Vector 4: Tenant-to-Tenant
- Attack Vector 5: Mobile Application as part of Target System
- Attack Vector 6: Client-side Component as part of Target System

### 4. FedRAMP Penetration Testing Reporting Requirements

- Familiarity with penetration testing rules of engagement
- Reporting penetration testing deficiencies in a security assessment package

---