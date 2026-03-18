# Recommendations Register

## Priority Recommendations

| ID | Recommendation | Risk Addressed | Priority | Suggested Owner |
|---|---|---|---|---|
| REC-01 | Implement periodic user access reviews across critical systems | Access Management | High | IT / Operations Manager |
| REC-02 | Remove unnecessary privileged access and enforce least privilege | Access Management | High | IT Administrator |
| REC-03 | Establish a monthly patching schedule for endpoints and critical systems | Patch Management | High | IT Administrator |
| REC-04 | Standardise endpoint protection across all managed devices | Endpoint Security | High | IT Administrator |
| REC-05 | Create and maintain a central asset register with ownership and status fields | Asset Governance | High | Operations / IT |
| REC-06 | Define backup scope for critical systems and test restore procedures quarterly | Backup & Recovery | High | IT / System Owner |
| REC-07 | Create a basic incident response procedure with escalation contacts and actions | Incident Response | Medium | IT / Management |
| REC-08 | Review third-party systems and document key vendor dependencies and risks | Third-Party Risk | Medium | Management / IT |
| REC-09 | Review network architecture and separate high-risk or operational devices where possible | Network Security | Medium | IT / Network Support |
| REC-10 | Document minimum security standards for company devices and accounts | Governance | Medium | IT / Management |

---

## Detailed Recommendation Notes

### REC-01: Periodic Access Reviews
Review user accounts at defined intervals to confirm access remains appropriate for current job responsibilities. Focus first on high-risk platforms, admin accounts, finance-related systems, and shared operational tools.

### REC-02: Privileged Access Reduction
Limit administrative rights to authorised personnel only. Remove legacy access, reduce shared admin usage, and maintain a record of privileged users.

### REC-03: Formal Patch Schedule
Create a recurring patch process with ownership, review dates, and exception handling. Include operating systems, browsers, productivity tools, and operational software.

### REC-04: Endpoint Security Baseline
Ensure all endpoints have standard protections such as antivirus or EDR, OS updates, controlled admin rights, and basic hardening settings.

### REC-05: Central Asset Register
Maintain an up-to-date asset inventory that records device type, assigned owner, location, status, and security management state.

### REC-06: Backup Recovery Testing
Confirm not only that backups run, but that critical systems and files can actually be restored within acceptable timeframes.

### REC-07: Incident Response Procedure
Document what to do when malware, account compromise, phishing, or system outages occur. Include escalation steps and responsibilities.

### REC-08: Vendor Dependency Review
List major business-critical vendors and assess their importance, access level, and operational/security dependency.

### REC-09: Network Review
Assess whether operational devices, office systems, and sensitive services are appropriately separated to reduce exposure.

### REC-10: Minimum Security Standards
Define a baseline for devices, accounts, authentication, updates, antivirus, and acceptable use to improve consistency.

---

## Suggested Implementation Roadmap

### Short Term (0–30 Days)
- Create asset register
- Identify privileged accounts
- Review critical user access
- Confirm endpoint protection coverage
- Identify critical backups

### Medium Term (30–90 Days)
- Launch patching schedule
- Document incident response process
- Test backup restoration
- Review network exposure
- Review third-party dependencies

### Longer Term (90+ Days)
- Formalise governance documentation
- Introduce recurring control reviews
- Improve logging and monitoring maturity
- Align security controls with a recognised framework such as NIST CSF or CIS Controls