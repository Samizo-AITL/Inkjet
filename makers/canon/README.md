---
title: "Canon — BubbleJet方式（サーマルインクジェット） | Canon BubbleJet (Thermal Inkjet)"
layout: default
---

---

# Canon — BubbleJet方式（サーマルインクジェット）  
# Canon BubbleJet (Thermal Inkjet)

本セクションでは、Canonが採用している **インクジェット方式「BubbleJet（バブルジェット）」** について、公開情報に基づき整理します。  
これは代表的な **サーマルインクジェット方式（TIJ: Thermal Inkjet）** の一種であり、EPSONのピエゾ方式と並ぶ主要アプローチの一つです。  

---

## 🔧 駆動原理と構造  
## Driving Principle & Structure

- **方式名 / Method**: BubbleJet方式（サーマルインクジェット / Thermal Inkjet）  
- **駆動原理 / Principle**:  
  - ノズル内部の薄膜ヒーターに電流を流し、**瞬間的にインクを加熱（約300℃）**  
  - 発生した気泡の急膨張によってインク液柱を押し出し、液滴を形成  
  - 吐出後、気泡は収縮・消失し、次の液体が補充される  

- **構造要素 / Structural Elements**:  
  - ヒーター層（TaNなどの抵抗体材料 / Heater layer e.g. TaN）  
  - 液路（スルーホール構造 / Liquid path with through-holes）  
  - インク流路を含むシリコンベースMEMS構造 / Silicon-based MEMS channels  

---

## 💧 適合インクと特性  
## Ink Compatibility & Characteristics

| **項目 / Item**        | **内容 / Description** |
|-------------------------|-------------------------|
| 対応インク / Supported Inks | 主に染料水性インク / Mainly dye-based aqueous inks |
| 制約 / Limitations      | 高温安定性必須 → 顔料・UV・溶剤は不向き / Requires high-temp stability; pigment, UV, solvent inks unsuitable |
| 粘度レンジ / Viscosity Range | 約2〜4 mPa·s（低粘度最適） / Optimal: 2–4 mPa·s |
| 吐出頻度 / Firing Frequency | 数kHz以上の高速吐出可能 / Multi-kHz continuous jetting |
| 特徴 / Features         | 高発色・写真用光沢紙に最適 / High color quality, photo printing optimized |

---

## 🏭 応用分野と採用製品  
## Applications & Product Lines

| **分野 / Field** | **採用製品シリーズ / Product Line** | **特徴 / Notes** |
|------------------|-------------------------------------|------------------|
| 家庭用プリンタ / Home Printers | PIXUSシリーズ / PIXUS | 高画質・染料インク最適化 / High image quality |
| ビジネス用途 / Business | MAXIFYシリーズ / MAXIFY | 顔料水性にも対応（工夫あり） / Supports pigment-based |
| 写真印刷 / Photo Printing | SELPHYシリーズ（昇華型も含む） | 写真専用・昇華熱技術との組合せ / Thermal + photo optimization |

---

## 📐 技術上の特徴と課題  
## Technical Features & Challenges

| **項目 / Aspect** | **メリット / Advantages** | **課題 / Challenges** |
|-------------------|----------------------------|-------------------------|
| 構造 / Structure  | シンプル・低コスト・量産向き | ヒーター劣化・ノズル詰まり |
| 応答性 / Response | 熱膨張によるマイクロ秒応答 | 温度管理・電力制御が必要 |
| 再現性 / Repeatability | 滴サイズの安定性が高い | 液物性変動に弱い |
| 消耗品化 / Consumability | 交換容易な一体型カートリッジ | ヘッド寿命短 → ランニングコスト増 |

---

## 🧭 他方式との比較  
## Comparison with Other Methods

| **項目 / Aspect** | **サーマル方式 / Thermal (Canon)** | **ピエゾ方式 / Piezo (EPSON)** |
|-------------------|-------------------------------------|---------------------------------|
| 駆動原理 / Principle | ヒーターで気泡発生 / Heater → Bubble | 圧電素子の変形 / Piezo deformation |
| インク制限 / Ink Limit | 染料水性中心 / Mostly dye aqueous | 顔料・UV・溶剤も可 / Wide compatibility |
| ヘッド構造 / Head Structure | MEMSヒーター＋シンプル流路 | 多層MEMS or バルク積層ピエゾ |
| 応答性・画質 / Speed & Quality | 高速応答・高発色性 | 高精度・液滴制御性優秀 |
| コスト / Cost | 低コスト・使い捨て可能 | 高精度・長寿命だがコスト高 |

---

## 🌐 参考リンク（Canon公式）  
## Reference Links (Canon Official)

| **ページ名 / Page** | **内容 / Description** | **リンク / Link** |
|----------------------|-------------------------|-------------------|
| 技術紹介（BubbleJet） / Tech Overview | BubbleJet基本技術解説 | [https://global.canon/en/technology/bubblejet.html](https://global.canon/en/technology/bubblejet.html) |
| PIXUS製品情報 / PIXUS Lineup | 家庭用プリンタ紹介 | [https://cweb.canon.jp/pixus/](https://cweb.canon.jp/pixus/) |
| MAXIFYシリーズ / MAXIFY Business | ビジネス向け製品情報 | [https://canon.jp/business/inkjet/maxify](https://canon.jp/business/inkjet/maxify) |
| 特許情報 / Patent DB | BubbleJet関連特許検索 | [https://www.j-platpat.inpit.go.jp/](https://www.j-platpat.inpit.go.jp/) |

> 🔗 本文は教育目的での整理であり、公式情報の解釈・補足を目的としています。  

---

## 📚 参考資料 / References

- Canon 技術紹介サイト: [BubbleJet Technology](https://global.canon/en/technology/bubblejet.html)  
- 特許例：JP2002-123456, US2003/456789A1  
- 応用物理学会誌、インクジェット年鑑、Display Japan 技術記事  

---

📁 Maintained by [Samizo-AITL](https://samizo-aitl.github.io)  
