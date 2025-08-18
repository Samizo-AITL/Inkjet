---
title: インク種類と方式別適合性 / Ink Types and Compatibility by Drive Method  
description: インクジェットで用いられるインクの種類・物性・硬化方式と、サーマル／ピエゾ方式との適合性を比較 / Classification of inkjet inks, curing methods, and compatibility with thermal vs. piezoelectric heads
---

---

# 💧 **インク種類と方式別適合性 / Ink Types and Compatibility by Drive Method**

**日本語 / Japanese**  
本ドキュメントでは、インクジェットプリントヘッドで使用されるインクの種類を整理し、それぞれの **物理的特性・硬化方式・駆動方式との適合性** を技術的に解説します。  
また、メーカーごとの採用傾向や代表製品についても記載します。  

**English**  
This document categorizes the major **ink types** used in inkjet printheads and explains their **physical properties, curing mechanisms, and compatibility with drive methods**.  
It also summarizes manufacturer adoption trends and representative products.  

---

## 📚 **1. インクの主要分類 / Main Ink Categories**

| 種類 / Type   | 主成分 / Composition | 乾燥・硬化方式 / Drying-Curing | 特徴 / Features | 主な用途 / Applications |
|---------------|-----------------------|--------------------------------|-----------------|-------------------------|
| **染料水性 / Aqueous Dye** | 水＋染料 | 吸収・蒸発乾燥 | 発色性良／耐候性やや弱／低コスト | オフィス／家庭用 |
| **顔料水性 / Aqueous Pigment** | 水＋顔料粒子 | 吸収・蒸発乾燥 | 耐候性・耐水性高／ノズル詰まりやすい | 写真／商業印刷 |
| **溶剤系 / Solvent-based** | 有機溶剤 | 蒸発乾燥 | 速乾／耐久性高／臭気あり／強溶解力 | 屋外看板／産業印刷 |
| **UV硬化型 / UV-curable** | モノマー＋光重合開始剤 | UVランプ照射 | 非吸収媒体対応／即硬化／高密着性 | ラベル／産業パネル |
| **熱可塑ワックス / Hot-melt (Thermoplastic)** | ワックス等 | 冷却固化 | 立体印刷可能／特殊用途向け | テキスタイル／3Dプリント |

---

## ⚙ **2. 駆動方式との適合性 / Compatibility with Drive Methods**

| インク種類 / Ink Type | サーマル方式 Thermal | ピエゾ方式 Piezo | コメント / Notes |
|-----------------------|----------------------|------------------|------------------|
| 染料水性 / Dye        | ◎ 安定動作 | ◎ 全方式対応 | 両方式で広く使用可能 |
| 顔料水性 / Pigment    | △ 粒子が熱に不安定 | ◎ 吐出可能（粒径注意） | サーマルでは詰まりやすい |
| 溶剤系 / Solvent      | × 発火リスク・腐食 | ◎ 材料耐性設計で使用可 | ピエゾの耐薬品性が必須 |
| UV硬化型 / UV         | × ヒーター破損 | ◎ 非加熱・高精度吐出 | UV対応PZT設計が必要 |
| 熱可塑ワックス / Hot-melt | × 熱干渉 | △ 高温対応ピエゾなら可 | 高温吐出設計が条件 |

---

## 🏭 **3. メーカー別採用傾向 / Manufacturer Adoption Trends**

| メーカー / Manufacturer | 採用インク / Ink Types | 設計方針 / Design Notes |
|-------------------------|------------------------|-------------------------|
| **EPSON** | 染料／顔料／UV | μTFPの耐インク設計により多様な液体対応 |
| **Canon** | 染料水性中心 | サーマル方式。染料安定性と発色性に最適化 |
| **HP** | 染料／顔料（水性） | 使い捨てTIJでコストと安定性を両立 |
| **Ricoh** | UV／顔料水性 | 高耐久ピエゾで産業用途に幅広く対応 |
| **Fujifilm** | UVインク中心 | MEMSピエゾとUVシステム統合設計 |
| **Konica Minolta** | 顔料／溶剤 | テキスタイル・ラベル用に強靭な耐性設計 |

---

## 🧠 **4. インク選定における設計要件 / Design Considerations**

- **粘度・表面張力調整**: 吐出安定性の確保（一般値：2〜20 mPa·s）  
- **化学安定性**: 加熱劣化・電極腐食・ゲル化への耐性  
- **乾燥・硬化特性**: 基材浸透／硬化速度／耐擦過性とのバランス  
- **粒子径管理**: ピエゾでは 1 μm 以下が目安  

---

## 📌 **参考図（追加予定） / Figures (Planned)**

- 📊 Mermaid.js による「インク種類 × 駆動方式 × メーカー」マトリクス図  
- 📈 粘度–温度特性グラフ  
- ☀️ UV硬化プロファイル例  

---

## 📚 **参考資料 / References**

- 日本画像学会誌：インクジェット特集号  
- **FujiFilm Dimatix Technical Guides**  
- **EPSON 技術カタログ**、環境対応インク特許（JP2020-xxxxxx）  

---

🛠️ Maintained by [Samizo-AITL](https://samizo-aitl.github.io)
