---
title: 比較セクション — 駆動方式・用途・インク種類の技術比較 / Comparison Section — Drive Methods, Applications, Ink Types  
description: インクジェット技術を構成する「駆動方式」「用途」「インク種類」を体系的に比較・整理 / Systematic comparison of inkjet drive methods, application fields, and ink types
---

# 📊 **比較セクション：駆動方式・用途・インク種類の技術比較 / Comparison Section: Drive Methods, Applications, Ink Types**

**日本語 / Japanese**  
本ディレクトリでは、インクジェットプリンタ技術を構成する**「駆動方式」「用途分類」「インク特性」**について、  
各社技術や方式ごとの違いが明確になるよう、体系的に比較・整理しています。  

**English**  
This directory systematically compares **drive methods, application classifications, and ink characteristics** in inkjet printing technology,  
highlighting the differences across manufacturers and methods.  

---

## 📚 **構成 / Structure**

```plaintext
comparison/
├─ drive_methods.md      # 駆動方式の分類（熱方式 vs ピエゾ／d31・d33など） / Drive method classification (thermal vs piezo, d31/d33, etc.)
├─ usage_fields.md       # 用途ごとの分類と技術要件 / Application-specific classifications and requirements
├─ ink_types.md          # 使用インクの種類・物性・適合性 / Ink types, properties, and compatibility
└─ summary_table.md      # 全体を統合した比較表 / Integrated comparison table
```

---

## 🔍 **各ファイルの概要 / File Overviews**

### 🔹 [**drive_methods.md**](./drive_methods.md)
- サーマル（熱方式）とピエゾ（圧電方式）の**原理的違い**を整理  
- **d31／d33モード、駆動電圧、波形設計**の技術的背景を記述  
- 各社の方式選定の傾向や背景に触れ、比較の基礎を提供  
➡️ Summarizes **thermal vs. piezo principles**, drive modes (d31/d33), driving voltages, waveform design, and manufacturer trends.  

---

### 🔹 [**usage_fields.md**](./usage_fields.md)
- **商業印刷／産業用途／バイオ滴下／電子配線／3Dプリント**などの分類  
- 解像度・吐出量・材料特性・温度応答といった**要求性能ごとに整理**  
- 用途から駆動方式や構造要件への示唆を提示  
➡️ Classifies applications (commercial, industrial, bio, electronics, 3D printing) with **performance requirements** and **implications for drive/structure choices**.  

---

### 🔹 [**ink_types.md**](./ink_types.md)
- **染料・顔料・UV・溶剤・導電性・バイオ液**を物性・用途ごとに整理  
- **粘度・表面張力・乾燥性**とヘッド方式との関係を比較  
- ピエゾ vs サーマルでの**適用可能性**を併記  
➡️ Organizes **dye, pigment, UV, solvent, conductive, bio-inks** by properties and applications; compares suitability for piezo vs. thermal heads.  

---

### 🔹 [**summary_table.md**](./summary_table.md)
- 駆動方式・用途・インクを**統合的に整理した比較表**を提示  
- 技術選定・製品企画・教育用資料に活用可能  
- **適用分野／制約**を一目で把握できる技術チャート  
➡️ Provides an **integrated comparative table** for drive methods, applications, and inks — a quick-reference **technology chart** for design, planning, and education.  

---

## 🎯 **想定用途 / Intended Use**

- 🎓 **教育・学習 / Education & Training**  
  技術者・学生が **駆動方式・材料・用途の違い**を横断的に学ぶ教材  
  Learning resource for engineers and students to study differences across **methods, materials, and applications**  

- 🛠 **設計支援 / Design Reference**  
  製品設計時の **ヘッド選定／インク選定** の参考資料  
  Reference for **head and ink selection** during product design  

- 📊 **技術比較・講演資料 / Technical & Presentation Material**  
  技術比較や講演資料作成のベースとして活用  
  Base material for **comparative analysis and technical presentations**  

---

## 📎 **関連セクション / Related Sections**

- 🔗 [**evaluation_tools/**](../evaluation_tools/) — 波形制御やインク飛行評価に関する補完技術  
  Complementary technologies for **waveform control and ink flight evaluation**  

- 🔗 [**3d_printing/**](../3d_printing/) — 材料積層やバイオプリントなど先端用途  
  Advanced applications such as **additive manufacturing and bioprinting**  

---

🛠️ Maintained by [Samizo-AITL](https://samizo-aitl.github.io)
