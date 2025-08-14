---
title: Inkjet Technology Archive
description: インクジェットプリントヘッド技術の比較・教育・応用のための公開情報アーカイブ | Public Archive for Inkjet Printhead Technology (Comparison, Education, Applications)
---

---

# 🖨️ **Inkjet — インクジェット技術アーカイブ / Inkjet Technology Archive**

[![Samizo-AITLポータルサイトに戻る](https://img.shields.io/badge/Samizo--AITL%20ポータルサイトに戻る-brightgreen)](https://samizo-aitl.github.io/) [![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

---

## 🔗 **公式リンク | Official Links**

| 🌐 言語 / Language | 📂 種別 / Type | 🔗 リンク / Link |
|--------------------|---------------|------------------|
| 🇯🇵 **日本語版 / Japanese Version** | 🌐 GitHub Pages | https://samizo-aitl.github.io/Inkjet/ |
| 🇯🇵 **日本語版 / Japanese Version** | 💻 GitHub | https://github.com/Samizo-AITL/Inkjet |
| 🇺🇸 **英語版 / English Version** | 🌐 GitHub Pages | https://samizo-aitl.github.io/Inkjet/en/ |
| 🇺🇸 **英語版 / English Version** | 💻 GitHub | https://github.com/Samizo-AITL/Inkjet/tree/main/en |

---

## 📜 **概要 / Overview**

**JP:** 本リポジトリは、**インクジェットプリントヘッド技術**に関する**公開情報のみ**を収集・整理した**技術アーカイブ**です。主要メーカー（**EPSON / Canon / Ricoh / Fujifilm / HP** など）の技術を横断比較し、**構造・駆動方式・インク適合性・評価手法・用途事例**から**3Dプリンティング応用**までをカバーします。  
**EN:** This repository is a **technical archive** of **publicly available knowledge** on inkjet printhead technology. It compares major manufacturers (e.g., **EPSON, Canon, Ricoh, Fujifilm, HP**) and covers **architecture, drive methods, ink compatibility, evaluation techniques, and application cases**, including **3D printing**.

> 🔎 くわしくは / See also  
> • **駆動方式の比較 / Drive Method Comparison** → `comparison/drive_methods.md`  
> • **用途分類 / Application Fields** → `comparison/usage_fields.md`  
> • **波形・インク飛翔評価 / Ink Flight Analysis** → `evaluation_tools/ink_flight_analysis.md`  
> • **薄膜ピエゾCMOS混載 / Thin-Film Piezo CMOS Integration (public case)** → `fabrication/`

---

## 📌 **特徴 / Features**

| 🎯 項目 / Item | 🇯🇵 日本語説明 / JP Description | 🇺🇸 English Description |
|---|---|---|
| 🏭 **メーカー比較** | 各社の構造・特性・用途を横断比較 | Cross-comparison of structure, features, and applications |
| ⚙️ **駆動方式** | ピエゾ・サーマル・MEMS方式の原理 | Operating principles of Piezo, Thermal, and MEMS methods |
| 💧 **インク適合性** | 水性・UV・溶剤・油性インクの適合評価 | Compatibility with aqueous, UV, solvent, and oil-based inks |
| 📊 **評価技術** | 波形解析・滴下観察・飛翔安定性評価 | Waveform analysis, droplet observation, flight stability |
| 🧪 **応用分野** | 印刷、エレクトロニクス、3Dプリント | Printing, electronics, 3D fabrication |

---

## 📁 **ディレクトリ構成 / Repository Structure**

Inkjet/  
├─ makers/ … 各社の技術・構造比較 / Maker-specific comparisons  
├─ comparison/ … 駆動方式・用途・インクの横断比較 / Cross-technology comparisons  
├─ evaluation_tools/ … 波形制御・滴下観察・評価技術 / Evaluation tools & methods  
├─ 3d_printing/ … 材料噴射型3Dプリント応用 / 3D printing applications  
├─ fabrication/ … 薄膜ピエゾCMOS混載（公開事例） / Thin-film piezo CMOS integration (public case)  
└─ README.md

---

## 🎓 **想定用途 / Intended Use**

| 用途 / Use | 説明 / Description |
|---|---|
| 🎓 **教育・研修 / Education & Training** | 原理・構造・応用を体系的に学習 / Learn principles, structures, and applications systematically |
| 🛠 **技術比較 / Technical Comparison** | メーカー・用途・インク適合性を比較 / Compare manufacturers, applications, and ink compatibility |
| 📊 **製品選定 / Product Selection** | 開発時の参考情報（波形・評価装置含む） / Reference for development (incl. waveform & equipment) |
| 🧪 **応用研究 / Applied Research** | 3Dプリント・バイオプリント等の基礎資料 / Basis for 3D/bio printing research |

---

## 🔗 **関連リポジトリ / Related Repositories**

| プロジェクト / Project | 説明 / Description |
|---|---|
| **Edusemi-v4x** → https://github.com/Samizo-AITL/Edusemi-v4x | 半導体技術教育（プロセス・設計・PDK・テスト） / Semiconductor education (process, design, PDK, test) |
| **EduMecha** → https://github.com/Samizo-AITL/EduMecha | 機械設計・Creo教材（プリントヘッド構造演習） / Mechanical design (Creo) training |
| **AITL-H** → https://github.com/Samizo-AITL/AITL-H | FSM×PID×LLMの知能制御（装置制御への応用可） / Hybrid intelligent control |
| **SamizoGPT** → https://github.com/Samizo-AITL/SamizoGPT | 教材・プロンプト設計支援 / Prompt & education support |

---

## 👤 **著者 / Author**

**三溝 真一（Shinichi Samizo）**  
- 🎓 信州大学大学院 電気電子工学 修了 / M.Eng., Electrical & Electronic Engineering, Shinshu University  
- 🏢 元 セイコーエプソン株式会社 技術者（1997–） / Former Engineer, Seiko Epson Corp.  
- 📌 専門 / Expertise: 半導体デバイス、薄膜ピエゾ、PrecisionCore製品化 / Semiconductor devices, thin-film piezo, productization

📬 **Contact:**  
✉️ shin3t72@gmail.com / 🐦 https://x.com/shin3t72 / 💻 https://samizo-aitl.github.io/

---

## 🔓 **公開方針 / Open Access Policy**

- **公開特許・論文・学会資料**などの情報のみ使用 / Only public patents, papers, and conference materials are used  
- **製品図面・量産条件等の機密情報は非掲載** / No confidential manufacturing details included  
- 機微情報は **Private リポジトリ** に分離管理 / Sensitive details stored in private repositories

---

## 🔜 **今後の計画 / Roadmap**

- [ ] 🌐 GitHub Pagesで教材展開 / Publish on GitHub Pages  
- [ ] 🧠 SamizoGPT連携 / Integrate with SamizoGPT  
- [ ] 💧 印刷現象シミュレーション資料の追加 / Add simulation docs on jetting phenomena  
- [ ] 🏗 評価装置PoCとの連携 / PoC integration with evaluation equipment

---

## 💬 **フィードバック / Feedback**

ご意見・改善案は **GitHub Discussions** へ: https://github.com/Samizo-AITL/Inkjet/discussions  
Feedback and suggestions are welcome via **GitHub Discussions**: https://github.com/Samizo-AITL/Inkjet/discussions
