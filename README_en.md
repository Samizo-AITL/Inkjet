# 🖨️ Inkjet Technology Archive

This repository provides a structured archive of **publicly available knowledge** on inkjet printhead technologies.  
It covers the principles, structural features, drive mechanisms, ink compatibility, application fields, drop ejection evaluation, and the use of inkjet in additive manufacturing, with cross-comparisons of major vendors such as EPSON, Canon, Ricoh, Fujifilm, and HP.

> 🇯🇵 日本語版はこちら → [README.md](./README.md)

---

## 📌 Project Overview

This repository organizes only **non-confidential, open-source information** about inkjet printhead technologies.  
It includes a cross-company technical comparison of structure, drive principles, ink types, application domains, and wave control strategies—useful for both educational and industrial purposes.

Topics covered include:

- Drive mechanisms (piezoelectric, thermal, MEMS, etc.)
- Ink compatibility (aqueous, solvent, UV-curable)
- Application fields (textile, packaging, electronics, bioprinting, etc.)
- Drop evaluation techniques and waveform design
- Integration with 3D printing and digital fabrication

> 🔎 For details, refer to:  
> → [Drive Mechanisms Comparison](./comparison/drive_methods.md)  
> → [Application Fields](./comparison/usage_fields.md)  
> → [Drop Ejection Evaluation](./evaluation_tools/ink_flight_analysis.md)

---

## 📁 Repository Structure

```plaintext
Inkjet/
├─ makers/                      # Vendor-specific information (publicly available only)
│   ├─ epson/
│   │   ├─ MACH/                # MACH head overview
│   │   └─ uTFP/                # uTFP structure (linked to private archive)
│   ├─ canon/
│   ├─ ricoh/
│   ├─ fujifilm/
│   └─ hp/
│
├─ comparison/                  # Cross-vendor comparisons
│   ├─ drive_methods.md         # Piezo vs. thermal vs. electrostatic principles
│   ├─ usage_fields.md          # Application categories (industrial, medical, etc.)
│   ├─ ink_types.md             # Ink compatibility: aqueous, solvent, UV, etc.
│   └─ summary_table.md         # Summary table comparing technical features
│
├─ evaluation_tools/           # Tools for drop control and observation
│   ├─ waveform_control.md      # Waveform generation and drive optimization
│   ├─ ink_flight_analysis.md   # Drop stability, velocity, diameter analysis
│   └─ equipment_list.md        # Equipment for evaluation (strobe, camera, etc.)
│
├─ 3d_printing/                # Inkjet-based additive manufacturing
│   ├─ overview.md              # General overview
│   ├─ classification.md        # Technology classification and comparison
│   └─ inkjet_related.md        # Inkjet use cases in AM (bioprinting, electronics)
│
└─ README_en.md                # This file

```

