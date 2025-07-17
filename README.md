# Inkjet — インクジェット技術アーカイブ / Inkjet Technology Archive

本リポジトリは、インクジェットプリントヘッド技術に関する「公開可能な情報のみ」を対象とした、技術アーカイブ兼教材リポジトリです。  
EPSON・Canon・Ricoh・Fujifilm・HP など、各社のプリントヘッド技術を比較・分類し、構造・駆動方式・インク適合性・用途別の特徴・インク飛行評価・3Dプリンティングへの応用までを体系的に整理しています。

This repository is a structured and open-access archive focused on **publicly available knowledge** related to inkjet printhead technologies.  
It provides a comprehensive overview of drive mechanisms, application domains, ink compatibility, drop ejection evaluation tools, and extensions into 3D printing, with cross-comparisons of leading companies such as EPSON, Canon, Ricoh, Fujifilm, and HP.

---

## 📚 構成 / Repository Structure

```plaintext
Inkjet/
├─ makers/                  # 各社ディレクトリ（EPSON, Canon, Ricoh, etc.）
│   ├─ epson/
│   │   ├─ uTFP/            # 第1章〜第8章（非公開Privateにリンク）
│   │   └─ MACH/
│   └─ ricoh/, canon/, ...
│
├─ comparison/              # 駆動方式・用途・インク等の比較
│   ├─ drive_methods.md
│   ├─ usage_fields.md
│   ├─ ink_types.md
│   └─ summary_table.md
│
├─ evaluation_tools/       # インク飛行評価・波形制御・ノズル観察など
│   ├─ ink_flight_analysis.md
│   ├─ waveform_control.md
│   └─ equipment_list.md
│
├─ 3d_printing/            # 3Dプリンタ技術との関連・応用
│   ├─ overview.md
│   ├─ classification.md
│   └─ inkjet_related.md
│
└─ README.md               # 本ファイル（トップ概要）
```

---

## 🔓 公開方針 / Open Access Policy

- 本リポジトリは、**一般に公開された技術情報・学術資料・特許・記事など**をもとに構成されています。
- EPSONを含む一部詳細技術情報（製品図面、構造断面、量産条件などの**社内資料や開発ノウハウ**）は、別途非公開リポジトリ `Private/precisioncoreprinthead/` にて管理しています。
- 公開範囲と非公開範囲を厳密に分離し、教育・研究・技術比較の安全な情報ベースとして活用できるように設計しています。

This repository includes only **non-confidential, publicly available information**.  
Company-internal documents, proprietary processes, or non-disclosed data are excluded and handled separately.  
The project aims to serve as a safe and transparent knowledge base for technical comparison, education, and documentation.

---

## 🎯 想定用途 / Intended Use

- 教材／技術教育（インクジェットの全体像理解、構造・駆動方式の違い）
- 技術者向け比較分析（新規インク適合性／構造選定／評価装置選定）
- 記事・講演・Zenn展開などのベース資料
- 将来的な3Dプリンタとの融合構想の起点

---

## 🛠 使用技術 / Tools

- Markdown（Zenn互換）
- Mermaid.js（技術構造図、用途マッピング等）
- GitHub Pages対応可能（教材化に向けて拡張予定）

---

## 📩 連絡先 / Contact

作成・管理者：三溝 真一（Shinichi Samizo）  
GitHub: [Samizo-AITL](https://github.com/Samizo-AITL)  
Email: shin3t72@gmail.com

---
