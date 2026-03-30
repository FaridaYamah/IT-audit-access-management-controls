# IT Audit project: Access Management & Change Controls Review

IT Audit Portfolio - Access Management & Change Controls

## 👩🏽‍💻 Author

**Farida Yamah
Data Analyst → IT Audit & GRC 

🔗 [View My LinkedIn Profile](https://www.linkedin.com/in/farida-yamah-97a29123b)

 
 This project simulates an IT General Controls (ITGC) audit of Access Management and Change Management within a critical ERP environment. focusing on identifying control deficiencies, assessing risk exposure, and recommending remediation actions.

---

## 🔍 Executive Summary

- ✅ 12 ITGC controls tested across User Provisioning, Modifications, and Terminations
- ✅ Achieved 99% role-to-access alignment
- ✅ Reduced emergency change deployments by 60%
- ❌ Identified control deficiencies
    -  missing approvals
    -  Delayed user termination
    -  inappropriate
    -   role assignments
- 🛠️ Supporting artifacts include
      - Risk & Control Matrix (RCM)
      - Audit report
      - Testing workbook
      - Risk Heatmap

---

## 🎯 Scope & Objectives

**System Audited:** Critical ERP System  
**Audit Period:** Oct 2024 – Oct 2025  

**Objective:**  
Evaluate access management controls across:
- User Provisioning
- User Modification
- User Termination

Ensure access is granted, modified, and removed in accordance with the organization's Access Management Policy and SOX ITGC expectations.

---

## 🧪 Methodology

- Conducted walkthrough with process owners to understand control design
- Reviewed Access Management Policies and provisioning workflows
- Selected a sample of users for testing provisioning, modification, and termination controls
- Performed: 
    -Test of Design (TOD) 
     -Test of Operating Effectiveness (TOE)
- Inspected audit evidence including:
  - Approval emails
  - Ticketing system logs
  - HR termination records
  - Active Directory extracts

---

## 🚨 Key Findings

1. ❌ **Missing Approval Evidence**  
   - **Risk Rating:** High  
   - **Impact:** Unauthorized access may be granted without proper management oversight
   - **Recommendation:** Enforce mandatory approval workflows before provisioning access

2. ❌ **Late Terminations**  
   - **Risk Rating:** High  
   - **Impact:** Delayed removal of system access for terminated employees increases the risk of unauthorized access and potential data misuse.
   - **Recommendation** Implement automated HR-IT integration to ensure user access is revoked within 24 Hours of termination.

3. ❌ **Incorrect Role Assignments**  
   - **Risk Rating:** Medium  
   - **Impact:** Misaligned user roles may result in excessive access privilieges, increasing the risk of segregation of duties (SOD) conflicts and unauthorized activities.
   - **Recommendation** Enforce role-based access controls (RBAC) and validate user access against approval job functions and role matrices.

4. ✅ **Change Requests Fully Approved and Documented**  
   - **Risk Rating:** Low (Effective Control)
   - **Observation** All sampled change requests were properly approved and supported with adequate documentation.
   - **Conclusion** Control is operating effectively with no exceptions noted.

---

## 📂 Repository Structure

| File | Description |
|------|-------------|
| 📄 `Access Management Audit Report.docx` | Final audit report summarizing findings and recommendations |
| 📊 `Access Management RCM.xlsx` | Risk & Control Matrix mapping risks to controls and test procedures |
| 📈 `Risk Matrix.pdf` | Risk heatmap showing severity and prioritization |
| 🧪 `Test Workbook.xlsx` | Detailed testing results (pass/fail with evidence) |
| 📁 `Evidence/` | (Optional) Sample redacted tickets, approvals, HR exports |

## 👩‍💻 About the Auditor

Hi, I'm **Farida Yamah** — a Data Analyst transitioning into IT Audit & GRC. I leverage data analytics to perform control testing, identify risks, and support audit conclusions aligned with SOX and internal control frameworks. 

📫 [LinkedIn](https://www.linkedin.com/in/farida-yamah-97a29123b) 

---

