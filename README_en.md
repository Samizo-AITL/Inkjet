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

---

## 🔓 Open Access Policy

- This repository is based on **open-source publications, patents, academic articles, and publicly accessible materials**.
- It **excludes all proprietary, confidential, or internal development data** (e.g., product drawings, process parameters).
- Confidential technical details (e.g., structural data from EPSON) are stored in the separate private archive `Private/Epson/uTFP/`.

> 🔐 Internal archive: `Private/Epson/`

---

## 🎯 Intended Use

| Purpose            | Description |
|--------------------|-------------|
| 🎓 Education        | Teaching materials to understand inkjet structure and operation |
| 🛠 Technical Analysis | Comparative review of head structures and ink compatibility |
| 📊 Product Planning | Reference for selecting heads, waveform tuning, and ink types |
| 🧪 R&D Exploration  | Use cases in 3D printing, bio-ink, and functional printing research |

---

## 🔧 Tools & Format

- Written in Markdown (compatible with Zenn / GitHub Pages)
- Uses Mermaid.js for technical diagrams and mappings
- GitHub Pages support planned → [Samizo-AITL.github.io (in progress)](https://github.com/Samizo-AITL)

> Mermaid diagram sample: [Application Fields](./comparison/usage_fields.md)

---

## 📎 Related Repositories

| Project | Description |
|---------|-------------|
| [Edusemi-v4x](https://github.com/Samizo-AITL/Edusemi-v4x) | Semiconductor education platform (design, process, test, reliability) |
| [EduMecha](https://github.com/Samizo-AITL/EduMecha) | Mechanical design tutorials with Creo, integrated with inkjet examples |
| [AITL-H](https://github.com/Samizo-AITL/AITL-H) | Hybrid intelligent control system (FSM×PID×LLM) for devices like inkjet systems |
| [SamizoGPT](https://github.com/Samizo-AITL/SamizoGPT) | Prompt toolkit for education, research, and technical design |

---

## 👤 Author Profile

**Shinichi Samizo**  
- M.S. in Electrical and Electronic Engineering, Shinshu University  
- Former R&D Engineer at Seiko Epson Corporation (1997–)

📌 **Expertise**:  
- Semiconductor devices (logic, memory, high-voltage mixed process)  
- Thin-film piezoelectric actuators  
- PrecisionCore printhead commercialization, configuration management, and technical education

📬 **Contact**  
- ✉️ Email: [shin3t72@gmail.com](mailto:shin3t72@gmail.com)  
- 🐦 X (Twitter): [https://x.com/shin3t72](https://x.com/shin3t72)  
- 💻 GitHub: [https://samizo-aitl.github.io/](https://samizo-aitl.github.io/)

---

## 🔜 Roadmap

- [ ] 📘 Public launch via GitHub Pages (Zenn-compatible)
- [ ] 🧠 Prompt integration via SamizoGPT (for material generation and comparison)
- [ ] 🖨️ Add content on fluid simulation and jetting phenomena
- [ ] 🏗️ Link to actual evaluation tools and PoC projects (image capture, automation)

---

## 💬 Feedback & Suggestions

Your ideas, corrections, and contributions are welcome!  
Please feel free to open a topic in the Discussions tab below:

👉 [💬 Go to Discussions](https://github.com/Samizo-AITL/Inkjet/discussions)

(You will need to sign in with your GitHub account to post.)

---
