# 🖨️ **Inkjet — インクジェット技術アーカイブ / Inkjet Technology Archive**

本リポジトリは、**インクジェットプリントヘッド技術に関する公開可能な情報のみ**を体系的に整理した**技術アーカイブ**です。  
**EPSON・Canon・Ricoh・Fujifilm・HP** など主要メーカーのプリントヘッド技術を横断的に分析し、  
**構造・駆動方式・インク適合性・用途別評価・インク飛行現象・3Dプリンティング応用**まで幅広くカバーしています。

> 🌐 **英語版はこちら →** [**English version / README_en.md**](./README_en.md)

---

## 📌 **プロジェクト概要 / Project Overview**

本リポジトリは、**インクジェットプリントヘッドに関する公開情報のみ**を対象とし、  
**構造・駆動方式・インク適合性・用途・評価手法・3Dプリンティング応用**までを横断的に整理した**技術アーカイブ**です。  
**EPSON・Canon・Ricoh・Fujifilm・HP** など、主要メーカーの**技術比較**も含み、**教育・研究・製品開発**の基礎資料として活用できます。

This archive is structured around **publicly available knowledge** of inkjet printhead technologies,  
including **drive mechanisms** (piezo, thermal, MEMS), **ink compatibility** (aqueous, UV, solvent),  
**evaluation methods**, and **application fields** such as **printing**, **electronics**, and **3D fabrication**.

> 🔎 **詳細な比較・評価内容は以下をご参照ください：**  
> → [**駆動方式の比較 / drive_methods.md**](./comparison/drive_methods.md)  
> → [**用途分類 / usage_fields.md**](./comparison/usage_fields.md)  
> → [**波形・インク飛翔評価 / ink_flight_analysis.md**](./evaluation_tools/ink_flight_analysis.md)

---

## 📁 **ディレクトリ構成 / Repository Structure**

```plaintext
Inkjet/
├─ makers/                      # 各社プリントヘッド構造の技術情報（公開情報のみ）
│   ├─ epson/
│   │   ├─ MACH/                # Machヘッド（構造・応用・資料リンク）
│   │   └─ uTFP/                # μTFP構造（※詳細は非公開リポジトリに格納）
│   ├─ canon/
│   ├─ ricoh/
│   ├─ fujifilm/
│   └─ hp/
│
├─ comparison/                  # 比較資料（駆動方式・用途・インク等）
│   ├─ drive_methods.md         # ピエゾ・サーマル・電気熱方式などの原理比較
│   ├─ usage_fields.md          # 用途別分類（産業・商業・医療等）
│   ├─ ink_types.md             # 水性／溶剤／UV／油性等のインク適合性
│   └─ summary_table.md         # メーカー別比較表（技術特徴の一覧）
│
├─ evaluation_tools/           # 波形制御・ノズル観察・インク飛行評価ツール
│   ├─ waveform_control.md      # 波形生成・駆動方式の最適化手法
│   ├─ ink_flight_analysis.md   # 飛翔安定性・液滴径・速度分布などの評価技術
│   └─ equipment_list.md        # 高速カメラ・ストロボ装置・観察ツール一覧
│
├─ 3d_printing/                # 3Dプリンティング・積層造形への応用
│   ├─ overview.md              # インクジェット×AMの総覧
│   ├─ classification.md        # 材料噴射型との比較・分類
│   └─ inkjet_related.md        # プリントヘッド応用事例（バイオ・電子回路等）
│
└─ README.md                   # 本ファイル（トップ概要）
```

---

## 🔓 **公開方針 / Open Access Policy**

- 本リポジトリは、**公開特許・論文・学術資料・業界記事**などの**一般公開情報**に基づき構成されています。  
- 一方で、**製品図面・社内プロセス・量産条件・解析結果等の機密情報は一切含みません**。  
- 一部、詳細技術情報は `Private/Epson/uTFP/` 等の**非公開領域**に分離して管理しています。

> 🔐 **For internal archives (Epson-specific), see →** `Private/Epson/`

---

## 🎯 **想定用途 / Intended Use**

| 用途 | 説明 |
|------|------|
| 🎓 **教育・研修** | インクジェット技術の**原理・構造・応用**を体系的に理解する教材として活用可能 |
| 🛠 **技術比較** | メーカーごとの**プリントヘッド特性・インク適合性・用途適合**を比較検討 |
| 📊 **製品選定** | 製品設計や応用開発の際の**参考情報**として活用（**波形制御や評価装置選定**含む） |
| 🧪 **応用研究** | **3Dプリンティング・バイオプリンティング・機能性インク開発**などの研究出発点 |

---

## 🔧 **使用技術・記述形式 / Tools & Format**

- **Markdown**（Zenn / GitHub Pages 両対応）  
- **Mermaid.js**（構造図・用途マッピング視覚化）  
- 対応予定：GitHub Pages → [**Samizo-AITL.github.io（構想中）**](https://github.com/Samizo-AITL)

> 📊 Mermaid例 → [**用途分類 / usage_fields.md**](./comparison/usage_fields.md)

---

## 📎 **関連リポジトリ / Related Repositories**

| プロジェクト名 | 内容 |
|----------------|------|
| [**Edusemi-v4x**](https://github.com/Samizo-AITL/Edusemi-v4x) | 半導体技術教育教材（プロセス設計・テスト・信頼性など） |
| [**EduMecha**](https://github.com/Samizo-AITL/EduMecha) | 機械設計・Creo教材。**プリントヘッド構造との統合演習**に対応 |
| [**AITL-H**](https://github.com/Samizo-AITL/AITL-H) | **FSM×PID×LLMによる知能制御**。インクジェット装置制御にも応用可能 |
| [**SamizoGPT**](https://github.com/Samizo-AITL/SamizoGPT) | 教材・プロンプト設計の**統合支援ツール**（Zenn展開支援予定） |

---

## 👤 **執筆者情報 / Author**

**三溝 真一（Shinichi Samizo）**  
- 信州大学大学院 **電気電子工学 修了**  
- 元 **セイコーエプソン株式会社 技術者（1997年〜）**

📌 **経験領域：**  
- **半導体デバイス（ロジック／メモリ／高耐圧混載）**  
- **薄膜ピエゾアクチュエータ**  
- **PrecisionCoreプリントヘッド製品化・構成管理・教育設計**

📫 [**GitHub: Samizo-AITL**](https://github.com/Samizo-AITL)  
📩 Email: [shin3t72@gmail.com](mailto:shin3t72@gmail.com)

---

## 🔜 **今後の展開 / Roadmap**

- [ ] 📘 **GitHub Pages展開**による教材公開（Zenn互換対応）  
- [ ] 🧠 **SamizoGPT連携**によるプロンプト支援（技術比較・教材生成）  
- [ ] 🖨️ **印刷現象と流体シミュレーション**の連携資料追加  
- [ ] 🏗️ **評価系装置のPoC連携**（撮像／波形記録／自動化）

---

## 💬 **ご意見・提案 / Feedback & Suggestions**

本リポジトリに関する**ご意見・改善提案・議論**などがあれば、以下の **Discussion ページ**で歓迎します。  
**技術的観点・教育活用・構成改善**など、どのような視点でもお気軽にご投稿ください。

👉 [💬 Discussion ページはこちら](https://github.com/Samizo-AITL/Inkjet/discussions)

> ※ GitHub アカウントでログインのうえ、トピック作成または既存スレッドへの返信が可能です。

---
