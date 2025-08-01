# 比較セクション：駆動方式・用途・インク種類の技術比較

本ディレクトリでは、インクジェットプリンタ技術を構成する「駆動方式」「用途分類」「インク特性」について、  
各社技術や方式ごとの違いが明確になるよう、体系的に比較・整理しています。

---

## 📚 構成 / Structure

```plaintext
comparison/
├─ drive_methods.md      # 駆動方式の分類（熱方式 vs ピエゾ／d31・d33など）
├─ usage_fields.md       # 用途ごとの分類と技術要件
├─ ink_types.md          # 使用インクの種類・物性・適合性
└─ summary_table.md      # 上記全体を統合した比較表
```

---

## 🔍 各ファイルの概要

### 🔹 [`drive_methods.md`](./drive_methods.md)
- サーマル（熱方式）とピエゾ（圧電方式）の原理的違いを整理
- d31／d33モード、駆動電圧、波形設計の技術的背景を記述
- 各社の方式選定の傾向や背景にも触れ、比較の基礎を提供

### 🔹 [`usage_fields.md`](./usage_fields.md)
- 商業印刷／産業用途／バイオ滴下／電子配線／3Dプリントなどの分類
- 解像度・吐出量・使用材料・温度応答といった要求特性に基づき用途別に分類
- 用途から求められる駆動方式や構造要件への示唆も提示

### 🔹 [`ink_types.md`](./ink_types.md)
- 染料、顔料、UV、溶剤、導電性、バイオ液などを物性・用途ごとに整理
- 粘度・表面張力・乾燥性・インク構成とヘッド方式の関係を比較
- ピエゾ vs 熱方式での適用可能性も併せて記述

### 🔹 [`summary_table.md`](./summary_table.md)
- 上記3項目（駆動方式・用途・インク）を統合した比較表を提示
- 技術選定・製品企画・学習資料に活用できるように視覚化
- 「何に適しているか／制約は何か」を俯瞰できる技術チャート

---

## 🎯 想定用途 / Intended Use

- 駆動方式・材料・用途の違いを横断的に学習したい技術者・学生向け教材
- 製品設計時のヘッド選定／インク選定の参考資料
- 技術比較や講演資料作成のベースマテリアル

---

## 📎 関連セクション

- 🔗 [`evaluation_tools/`](../evaluation_tools/) — 波形制御やインク飛行評価に関する補完技術
- 🔗 [`3d_printing/`](../3d_printing/) — 先端用途（材料積層・バイオプリント）への応用
