# Model Risk Register — AI in Financial Services

![Framework](https://img.shields.io/badge/Framework-NIST%20AI%20RMF-navy)
![Standard](https://img.shields.io/badge/Standard-ISO%2FIEC%2042001-blue)
![Regulation](https://img.shields.io/badge/Regulation-EU%20AI%20Act%202024-darkred)

A professional Model Risk Register assessing six AI systems deployed in a 
hypothetical European bank against EU Regulation 2024/1689 (EU AI Act), 
NIST AI Risk Management Framework, and ISO/IEC 42001. 
Built using the 3 Lines of Defense (3LoD) governance model.

---

## AI Systems Assessed

| Model ID | Model Name | EU AI Act Tier |
|----------|------------|----------------|
| MOD-001 | Fraud Detection System | 🟠 High Risk |
| MOD-002 | Credit Scoring Model | 🟠 High Risk |
| MOD-003 | Biometric Identification System | 🟠 High Risk |
| MOD-004 | AML Transaction Monitoring | 🟠 High Risk |
| MOD-005 | KYC / CDD Customer Screening | 🟠 High Risk |
| MOD-006 | Customer Service Chatbot | 🟡 Limited Risk |

---

## What the Register Documents

For each AI system:

- **EU AI Act Tier:** Risk classification under EU Regulation 2024/1689
- **Inherent Risk:** Risk level before controls are applied
- **Controls in Place:** Safeguards, oversight mechanisms, and audit processes
- **Residual Risk:** Remaining risk after controls are applied
- **Model Owner:** Accountable senior role within the organisation
- **Audit Status:** Current governance and review status
- **Required Action:** Outstanding compliance obligations under applicable frameworks

---

## Regulatory Frameworks Applied

**EU AI Act (EUR-Lex 2024/1689)**  
Article 5 prohibited practices, Article 6 + Annex III high-risk obligations,
Article 50 transparency requirements, Recital 48 minimal risk guidance.

**NIST AI Risk Management Framework (AI RMF 1.0)**  
Govern, Map, Measure, and Manage functions applied to each model assessment.

**ISO/IEC 42001, AI Management Systems**  
Control requirements used to assess governance adequacy for each system.

**3 Lines of Defense (3LoD)**  
First line: business unit model owners. Second line: risk and compliance 
function. Third line: internal audit.

---

## File Structure

\```
model-risk-register-ai-banking/
│
├── Model_Risk_Register_AI_Banking.xlsx
│   ├── Cover Sheet         Methodology, author, and document metadata
│   ├── Model Risk Register Six AI systems fully assessed
│   └── Risk Rating Key     Definitions for all tiers, ratings, and statuses
│
└── README.md
\```

---

## Risk Rating Key

| Rating | Meaning |
|--------|---------|
| 🔴 High | Significant potential for harm. Immediate controls required. |
| 🟠 Medium | Moderate risk. Controls in place. Ongoing monitoring required. |
| 🟢 Low | Minimal risk. Standard monitoring applies. |

---

## Disclaimer

This is a portfolio project for professional development purposes. 
All organisations, models, and data are hypothetical. 
This register does not constitute legal or regulatory advice.

---

## Author

**Brandon Muchenje**  
AI Governance and GRC Analyst  
BCom in Law (Cum Laude) | IBM Data Science | IAPP AIGP Training  
[LinkedIn](https://www.linkedin.com/in/brandon-m-muchenje) | 
[GitHub](https://github.com/brandonmuch)

---

## Related Projects

- [EU AI Act Risk Classification Tool](https://github.com/brandonmuch/eu-ai-act-classifier)

---

## References

- [EU AI Act, EUR-Lex 2024/1689](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32024R1689)
- [NIST AI Risk Management Framework](https://www.nist.gov/artificial-intelligence)
- [ISO/IEC 42001](https://www.iso.org/standard/81230.html)
```
