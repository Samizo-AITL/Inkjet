---
title: 駆動方式の比較 / Comparison of Drive Methods  
description: サーマル方式とピエゾ方式（d31/d33）、駆動電圧・波形設計、メーカー別採用技術の比較 / Comparative overview of thermal vs piezo (d31/d33), drive voltage, waveform design, and manufacturer adoption
---

# ⚙️ **駆動方式の比較 / Comparison of Drive Methods**

**日本語 / Japanese**  
本ドキュメントでは、インクジェットプリントヘッドにおける代表的な駆動方式である **サーマル（熱方式）** と **ピエゾ方式（Piezoelectric）** の違いを整理します。  
また、ピエゾ方式内部でも **アクチュエータ構造（d31 vs d33）** の違いや、**駆動電圧・波形特性**を補足し、各社方式の理解を支援します。  

**English**  
This document compares the two main inkjet drive methods: **thermal** and **piezoelectric**.  
It also highlights classifications within piezo actuators (**d31 vs. d33**), along with notes on **driving voltages and waveform designs**,  
to support understanding of each manufacturer’s approach.  

---

## 🧪 **1. 駆動方式の原理比較 / Principle Comparison**

| 項目 / Item       | サーマル（Thermal） | ピエゾ（Piezoelectric） |
|------------------|---------------------|-------------------------|
| 駆動原理 / Principle | 抵抗体を加熱しインクを沸騰 → 気泡生成で吐出 | ピエゾ素子の変形で圧力を加えインクを押し出す |
| 主な材料 / Materials | ヒーター（TaN, HfB₂ 等） | PZT（Lead Zirconate Titanate） |
| 温度ストレス / Thermal Stress | 高（200〜300℃） | 低（常温〜小発熱） |
| インク制限 / Ink Limitations | 熱安定性が必要（水性染料中心） | 広範なインク対応（顔料／UV／溶剤等） |
| 特徴 / Features | 低コスト・高速応答 | 高精度・高信頼性・広い材料適用性 |
| 採用例 / Examples | Canon（BubbleJet）、HP（TIJ） | Epson, Ricoh, Fujifilm, Konica Minolta 等 |

---

## 🔍 **2. ピエゾ素子構造の分類 / Piezoelectric Actuator Types**

### ◽ **d31モード（横方向変位 / Lateral Deformation）**
- **構造 / Structure**: バルク積層型（旧世代ヘッドに多い）  
- **動作 / Operation**: 電界で素子が横方向に収縮 → キャビティを圧縮  
- **特徴 / Features**:  
  - 高耐久・シンプル構造  
  - 駆動電圧はやや高め（30〜40V）  
  - 応答速度は中程度  

---

### ◽ **d33モード（縦方向変位 / Vertical Deformation）**
- **構造 / Structure**: 薄膜PZT／MEMS構造（例：μTFP）  
- **動作 / Operation**: 電界で縦に伸縮し、インク室を直接圧縮  
- **特徴 / Features**:  
  - 高密度実装が可能（300〜600 dpi）  
  - 応答性・エネルギー効率に優れる  
  - 微細MEMSプロセスが必要  

---

## ⚡ **3. 駆動電圧と波形設計 / Drive Voltage & Waveform Design**

| 項目 / Item        | 内容 / Notes |
|--------------------|--------------|
| 電圧レベル / Voltage | サーマル：12〜24V<br>ピエゾ：20〜40V |
| 駆動構成 / Driving Scheme | ピエゾは複数電極間の電位差で動作を制御 |
| 波形制御 / Waveform Control | パルス幅・振幅・立ち上がり制御で吐出量を最適化 |
| 特殊設計 / Special Notes | 一部では共通電極に**オフセット電圧（負バイアス）**を与える設計を採用 |

> ⚠️ 圧電材料はヒステリシス特性を持つため、抗電界を超える駆動が必要になる場合があり、波形設計が重要。  

---

## 🏭 **4. メーカー別採用方式 / Manufacturer Adoption**

| メーカー / Manufacturer | 駆動方式 / Method | 備考 / Notes |
|-------------------------|------------------|--------------|
| **EPSON**   | ピエゾ（d33） | 薄膜PZT + MEMS構造、高応答制御方式（詳細非公開） |
| **Canon**   | サーマル | ヒーターによる気泡駆動（BubbleJet） |
| **HP**      | サーマル | TIJ（Thermal InkJet）、使い捨て設計中心 |
| **Ricoh**   | ピエゾ（d33） | MEMS型ピエゾ、高耐久設計 |
| **Fujifilm**| ピエゾ（d31/d33） | Dimatix 含む多様なモジュール構成 |

---

## 📌 **今後の拡張予定 / Planned Extensions**

- 📊 Mermaid.js による駆動方式構造図（d31 vs d33）  
- 📈 波形制御の代表例とインク応答性のマッピング  
- 🔬 ヒステリシスモデルと有効変位領域の可視化（例：PZT E-Vカーブ）  

---

## 📚 **参考資料 / References**

- 特許 / Patents: JP2018-xxxxxx, US2020/xxxxxxxA1  
- 技術論文 / Papers: 応用物理学会誌, SID 技術報告, JETRO レポート  
- メーカー資料 / Catalogs: Epson, Fujifilm, Ricoh 他  

---

🛠️ Maintained by [Samizo-AITL](https://samizo-aitl.github.io)
