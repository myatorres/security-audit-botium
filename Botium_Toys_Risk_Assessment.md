# Botium Toys – Internal Security Audit Report

## Audit Scope and Goals

**Scope**: Review all internal assets, systems, and controls related to Botium Toys' IT infrastructure.

**Goals**:
- Identify key security risks
- Evaluate compliance with applicable regulations
- Recommend control improvements to strengthen cybersecurity posture

---

## Summary of Findings

The internal audit revealed several critical gaps in Botium Toys’ security posture:

- **Asset Management**: Lack of asset classification and documentation
- **Access Controls**: No role-based access or separation of duties
- **Encryption**: Credit card data is not encrypted
- **Incident Response**: No disaster recovery or IDS in place
- **Password Policy**: Weak enforcement and no centralized password management
- **Physical Security**: Adequate (locks, fire suppression, CCTV)

---

## Risk Assessment Highlights

- **Risk Score**: 8/10
- **Impact**: Medium to high (due to possible data loss or fines)
- **Root Causes**:
  - Insufficient access controls
  - Lack of encryption and disaster planning
  - Limited regulatory compliance (PCI-DSS, GDPR)

---

## Compliance Checklist

See [controls_compliance_checklist.md](./controls_compliance_checklist.md) for a completed checklist indicating compliance status across 20+ controls.

---

## Recommendations

- Implement access control policies based on least privilege
- Encrypt stored cardholder data
- Establish regular backups and a disaster recovery plan
- Deploy an Intrusion Detection System (IDS)
- Enforce stronger password policies with a central management system

