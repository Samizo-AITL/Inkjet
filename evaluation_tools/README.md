# 評価技術セクション：インク飛行・波形制御・観察装置の技術整理

本ディレクトリでは、インクジェット技術における**インク滴の挙動・駆動波形・評価装置**に関する技術的知見を整理します。  
プリントヘッド開発やインク適合性評価、応用用途への展開において、これらの技術は不可欠です。

---

## 📂 構成 / Structure

```plaintext
evaluation_tools/
├─ ink_flight_analysis.md   # インク飛翔・滴下挙動の観察と評価技術
├─ waveform_control.md      # 駆動波形の設計・調整とその評価手法
└─ equipment_list.md        # 観察・測定・評価に使用される主要装置一覧
```

---

## 🔍 各ファイルの概要

### 🔹 [`ink_flight_analysis.md`](./ink_flight_analysis.md)
- インクの滴下挙動（速度・飛行方向・サテライトの有無など）を可視化・測定する技術を紹介
- ストロボ観察、高速カメラ、フェーズドライブ制御による時間分解観察などを記述
- 各評価指標（初速・分離角・安定性指数）と、観察結果の評価方法を整理

### 🔹 [`waveform_control.md`](./waveform_control.md)
- 駆動波形の設計要素（プリチャージ・メインパルス・ダンピング）と電圧制御の基本を記述
- ピエゾアクチュエータへの電気入力と吐出応答の関係を整理し、波形設計の原則を解説
- 社内表現を用いず、一般的原理ベースで安全に記述

### 🔹 [`equipment_list.md`](./equipment_list.md)
- 滴下観察、インク物性測定、波形解析などに使用される装置の代表例を列挙
- ストロボスコープ、高速撮影装置、インク粘度計、リザーバ圧力制御装置などを分類
- 各装置の用途と評価項目との関係を明確化し、実験設計の参考にできるよう整理

---

## 🎯 想定用途 / Intended Use

- プリントヘッド開発やインク評価における試験環境構築のガイドとして
- 波形設計やインク適合性の教育資料（社内技術者・学生向け）として
- 出力不良や吐出不安定時のトラブルシューティング資料としても活用可能

---

## 📎 関連セクション

- 🔗 [`comparison/`](../comparison/) — 駆動方式・用途分類と密接に関連
- 🔗 [`3d_printing/`](../3d_printing/) — 材料噴射型の精密制御応用との接続

---

## 📚 参考文献

- Fujifilm Dimatix Technical Reference  
- 各種滴下観察装置カタログ（ImageXpert, JetXpert, オプテックスなど）  
- Additive Manufacturing Journal, Printing Technology Review
