---
title: Inkjet Technology Archive  
description: インクジェットプリントヘッド技術の比較・教育・応用のための公開情報アーカイブ  
---

---

# 🖨️ **Inkjet — インクジェット技術アーカイブ / Inkjet Technology Archive**

[![Samizo-AITLポータルサイトに戻る](https://img.shields.io/badge/Samizo--AITL%20ポータルサイトに戻る-brightgreen)](https://samizo-aitl.github.io/) [![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

---

## 🔗 **公式リンク | Official Links**

**🇯🇵 Japanese**  
[![🌐 GitHub Pages JP](https://img.shields.io/badge/GitHub%20Pages-日本語版-brightgreen?logo=github)](https://samizo-aitl.github.io/Inkjet/)  
[![💻 GitHub Repo JP](https://img.shields.io/badge/GitHub-日本語版-blue?logo=github)](https://github.com/Samizo-AITL/Inkjet)  

**🇺🇸 English**  
[![🌐 GitHub Pages EN](https://img.shields.io/badge/GitHub%20Pages-English-brightgreen?logo=github)](https://samizo-aitl.github.io/Inkjet/en/)  
[![💻 GitHub Repo EN](https://img.shields.io/badge/GitHub-English-blue?logo=github)](https://github.com/Samizo-AITL/Inkjet/tree/main/en)

---

## 📌 **プロジェクト概要 / Project Overview**

**日本語 / Japanese**  
本リポジトリは、**インクジェットプリントヘッド技術に関する公開可能な情報のみ**を体系的に整理した**技術アーカイブ**です。  
EPSON・Canon・Ricoh・Fujifilm・HPなど主要メーカーの**構造・駆動方式・インク適合性・用途別評価・インク飛翔現象・3Dプリンティング応用**まで幅広くカバーしています。

**English**  
This repository is an **open technical archive** based solely on **public information** about **inkjet printhead technologies**.  
It spans **structure, drive methods, ink compatibility, application-specific evaluation, ink flight phenomena,** and **3D printing applications**, across major manufacturers such as EPSON, Canon, Ricoh, Fujifilm, and HP.

---

## 📚 **Repository Contents / コンテンツ構成**

| フォルダ / Folder | 説明（日本語 / Japanese） | Summary (English) |
|-------------------|---------------------------|-------------------|
| [`makers/`](./makers/) | 各社（Epson, Canon, Ricoh, Fujifilm, etc.）の**技術方式・ヘッド構造の比較** | Manufacturer-specific **technology & head structure comparison** |
| [`comparison/`](./comparison/) | **駆動方式・インク種・用途・解像度**の観点での**横断的比較** | Cross-technology comparison by **drive method, ink type, applications, resolution** |
| [`evaluation_tools/`](./evaluation_tools/) | **波形制御・滴下観察・評価装置**の**基礎知識と解説** | Fundamentals of **waveform control, droplet observation, evaluation tools** |
| [`3d_printing/`](./3d_printing/) | **材料噴射型3Dプリント**への**応用可能性・ヘッド適合性** | Feasibility & **head compatibility** for **material jetting 3D printing** |
| [`fabrication/`](./fabrication/) | **薄膜ピエゾCMOS混載（ラピス）事例（公開情報ベース）** | **Lapis thin-film piezo CMOS integration** (public info only) |

---

## 📁 **ディレクトリ構成 / Repository Structure**

```plaintext
Inkjet/
├─ makers/                      # 各社プリントヘッド構造の技術情報（公開情報のみ）  
│   ├─ epson/                   # Epson製プリントヘッド（MACH, μTFP等）の構造・応用情報  
│   ├─ canon/                   # Canon製（バブルジェット等）の構造・特性情報  
│   ├─ ricoh/                   # Ricoh製産業用ヘッド情報  
│   ├─ fujifilm/                # 富士フイルム製ヘッドの仕様・用途  
│   └─ hp/                      # HP製サーマル方式ヘッド情報  
│
├─ comparison/                  # メーカー横断比較資料  
│   ├─ drive_methods.md         # 駆動方式（ピエゾ・サーマル等）の比較解説  
│   ├─ usage_fields.md          # 用途別分類（商業印刷・産業用途・医療等）  
│   ├─ ink_types.md             # インク適合性（水性・溶剤・UVなど）  
│   └─ summary_table.md         # メーカー別技術特徴一覧表  
│
├─ evaluation_tools/            # 評価・観察・波形制御ツール解説  
│   ├─ waveform_control.md      # 駆動波形の最適化手法  
│   ├─ ink_flight_analysis.md   # インク飛翔安定性評価  
│   └─ equipment_list.md        # 高速カメラ・ストロボ等の評価装置一覧  
│
├─ 3d_printing/                  # 3Dプリンティング応用関連  
│   ├─ overview.md               # インクジェットAMの総覧  
│   ├─ classification.md         # 材料噴射型の分類・比較  
│   └─ inkjet_related.md         # バイオ・電子回路等の応用事例  
│
└─ README.md                     # 本ファイル（概要）
```

---

## 🔓 **公開方針 / Open Access Policy**

- **日本語**：公開特許・論文・学術資料・業界記事などの**一般公開情報**のみに基づき構成。機密情報は含みません。  
- **English**: Built only from **public patents, papers, academic references, and industry articles**. **No confidential data** is included.

---

## 🎯 **想定用途 / Intended Use**

| 用途 / Use Case | 説明（日本語 / Japanese） | Description (English) |
|------|-----------------------------|-----------------------|
| 🎓 **教育・研修 / Education & Training** | 原理・構造・応用を**体系的に学習** | Structured learning of **principles, structure, applications** |
| 🛠 **技術比較 / Technical Comparison** | メーカー別の**特性・適合性**を比較 | Compare **features & compatibilities** across makers |
| 📊 **製品選定 / Product Selection** | 設計・開発の**参考資料**（波形・評価装置含む） | Reference for **design & development** (incl. waveform & equipment) |
| 🧪 **応用研究 / Applied Research** | **3D/バイオプリント**等の研究出発点 | Starting point for **3D/bio printing** research |

---

## 📎 **関連リポジトリ / Related Repositories**

| プロジェクト名 / Project Name | GitHub Pages 🌐 | GitHub 💻 | 内容（日本語 / Japanese） | Summary (English) |
|----------------|---------------|----------------|-----------------------------|-------------------|
| **Edusemi-v4x** | [🌐](https://samizo-aitl.github.io/Edusemi-v4x/) | [💻](https://github.com/Samizo-AITL/Edusemi-v4x) | 半導体技術教育（プロセス・設計・PDK・テスト） | Semiconductor education (process, design, PDK, test) |
| **EduMecha** | [🌐](https://samizo-aitl.github.io/EduMecha/) | [💻](https://github.com/Samizo-AITL/EduMecha) | 機械設計・Creo教材（**プリントヘッド構造演習**対応） | Mechanical design & Creo training (**printhead structure exercises**) |
| **AITL-H** | [🌐](https://samizo-aitl.github.io/AITL-H/) | [💻](https://github.com/Samizo-AITL/AITL-H) | **FSM×PID×LLM**による知能制御（装置制御に応用可） | **Hybrid intelligent control** (applicable to equipment control) |
| **SamizoGPT** | [🌐](https://samizo-aitl.github.io/SamizoGPT/) | [💻](https://github.com/Samizo-AITL/SamizoGPT) | 教材・プロンプト設計支援ツール | Prompt design & learning support tool |

---

## 👤 **執筆者情報 / Author**

| 項目 / Field | 内容（日本語 / Japanese） | Content (English) |
|--------------|--------------------------|-------------------|
| **氏名 / Name** | 三溝 真一 | Shinichi Samizo |
| **学歴 / Education** | 信州大学大学院 電気電子工学 修了 | M.Eng., Electrical & Electronic Engineering, Shinshu University |
| **経歴 / Career** | セイコーエプソン株式会社 技術者（1997年〜） | Former Engineer, Seiko Epson Corp. (1997–) |
| **専門分野 / Expertise** | 半導体デバイス（ロジック・メモリ・高耐圧混載）<br>インクジェット薄膜ピエゾアクチュエータ<br>PrecisionCoreプリントヘッド製品化<br>BOM管理・ISO教育 | Semiconductor devices (logic, memory, high-voltage mixed)<br>Thin-film piezo actuators for inkjet<br>PrecisionCore printhead productization<br>BOM management & ISO training |
| **連絡先 / Contact** | ✉️ [shin3t72@gmail.com](mailto:shin3t72@gmail.com)<br>🐦 [https://x.com/shin3t72](https://x.com/shin3t72)<br>💻 [https://samizo-aitl.github.io/](https://samizo-aitl.github.io/) | ✉️ [shin3t72@gmail.com](mailto:shin3t72@gmail.com)<br>🐦 [https://x.com/shin3t72](https://x.com/shin3t72)<br>💻 [https://samizo-aitl.github.io/](https://samizo-aitl.github.io/) |

---

## 🔜 **今後の展開 / Roadmap**

- [ ] 🌐 **GitHub Pages展開 / Publish via GitHub Pages**  
- [ ] 🧠 **SamizoGPT連携 / Link with SamizoGPT**  
- [ ] 💧 **印刷現象 × 流体シミュレーション資料の追加 / Add jetting–fluid simulation docs**  
- [ ] 🏗️ **評価装置PoC連携 / PoC integration with evaluation equipment**

---

## 💬 **Discussions**

[![💬 GitHub Discussions](https://img.shields.io/badge/GitHub%20Discussions-Join%20the%20Conversation-blue?logo=github)](https://github.com/Samizo-AITL/Inkjet/discussions)  
ご意見・改善案は **Discussions** ページまでお気軽にどうぞ。  
Feedback & suggestions are welcome in **Discussions**.
