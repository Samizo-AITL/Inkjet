---
title: Inkjet Technology Archive  
description: Inkjet printhead technology archive (structure, drive methods, ink compatibility, applications, 3D printing)
---

---

# 🖨️ **Inkjet — Inkjet Technology Archive**

<p align="left" style="display:flex;flex-wrap:wrap;gap:6px;margin:0;padding:0;">
  <a href="https://samizo-aitl.github.io/">
    <img src="https://img.shields.io/badge/Back%20to%20Samizo--AITL%20Portal-brightgreen" alt="Back to Samizo-AITL portal">
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="MIT License">
  </a>
</p>

---

## 🔗 Official Links

| Language | GitHub Pages 🌐 | GitHub 💻 |
|----------|----------------|-----------|
| 🇯🇵 Japanese | [![GitHub Pages JP](https://img.shields.io/badge/GitHub%20Pages-Japanese-brightgreen?logo=github)](https://samizo-aitl.github.io/Inkjet/) | [![GitHub Repo JP](https://img.shields.io/badge/GitHub-Japanese-blue?logo=github)](https://github.com/Samizo-AITL/Inkjet) |
| 🇺🇸 English | [![GitHub Pages EN](https://img.shields.io/badge/GitHub%20Pages-English-brightgreen?logo=github)](https://samizo-aitl.github.io/Inkjet/en/) | [![GitHub Repo EN](https://img.shields.io/badge/GitHub-English-blue?logo=github)](https://github.com/Samizo-AITL/Inkjet/tree/main/en) |

---

## 📌 **Project Overview**

**English**  
This repository is an **open technical archive** based solely on **public information** about **inkjet printhead technologies**.  
It covers **structure, drive methods, ink compatibility, application-specific evaluation, ink flight phenomena,** and **3D printing applications**, across major manufacturers such as EPSON, Canon, Ricoh, Fujifilm, and HP.

**Japanese**  
本リポジトリは、**インクジェットプリントヘッド技術に関する公開可能な情報のみ**を体系的に整理した**技術アーカイブ**です。  
EPSON・Canon・Ricoh・Fujifilm・HPなど主要メーカーの**構造・駆動方式・インク適合性・用途別評価・インク飛翔現象・3Dプリンティング応用**まで幅広くカバーしています。

---

## 📚 **Repository Contents**

| Folder | Description (Japanese) | Summary (English) |
|--------|------------------------|-------------------|
| 📂 **makers/**  
[![View Site](https://img.shields.io/badge/view-Site-green)](https://samizo-aitl.github.io/Inkjet/makers/) [![View Repo](https://img.shields.io/badge/view-Repo-blue)](https://github.com/Samizo-AITL/Inkjet/tree/main/makers) | 各社（Epson, Canon, Ricoh, Fujifilm, HP）の**技術方式・構造比較** | Technology & structure comparison for each manufacturer |
| 📂 **comparison/**  
[![View Site](https://img.shields.io/badge/view-Site-green)](https://samizo-aitl.github.io/Inkjet/comparison/) [![View Repo](https://img.shields.io/badge/view-Repo-blue)](https://github.com/Samizo-AITL/Inkjet/tree/main/comparison) | **駆動方式・インク種・用途・解像度**による横断比較 | Cross-comparison by **drive method, ink type, applications, resolution** |
| 📂 **evaluation_tools/**  
[![View Site](https://img.shields.io/badge/view-Site-green)](https://samizo-aitl.github.io/Inkjet/evaluation_tools/) [![View Repo](https://img.shields.io/badge/view-Repo-blue)](https://github.com/Samizo-AITL/Inkjet/tree/main/evaluation_tools) | **波形制御・滴下観察・評価装置**の基礎と解説 | Basics of **waveform control, droplet observation, evaluation equipment** |
| 📂 **3d_printing/**  
[![View Site](https://img.shields.io/badge/view-Site-green)](https://samizo-aitl.github.io/Inkjet/3d_printing/) [![View Repo](https://img.shields.io/badge/view-Repo-blue)](https://github.com/Samizo-AITL/Inkjet/tree/main/3d_printing) | **材料噴射型3Dプリント**の応用・適合性 | Application & compatibility for **material jetting 3D printing** |
| 📂 **fabrication/**  
[![View Site](https://img.shields.io/badge/view-Site-green)](https://samizo-aitl.github.io/Inkjet/fabrication/) [![View Repo](https://img.shields.io/badge/view-Repo-blue)](https://github.com/Samizo-AITL/Inkjet/tree/main/fabrication) | **薄膜ピエゾCMOS混載事例**（公開情報ベース） | **Thin-film piezo CMOS integration** case studies (public info only) |

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
├─ 3d_printing/                 # 3D printing applications
│   ├─ overview.md              # Inkjet AM overview
│   ├─ classification.md        # Material jetting classification
│   └─ inkjet_related.md        # Application examples (bio, etc.)
│
└─ README.md                    # This overview
```

---

## 🔓 **Open Access Policy**

- **English**: Built only from **public patents, papers, academic references, and industry articles**. **No confidential data** is included.  
- **Japanese**: 公開特許・論文・学術資料・業界記事などの**一般公開情報**のみに基づき構成。機密情報は含みません。  

---

## 🎯 **Intended Use**

| Use Case | Description (English) | 説明（日本語 / Japanese） |
|----------|-----------------------|---------------------------|
| 🎓 **Education & Training** | Structured learning of **principles, structure, applications** | 原理・構造・応用を体系的に学習 |
| 🛠 **Technical Comparison** | Compare **features & compatibilities** across makers | メーカー別の特性・適合性を比較 |
| 📊 **Product Selection** | Reference for **design & development** (incl. waveform & equipment) | 設計・開発の参考資料（波形・評価装置含む） |
| 🧪 **Applied Research** | Starting point for **3D/bio printing** research | 3D/バイオプリント等の研究出発点 |

---

## 📎 **Related Repositories**

| Project Name | Links | Summary (English) | 内容（日本語 / Japanese） |
|--------------|-------|-------------------|---------------------------|
| **Edusemi-v4x** | [![View Site](https://img.shields.io/badge/view-Site-green)](https://samizo-aitl.github.io/Edusemi-v4x/) [![View Repo](https://img.shields.io/badge/view-Repo-blue)](https://github.com/Samizo-AITL/Edusemi-v4x) | Semiconductor education (process, design, PDK, test) | 半導体技術教育（プロセス・設計・PDK・テスト） |
| **EduMecha** | [![View Site](https://img.shields.io/badge/view-Site-green)](https://samizo-aitl.github.io/EduMecha/) [![View Repo](https://img.shields.io/badge/view-Repo-blue)](https://github.com/Samizo-AITL/EduMecha) | Mechanical design & Creo training (printhead structure exercises) | 機械設計・Creo教材（プリントヘッド構造演習対応） |
| **AITL-H** | [![View Site](https://img.shields.io/badge/view-Site-green)](https://samizo-aitl.github.io/AITL-H/) [![View Repo](https://img.shields.io/badge/view-Repo-blue)](https://github.com/Samizo-AITL/AITL-H) | Hybrid intelligent control (equipment control capable) | FSM×PID×LLMによる知能制御（装置制御応用可） |
| **SamizoGPT** | [![View Site](https://img.shields.io/badge/view-Site-green)](https://samizo-aitl.github.io/SamizoGPT/) [![View Repo](https://img.shields.io/badge/view-Repo-blue)](https://github.com/Samizo-AITL/SamizoGPT) | Prompt design & learning support tool | 教材・プロンプト設計支援ツール |

---

## 👤 **Author**

| Item | Details |
|------|---------|
| **Name** | Shinichi Samizo |
| **Education** | Master, Electrical & Electronic Engineering, Shinshu University |
| **Career** | Former Seiko Epson Corporation engineer (1997–) |
| **Expertise** | Semiconductor devices (logic, memory, high-voltage integration)<br>Inkjet thin-film piezo actuators<br>PrecisionCore printhead productization, BOM management, ISO training |
| **Contact** | ✉️ [Email](mailto:shin3t72@gmail.com) / 🐦 [X](https://x.com/shin3t72) / 💻 [GitHub](https://samizo-aitl.github.io/) |

---

## 🔜 **Roadmap**

- [ ] 🌐 **GitHub Pages deployment** — Public by Q3 2025  
- [ ] 🧠 **SamizoGPT integration** — Add automatic generation of technical comparison prompts  
- [ ] 💧 **Printing phenomena × fluid simulation materials** — Linked with AM simulation  
- [ ] 🏗️ **Evaluation equipment PoC integration** — Automation of high-speed imaging & waveform control  

---

## 💬 **Discussions**

[![💬 GitHub Discussions](https://img.shields.io/badge/GitHub%20Discussions-Join%20the%20Conversation-blue?logo=github)](https://github.com/Samizo-AITL/Inkjet/discussions)  
Feedback & suggestions are welcome in **Discussions**.  
ご意見・改善案は **Discussions** ページまでお気軽にどうぞ。
