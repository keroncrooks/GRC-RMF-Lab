[README.md](https://github.com/user-attachments/files/20725948/README.md)

# RMF-Based Third Party Risk Management Lab

This GitHub lab simulates a third-party cybersecurity risk management process modeled after NIST RMF (Risk Management Framework) principles. It walks through a full lifecycle: from impact categorization to risk tracking, remediation, control implementation, and process automation.

---

## 📁 Included Files (In Workflow Order)

### 1. `FIPS199_Only.csv`
Establishes the foundation for all risk decisions by categorizing information types according to FIPS 199 (Confidentiality, Integrity, Availability). Each row includes a rationale and example for its impact rating, which guides all follow-on control selection and risk analysis.

### 2. `Risk_Register_Only.csv`
Captures individual risk entries tied to third-party activities, SIG responses, or control gaps. Fields include risk level, description, mitigation strategy, and ownership — enabling prioritization and integration into ongoing reviews.

### 3. `POAM_RMF_GRC_Lab.csv`
Maps risks from the register into active remediation plans. Includes target resolution dates, responsible parties, and current status. Useful for governance meetings, audit trails, and tracking open control gaps.

### 4. `Control_Implementation_Table_RMF_Lab.csv`
Maps selected and tailored NIST 800-53 controls to the categorized system. Shows implementation rationale, control owners, and supporting evidence. Useful for SSP development or ATO preparation.

### 5. `IRS_Third_Party_Risk_Workflow_Automation_Template.csv`
Outlines a proposed automated workflow for third-party intake and assessment using tools like SharePoint, Power Automate, or ServiceNow. Focuses on automating intake, tiering, document requests, and reminders to reduce manual burden and improve consistency.

---

## ✅ Purpose of This Lab

- Demonstrate how to implement a GRC-aligned third-party risk workflow from start to finish.
- Showcase familiarity with FIPS 199, NIST 800-53, POA&M handling, and automation planning.
- Simulate work typical of roles supporting FedRAMP, CMMC, or enterprise-level RMF programs.

---

## 📌 Frameworks & Standards Used

- NIST SP 800-53 Rev. 5
- NIST SP 800-30
- FIPS 199
- RMF (Risk Management Framework)
- POA&M documentation standards (FedRAMP-style)

---

## 🧠 Key Skills Demonstrated

- FIPS 199 impact categorization with rationale
- Risk register creation and risk-to-control traceability
- POA&M documentation and remediation tracking
- NIST control selection and tailoring
- Automation design for third-party workflows
- Evidence preparation for audits and ATOs

---

## 🗂️ For Reviewers

This lab is a simulation and does not reflect real vendor data. It is designed to showcase initiative, practical RMF alignment, and documentation quality expected in GRC-focused roles.

