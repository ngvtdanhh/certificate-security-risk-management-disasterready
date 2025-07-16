# 🚨 Breach Response Workflow – NGO Field Data Leak

This demo outlines a structured response plan following a suspected data breach in a humanitarian mission environment. It mirrors the key steps from DisasterReady's Security Risk Management Essentials training.

---

## 🧠 Scenario

- **Incident**: A team member reports their NGO-issued laptop was stolen from a guesthouse.
- **Data Involved**: Medical records and beneficiary information stored locally
- **System**: Offline database (unencrypted), synced weekly to HQ

---

## 🪜 Response Steps

### 🟠 1. Initial Detection

- **Who**: Local field coordinator notifies HQ security focal point
- **When**: Within 2 hours of noticing the theft
- **How**: Through secure Signal app + incident template form

### 🟡 2. Immediate Containment

- Lock out the device from HQ sync server  
- Invalidate associated staff credentials  
- Notify logistics/security to recover equipment if safe

### 🔴 3. Risk Assessment

| Criteria         | Evaluation                                  |
|------------------|---------------------------------------------|
| Data Sensitivity | High – includes PII and health information  |
| Likely Exposure  | High – stored in plain text (no encryption) |
| Impact Radius    | Moderate – approx. 120 individuals           |

### 🔵 4. Communication

- **Internal**: Notify staff, regional director, and infosec manager  
- **External**: Prepare a press-safe statement (if needed)  
- **Beneficiaries**: Plan for direct in-person explanation (low-literate populations)

---

## 🛠️ 5. Remediation

- Distribute encrypted drives to field team going forward  
- Conduct emergency staff training: "Mobile Device Security 101"  
- Evaluate guesthouse lock systems and secure storage

---

## 📊 6. Post-Incident Review

- Schedule After-Action Review (AAR) within 7 days  
- Update the risk register and incident response SOPs  
- Share anonymized lessons learned with peer NGOs

---

## 💬 Key Lessons

> “In field operations, breaches aren’t just technical failures—they are human vulnerabilities that demand a compassionate and coordinated response.”

---

## 🔗 Related Frameworks

- Sphere Handbook – Data Protection Principles  
- ICRC Handbook on Data Protection in Humanitarian Action  
- ISO/IEC 27035 – Incident Response Guidelines

