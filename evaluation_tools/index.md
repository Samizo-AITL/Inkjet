---
layout: default
title: evaluation_tools - 評価技術セクション | Evaluation Tools Section
---

---

# 評価技術セクション：インク飛行・波形制御・観察装置の技術整理  
# **Evaluation Tools Section: Ink Flight, Waveform Control, and Observation Systems**

本ディレクトリでは、インクジェット技術における **インク滴挙動・駆動波形・観察装置** に関する知見を整理します。  
In this directory, we compile technical knowledge related to **droplet behavior, driving waveforms, and evaluation/observation systems** in inkjet technology.  

---

## 📂 **構成 / Structure**

```plaintext
evaluation_tools/
├─ ink_flight_analysis.md   # インク飛翔挙動の観察・評価 / Ink flight & droplet behavior analysis
├─ waveform_control.md      # 駆動波形の設計と評価 / Waveform design and evaluation
└─ equipment_list.md        # 評価装置一覧 / Evaluation equipment list
```

---

## 🔍 **各ファイルの概要 / File Overview**

### 🔹 [**`ink_flight_analysis.md`**](./ink_flight_analysis.md)
- **JP**: インクの滴下挙動（速度・方向・サテライト発生）を観察・解析する技術を記載  
- **EN**: Describes methods for visualizing and analyzing droplet behavior (velocity, trajectory, satellite formation)  
- **技術要素 / Techniques**: ストロボ観察、高速カメラ、時間分解解析  

---

### 🔹 [**`waveform_control.md`**](./waveform_control.md)
- **JP**: 駆動波形の設計要素（プリチャージ・メインパルス・ダンピング）と応答の関係を整理  
- **EN**: Outlines design principles of drive waveforms (pre-charge, main pulse, damping) and their effect on droplet ejection  
- **技術要素 / Techniques**: PZT応答特性、電圧パラメータ、吐出安定性  

---

### 🔹 [**`equipment_list.md`**](./equipment_list.md)
- **JP**: インク滴下観察・物性測定・波形解析で用いられる代表的装置を列挙  
- **EN**: Lists representative instruments for droplet observation, ink property measurement, and waveform analysis  
- **装置例 / Examples**: 高速撮影装置、粘度計、圧力制御システム  

---

## 🎯 **想定用途 / Intended Use**

- **JP**: 開発・評価環境の構築指針、教育資料、トラブルシューティング用  
- **EN**: Guidance for building evaluation setups, training materials, and troubleshooting references  

---

## 📎 **関連セクション / Related Sections**

- 🔗 [**`comparison/`**](../comparison/) — 駆動方式・用途との関連 / Relation to drive methods and applications  
- 🔗 [**`3d_printing/`**](../3d_printing/) — 材料噴射型応用との接続 / Link to material jetting applications  

---

## 📚 **参考文献 / References**

- Fujifilm Dimatix Technical Reference  
- ImageXpert, JetXpert catalogues  
- *Additive Manufacturing Journal*, *Printing Technology Review*  

