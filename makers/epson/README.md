# EPSON — プリントヘッド技術概要（公開用）

本ディレクトリでは、EPSON社のインクジェットプリントヘッド技術に関する **公開可能な範囲の情報** を掲載しています。  
詳細な構造、駆動方式、材料構成、評価記録などの機密情報については、別途管理されている非公開リポジトリにて保存されています。

---

## 🔒 非公開技術情報との接続

以下の技術情報は、すべて非公開リポジトリ [`Private/Epson/`](https://github.com/Samizo-AITL/Private/tree/main/Epson) に格納されています。  
本リポジトリでは概要説明と構成リンクのみを掲載しており、**図面・試験データ・詳細記述は含まれません**。

| セクション | 内容概要                                   | 参照（※非公開） |
|------------|--------------------------------------------|------------------|
| `uTFP/`    | 薄膜MEMS構造（PrecisionCore）の技術構成     | [`Private/Epson/uTFP/`](https://github.com/Samizo-AITL/Private/tree/main/Epson/uTFP) |
| `MACH/`    | バルクピエゾ構造（旧世代Mach方式）          | [`Private/Epson/Mach/`](https://github.com/Samizo-AITL/Private/tree/main/Epson/Mach) |

> ⚠️ 現在これらのリンクは非公開設定となっており、アクセスには制限があります。将来的に教育用途での限定公開が検討されています。

---

## 🧭 本リポジトリでの掲載方針

- `epson/uTFP/README.md` および `MACH/README.md` にて、それぞれの非公開技術の章構成概要と導線のみを記述
- 電極構成・PZT積層・応答設計・駆動波形などの**詳細技術記述は含まれていません**
- 教材・研究向け構成の一部を公開技術と照合しつつ、技術マップとしての役割を担います

---

## 📘 EPSONヘッドの技術的特徴（公開範囲内）

- **駆動方式**：ピエゾ方式（薄膜PZT）
- **アクチュエータ構造**：d33モード MEMSアクチュエータ（μTFP構造）
- **特徴**：高密度ノズル設計、低消費電力、高速応答
- **対応インク**：水性（染料／顔料）、UVインク等
- **用途例**：写真印刷、商業用ラベル、テキスタイル印刷、産業用途（プリント基板・電子部品等）

> 駆動アルゴリズムや応答補正方式は、非公開制御技術に基づいており、本リポジトリでは扱いません。

---

## 🌐 参考リンク（EPSON公式サイト）

EPSON社のインクジェット技術に関する公開情報は、以下の公式リソースを参照ください。

| ページ名 | 内容 | リンク |
|----------|------|--------|
| インクジェット技術紹介 | PrecisionCoreを含む基盤技術の紹介 | [corporate.epson/ja/technology/inkjet](https://corporate.epson/ja/technology/inkjet/) |
| PrecisionCoreとは | PrecisionCoreプリントヘッドの特徴・構造 | [epson.jp/technology/core_technology/inkjet.htm](https://www.epson.jp/technology/core_technology/inkjet.htm) |
| 製品用途紹介 | インクジェットの商業／産業用製品ラインナップ | [epson.jp/products/inkjet/](https://www.epson.jp/products/inkjet/) |
| 知的財産レポート（PDF） | 技術開示・IP戦略を含む公開レポート | [IPレポート2023 (PDF)](https://corporate.epson/ja/technology/intellectual_property/pdf/ipr2023.pdf) |

> 🔗 各リンクはEPSON社による正式公開情報です。本リポジトリは非公式の技術整理であり、製品保証等とは関係ありません。

---

## 📝 備考

- 本READMEは「技術情報の構成・所在」を示すための**技術インデックス**として設けられています。
- 教材／研究支援を目的としており、**製品設計や信頼性保証を目的とした情報ではありません**。

---

📁 Maintained by [Samizo-AITL](https://samizo-aitl.github.io)
