---
layout: default
title: インク飛翔の可視化・評価技術 | Ink Flight Analysis and Observation
---

---

# 📷 **インク飛翔の可視化・評価技術** | **Ink Flight Analysis and Observation**

本ドキュメントでは、**インクジェットプリントヘッドから吐出される液滴挙動**を観察・評価するための技術・装置・指標を整理します。  
波形調整やインク適合性検証において、**液滴の初速・飛翔角・分裂挙動・着弾挙動**を定量的に把握することは不可欠です。  
This document organizes **technologies, equipment, and parameters** for observing and evaluating inkjet droplet flight.

---

## 🧪 **1. 評価の主要目的** | **Objectives of Evaluation**

- **波形パラメータ**（電圧・時間・立ち上がり）による吐出応答の変化を観察  
- インク種類（**粘度／表面張力**）による液滴形成挙動の違いを評価  
- **液滴初速・角度・サテライト発生**の定量化  
- **ノズル間のばらつき**や製造偏差の可視化  
- **経時変化（乾燥／劣化）**の影響把握  

---

## 📷 **2. 使用される主な観察装置** | **Observation Equipment**

| **装置／技術**            | **目的／測定内容 / Purpose**       | **備考 / Notes**             |
|---------------------------|-----------------------------------|------------------------------|
| 高速度カメラ（Strobe）    | 液滴形成〜分離〜着弾の連続観察 / High-speed droplet observation | 繰返し動作による同期観察 |
| ストロボ観察系            | 特定タイミングの静止観察 / Stroboscopic snapshot | 高繰返し精度が必要 |
| CCD＋照明系               | 全体形状・初速・飛翔方向確認 / Shape, velocity, trajectory | サイドビュー型が多い |
| 波形ジェネレータ          | 駆動電圧・パルス制御 / Drive pulse generation | ±40V対応、多ch制御 |
| モーション解析ソフト      | 液滴分裂・加速度・サテライト追跡 / Droplet & satellite tracking | Particle Tracking対応 |

---

## 🧾 **3. 観察指標とパラメータ** | **Observation Metrics**

| **指標項目 / Parameter** | **単位例 / Unit** | **意味 / Meaning** |
|---------------------------|------------------|--------------------|
| 液滴初速（Vd）            | m/s              | 吐出直後の液滴速度（例：3〜7 m/s） |
| 飛翔角（θ）               | deg              | ノズル正面からの偏向角 |
| サテライト数              | count            | 主液滴から分離した副滴の数 |
| タイミング遅延（Td）      | µs               | 波形印加から吐出までの遅れ |
| ノズル間ばらつき（Δ）     | %                | 吐出量・方向の相対ばらつき |

---

## 🧠 **4. 典型的な問題例と観察所見** | **Typical Issues & Observations**

| **観察現象 / Phenomenon** | **技術的要因例 / Possible Cause** | **対応策 / Countermeasure** |
|----------------------------|----------------------------------|-----------------------------|
| 液滴分裂（サテライト発生）| 波形立上り急峻／粘度不足 | プリパルス追加／波形緩和 |
| 飛翔角のばらつき           | ノズル加工誤差／流路汚れ | ノズル検査／クリーニング |
| 吐出遅延・不吐出           | インク粘度変化／電圧不足 | ヒーター加温／電圧再設計 |

---

## 🛠 **5. 関連評価と連携** | **Related Evaluations**

- 🔗 [`waveform_control.md`](./waveform_control.md) — 駆動波形設計と液滴応答 / Drive waveform vs droplet response  
- 🔗 [`ink_types.md`](../comparison/ink_types.md) — 粘度・表面張力の影響 / Influence of viscosity & surface tension  
- 🔗 **ノズル観察**（別セクション予定） — Nozzle structural inspection (planned)  

---

## 📚 **参考資料** | **References**

- EPSON, Fujifilm, Ricoh 技術ガイド / Technical guides  
- 実験論文：*J. Imaging Sci.*, *Japanese Journal of Applied Physics*  
- 高速度カメラメーカー資料：Photron, Keyence, Hamamatsu  
