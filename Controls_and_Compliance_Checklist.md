# Controls and Compliance Checklist — Completed
**Project:** Botium Toys — Internal Security Audit  
**Prepared by:** Nevin (kvnevinjoseph-ship-it)  
**Date:** 2025-11-18

---

## Executive Summary
Botium Toys currently has several high-priority security gaps: incomplete asset inventory, weak password management, lack of encryption for payment data, missing IDS/IPS monitoring, and no consistent backup/disaster recovery plan. The risk score from the supplied scope document is 8/10. The checklist below contains Yes/No answers and short recommendations for each control area.

---

## Checklist (Answers and short recommendations)

1. **Asset inventory & classification**  
   **Answer:** No  
   **Recommendation:** Create and maintain an authoritative asset inventory; classify assets by sensitivity and business impact.

2. **Access control & least privilege**  
   **Answer:** No  
   **Recommendation:** Implement role-based access, remove broad access to PII, and enforce least privilege.

3. **Password policy & centralized password management**  
   **Answer:** No  
   **Recommendation:** Enforce strong password minimums (≥8 chars, complexity), deploy centralized password management.

4. **Encryption for sensitive data (in transit & at rest)**  
   **Answer:** No  
   **Recommendation:** Encrypt cardholder data and other PII at rest and in transit using current best-practice ciphers (TLS 1.2+/AES-256).

5. **Firewall & network segmentation**  
   **Answer:** Partial  
   **Recommendation:** Review and harden firewall rules; segment network to isolate POS, DB, and administrative systems.

6. **IDS/IPS and monitoring (detective controls)**  
   **Answer:** No  
   **Recommendation:** Deploy IDS/IPS, centralize logs in a SIEM for alerting and investigation.

7. **Antivirus & endpoint protection**  
   **Answer:** Yes (present but verify coverage)  
   **Recommendation:** Ensure AV is updated, centrally managed, and monitored.

8. **Backups & disaster recovery**  
   **Answer:** No  
   **Recommendation:** Implement regular backups, verify restore processes, and formalize a DR plan.

9. **Physical security (locks, CCTV, etc.)**  
   **Answer:** Yes  
   **Recommendation:** Continue maintenance and audits of physical controls.

10. **Vendor/third-party security management**  
    **Answer:** Partial  
    **Recommendation:** Formalize vendor security requirements and review third-party compliance.

11. **Compliance (PCI/GDPR) readiness**  
    **Answer:** No  
    **Recommendation:** Perform compliance gap analysis for PCI and GDPR; remediate critical issues (payment processing, PII handling).

12. **Patch management & vulnerability management**  
    **Answer:** Partial  
    **Recommendation:** Establish scheduled patching and vulnerability scanning, prioritize critical fixes.

13. **Logging & auditing**  
    **Answer:** Partial  
    **Recommendation:** Enable and centralize logging, retain logs for investigations, and monitor for anomalies.

14. **Incident response & reporting**  
    **Answer:** No  
    **Recommendation:** Create an incident response plan with roles, playbooks, and regular tabletop exercises.

15. **Employee security training & awareness**  
    **Answer:** Partial  
    **Recommendation:** Implement regular security awareness training and role-based security training.

---

## Top Priority Recommendations (short list)
1. Build an asset inventory and classify assets.  
2. Encrypt payment and customer PII; segment the network (separate POS/DB).  
3. Deploy IDS/IPS and centralize logs into a SIEM.  
4. Implement regular backups and a tested disaster recovery process.  
5. Enforce strong password policy and use centralized password management.

---

## Conclusion
Botium Toys has a high-risk posture (Risk 8/10). Addressing the top priorities above will quickly reduce exposure and support future compliance efforts.

**Prepared by:** Nevin — kvnevinjoseph-ship-it  
**Contact:** https://www.linkedin.com/in/nevin-joseph-12b606254
