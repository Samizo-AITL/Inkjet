---
layout: default
title: インクジェット評価装置一覧 | Inkjet Evaluation Equipment List
---

---

# 🧪 **インクジェット評価装置一覧** | **Inkjet Evaluation Equipment List**

本ドキュメントでは、**インクジェットプリントヘッドの開発・評価**に使用される代表的な装置を分類・整理します。  
波形制御／液滴観察／流路可視化／印字検査など、幅広い測定項目に対応した装置群を掲載します。  
This document organizes representative equipment used in **inkjet printhead development and evaluation**, covering waveform control, droplet observation, flow channel visualization, and printing inspection.

---

## 🔍 **1. 駆動・波形制御装置** | **Drive & Waveform Control**

| **装置名／分類** | **主な用途 / Use**              | **備考 / Notes**            |
|------------------|---------------------------------|-----------------------------|
| 波形ジェネレータ | 任意電圧波形の印加 / Arbitrary waveform generation | ±40V対応、多ch制御可 / Supports ±40V, multi-channel |
| パルスドライバ   | 定型パルスの高精度出力 / Precision pulse driving | MEMS駆動向け最適化 / Optimized for MEMS heads |
| 電圧・電流モニタ | 動作中の電気信号波形取得 / Monitoring voltage & current | 高速サンプリング対応 / High-speed sampling |

---

## 📷 **2. インク飛翔観察・可視化系** | **Ink Flight Observation & Visualization**

| **装置名 / Equipment** | **主な機能 / Function**        | **備考 / Notes**             |
|-------------------------|--------------------------------|-------------------------------|
| 高速度カメラ            | 液滴形成・飛翔観察 / Droplet flight analysis | Photron / Keyenceなど |
| ストロボ照明＋CCD       | 同期静止観察 / Stroboscopic synchronized imaging | 液滴位置確認 / Position check |
| モーション解析ソフト    | サテライト追跡・速度計測 / Satellite & velocity tracking | Particle tracking対応 |

---

## 🖨 **3. 印字／吐出後の観察装置** | **Post-Ejection & Print Observation**

| **装置名 / Equipment**   | **用途 / Application**            | **備考 / Notes**                  |
|---------------------------|-----------------------------------|-----------------------------------|
| 受像センサ（ラインセンサ）| 濃度・ブリード測定 / Density & bleed check | 画像処理ソフト連携 / Image processing |
| 画像検査システム           | ドット形状観察 / Dot shape inspection     | AI検査対応 / AI inspection ready   |
| 位置ズレ計測系             | 印字精度測定 / Printing accuracy evaluation | XYθ誤差測定 / XYθ deviation check |

---

## 🧪 **4. 流路可視化・構造観察装置** | **Flow Path & Structural Observation**

| **装置名 / Equipment** | **用途 / Application**             | **備考 / Notes**           |
|-------------------------|------------------------------------|-----------------------------|
| X線CT装置              | 内部流路・接合観察 / Non-destructive internal inspection | 吐出不良解析 / Defect analysis |
| 実体顕微鏡              | ノズル加工・断面観察 / Nozzle surface & cross-section | 切断サンプル併用 / Cross-section prep |
| レーザー干渉計          | 液膜・吐出タイミング観察 / Film & timing observation | MEMS向け / For MEMS |

---

## 📦 **5. 評価プラットフォーム例** | **Integrated Evaluation Platforms**

| **名称 / Platform**     | **構成 / Configuration**         | **対応機能 / Functions**           |
|--------------------------|----------------------------------|------------------------------------|
| 富士フイルム JetXpert   | 波形印加＋飛翔観察＋印字確認 / Waveform + Flight + Print | 一体型計測ソリューション / Integrated system |
| 自社開発評価ベンチ       | 波形回路＋カメラ＋Z軸制御 / Custom electronics + Camera + Z-axis | プロト評価・低コスト対応 / Prototyping |

---

## 📚 **参考資料・関連リンク** | **References & Related Links**

- 🔗 [`waveform_control.md`](./waveform_control.md) — 駆動波形の設計・評価 / Drive waveform design & evaluation  
- 🔗 [`ink_flight_analysis.md`](./ink_flight_analysis.md) — 液滴飛翔の評価技術 / Droplet flight analysis  
- 各社装置メーカー資料：Photron, Keyence, Hamamatsu, Fujifilm 等 / Official equipment catalogs  
