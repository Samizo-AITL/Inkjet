---
title: メーカー別インクジェット技術比較表 / Cross-Comparison Table of Inkjet Technologies
description: インクジェット主要メーカーの駆動方式・アクチュエータ構造・適合インク・用途を横断比較 / Cross-comparison of inkjet manufacturers by drive method, actuator structure, ink compatibility, and applications
---

---

# 🏭 **メーカー別インクジェット技術比較表 / Cross-Comparison Table of Inkjet Technologies**

**日本語 / Japanese**  
本ドキュメントは、主要インクジェットプリントヘッドメーカーの技術要素を一覧化した比較表です。  
駆動方式・アクチュエータ構造・適合インク・主な用途といった視点から、教育・研究・設計検討などに活用できる横断的資料を提供します。  

**English**  
This document presents a **cross-comparison of major inkjet printhead manufacturers**.  
It highlights differences in **drive method, actuator structure, ink compatibility, and applications**, providing a reference for **education, research, and design studies**.  

---

## 📊 **技術比較マトリクス / Technology Comparison Matrix**

| **メーカー / Manufacturer** | **駆動方式 / Drive Method** | **アクチュエータ構造 / Actuator Structure** | **適合インク / Compatible Inks** | **主な用途 / Applications** | **備考 / Notes** |
|----------------|-------------------|-------------------|-------------------|-------------------|-------------------|
| **EPSON** | ピエゾ（d33） / Piezo d33 | 薄膜MEMS（μTFP） | 染料／顔料／UV | 写真／商業／テキスタイル | 独自電圧制御設計（非公開） |
| **Canon** | サーマル / Thermal | 薄膜ヒーター | 染料水性中心 | オフィス／家庭 | BubbleJet方式 |
| **HP** | サーマル / Thermal | TIJ（使い捨てヒーター） | 染料／顔料 | オフィス／業務用 | 小型・簡易設計 |
| **Ricoh** | ピエゾ（d33） / Piezo d33 | MEMS高耐久型 | UV／顔料 | ラベル／産業印刷 | 中粘度対応・高耐久 |
| **Fujifilm (Dimatix)** | ピエゾ（d31） / Piezo d31 | 積層型／MEMS | UV中心 | 機能材料／研究用途 | 精密液滴制御 |
| **Konica Minolta** | ピエゾ / Piezo | バルク型 | 溶剤／顔料 | テキスタイル／ラベル | KM512/1024シリーズ |

---

## 🔍 **補足事項 / Notes**

- **d33 / d31 モード**  
  - *d33*: 電界方向と変位方向が一致（縦変位 / longitudinal mode）  
  - *d31*: 電界と垂直方向に変位（横変位 / transverse mode）  

- **薄膜 vs バルク**  
  - 薄膜MEMS型：高精度・高密度実装に有利  
  - バルク型：シンプル構造で高耐久、大型用途に適合  

- **電圧制御**  
  - 一部ヘッドでは **抗電界を超える変位を得るため電圧バイアス設計** を採用  
  - 電極構成や駆動波形は各社独自技術に依存  

---

## 📎 **関連資料リンク / Related Docs**

- 🔗 [`drive_methods.md`](./drive_methods.md) — 駆動方式と原理の比較  
- 🔗 [`ink_types.md`](./ink_types.md) — インク種類と駆動方式の適合性  
- 🔗 [`usage_fields.md`](./usage_fields.md) — 用途別技術マッピング  

---

## 📚 **参考資料 / References**

- メーカー公式カタログ：**EPSON, Canon, Ricoh, Fujifilm, HP**  
- 日本画像学会／応用物理学会誌 特集号  
- 特許文献：**JP2018-xxxxxx, US2021/xxxxxxA1**  

---

🛠️ Maintained by [Samizo-AITL](https://samizo-aitl.github.io)
