---
title: Inkjet Technology Archive  
description: Open technical archive on inkjet printhead technology (structure, drive methods, ink compatibility, applications, 3D printing)
---

---

# 🖨️ **Inkjet Technology Archive**

<p align="left" style="display:flex;flex-wrap:wrap;gap:6px;margin:0;padding:0;">
  <a href="https://samizo-aitl.github.io/en/">
    <img src="https://img.shields.io/badge/Return%20to%20Samizo--AITL%20Portal-brightgreen" alt="Return to Samizo-AITL Portal">
  </a>
  <a href="../LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="MIT License">
  </a>
</p>

---

## 🔗 Official Links

| Language | GitHub Pages 🌐 | GitHub 💻 |
|----------|----------------|-----------|
| 🇺🇸 English | [![GitHub Pages EN](https://img.shields.io/badge/GitHub%20Pages-English-brightgreen?logo=github)](https://samizo-aitl.github.io/Inkjet/en/) | [![GitHub Repo EN](https://img.shields.io/badge/GitHub-English-blue?logo=github)](https://github.com/Samizo-AITL/Inkjet/tree/main/en) |
| 🇯🇵 Japanese | [![GitHub Pages JP](https://img.shields.io/badge/GitHub%20Pages-日本語版-brightgreen?logo=github)](https://samizo-aitl.github.io/Inkjet/) | [![GitHub Repo JP](https://img.shields.io/badge/GitHub-日本語版-blue?logo=github)](https://github.com/Samizo-AITL/Inkjet) |

---

## 📌 **Project Overview**

This repository is an **open technical archive** based solely on **public information** about **inkjet printhead technologies**.  
It spans **structure, drive methods, ink compatibility, application-specific evaluation, ink flight phenomena,** and **3D printing applications**, across major manufacturers such as EPSON, Canon, Ricoh, Fujifilm, and HP.

---

## 📚 **Repository Contents**

| Folder | Description |
|--------|-------------|
| [`makers/`](../makers/) | Manufacturer-specific **technology & head structure comparison** (Epson, Canon, Ricoh, Fujifilm, HP) |
| [`comparison/`](../comparison/) | Cross-technology comparison by **drive method, ink type, applications, resolution** |
| [`evaluation_tools/`](../evaluation_tools/) | Fundamentals of **waveform control, droplet observation, evaluation tools** |
| [`3d_printing/`](../3d_printing/) | Feasibility & **head compatibility** for **material jetting 3D printing** |
| [`fabrication/`](../fabrication/) | **Thin-film piezo CMOS integration** case studies (public info only) |

---

## 📁 **Repository Structure**

```plaintext
Inkjet/
├─ makers/                      # Manufacturer-specific printhead technology (public info only)
│   ├─ epson/                   # Epson MACH, μTFP structure & applications
│   ├─ canon/                   # Canon Bubble Jet structure & features
│   ├─ ricoh/                   # Ricoh industrial head specifications
│   ├─ fujifilm/                # Fujifilm head specs & applications
│   └─ hp/                      # HP thermal head information
│
├─ comparison/                  # Cross-manufacturer comparison
│   ├─ drive_methods.md         # Drive method comparison (piezo, thermal, etc.)
│   ├─ usage_fields.md          # Application classification (industrial, commercial, etc.)
│   ├─ ink_types.md             # Ink compatibility (aqueous, UV, etc.)
│   └─ summary_table.md         # Technology features summary table
│
├─ evaluation_tools/            # Evaluation, observation & waveform control tools
│   ├─ waveform_control.md      # Drive waveform optimization
│   ├─ ink_flight_analysis.md   # Ink flight stability analysis
│   └─ equipment_list.md        # Evaluation equipment list
│
├─ 3d_printing/                  # 3D printing applications
│   ├─ overview.md               # Inkjet AM overview
│   ├─ classification.md         # Material jetting classification
│   └─ inkjet_related.md         # Application examples (bio, etc.)
│
└─ README.md                     # This overview
```

---

## 🔓 **Open Access Policy**

Built only from **public patents, papers, academic references, and industry articles**.  
**No confidential data** is included.

---

## 🎯 **Intended Use**

| Use Case | Description |
|----------|-------------|
| 🎓 **Education & Training** | Structured learning of **principles, structure, applications** |
| 🛠 **Technical Comparison** | Compare **features & compatibilities** across makers |
| 📊 **Product Selection** | Reference for **design & development** (including waveform & equipment) |
| 🧪 **Applied Research** | Starting point for **3D/bio printing** research |

---

## 📎 **Related Repositories**

| Project Name | GitHub Pages 🌐 | GitHub 💻 | Summary |
|--------------|----------------|-----------|---------|
| **Edusemi-v4x** | [🌐](https://samizo-aitl.github.io/Edusemi-v4x/) | [💻](https://github.com/Samizo-AITL/Edusemi-v4x) | Semiconductor education (process, design, PDK, test) |
| **EduMecha** | [🌐](https://samizo-aitl.github.io/EduMecha/) | [💻](https://github.com/Samizo-AITL/EduMecha) | Mechanical design & Creo training (printhead structure exercises) |
| **AITL-H** | [🌐](https://samizo-aitl.github.io/AITL-H/) | [💻](https://github.com/Samizo-AITL/AITL-H) | Hybrid intelligent control (applicable to equipment control) |
| **SamizoGPT** | [🌐](https://samizo-aitl.github.io/SamizoGPT/) | [💻](https://github.com/Samizo-AITL/SamizoGPT) | Prompt design & learning support tool |

---

## 👤 **Author**

| Field | Content |
|-------|---------|
| **Name** | Shinichi Samizo |
| **Education** | M.Eng., Electrical & Electronic Engineering, Shinshu University |
| **Career** | Former Engineer, Seiko Epson Corp. (1997–) |
| **Expertise** | Semiconductor devices (logic, memory, high-voltage mixed)<br>Thin-film piezo actuators for inkjet<br>PrecisionCore printhead productization<br>BOM management & ISO training |
| **Contact** | ✉️ [Email](mailto:shin3t72@gmail.com) / 🐦 [X](https://x.com/shin3t72) / 💻 [GitHub](https://samizo-aitl.github.io/) |

---

## 🔜 **Roadmap**

- [ ] 🌐 Publish via GitHub Pages (by Q3 2025)  
- [ ] 🧠 Integrate with SamizoGPT — automatic prompt generation for technology comparison  
- [ ] 💧 Add jetting–fluid simulation materials — linked with AM simulation  
- [ ] 🏗️ PoC integration with evaluation equipment — automation of high-speed imaging & waveform control

---

## 💬 **Discussions**

[![💬 GitHub Discussions](https://img.shields.io/badge/GitHub%20Discussions-Join%20the%20Conversation-blue?logo=github)](https://github.com/Samizo-AITL/Inkjet/discussions)  
Feedback & suggestions are welcome in **Discussions**.
