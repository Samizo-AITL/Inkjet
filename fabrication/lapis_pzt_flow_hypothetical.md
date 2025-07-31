# ラピス ピエゾ混載CMOSプロセスフロー（技術推定要約）  
Lapis PZT-Integrated CMOS Process Flow (Hypothetical Summary)

> *LAPIS Semiconductor - Monolithic Integration of PZT MEMS and CMOS Circuits (Hypothetical Reconstruction)*

---

## ✅ 技術概要（Summary）

| 項目 | 内容 | Description |
|------|------|-------------|
| **プロセスノード** | 0.35μm セミリセスLOCOS | 0.35μm Semi-recessed LOCOS process |
| **ゲート構造** | WSi（タングステンサイリサイド）ゲート | WSi (tungsten silicide) gate |
| **電圧構成** | 高耐圧20V（G1-OX=430Å） + ロジック3.3V（G2-OX=70Å） | High voltage 20V + Logic 3.3V |
| **酸化膜厚** | 実効Tox = 500Å（G1 + G2） | Effective Tox = 500Å |
| **PZT構造** | Pt / PZT（10,000Å） / Ti（分割スパッタ + アニール4回） | Pt / PZT (10,000Å) / Ti with split sputtering and 4-step annealing |
| **基板結晶方位** | Si(111)（裏面キャビティ加工対応） | Si(111) for backside cavity formation |
| **集積方式** | モノリシック：CMOS + PZTアクチュエータ混載 | Monolithic integration: CMOS + PZT actuator |
| **放熱設計** | 裏面放熱＋GND配線＋サーマルビア実装 | Backside thermal dissipation + GND wiring + thermal vias |

---

## 🧩 代表工程フロー（抜粋）  
Representative Process Flow (Excerpt)

### 1. ウェル・アイソレーション / Well & Isolation
- LOCOS分離（セミリセス） / LOCOS isolation (semi-recessed)
- NWL/PWL（3.3V） + NWLH/PWLH（20V）

### 2. 酸化膜形成 / Oxide Formation
- G1-OX（430Å）→ 高耐圧用 / for high voltage
- G2-OX（70Å）→ ロジック用 / for logic
- 実効Tox = 500Å、Eox ≒ 4 MV/cm

### 3. ゲート形成・注入 / Gate Formation & Doping
- WSiゲート + PLYA-DP（パターン）/ WSi gate with PLYA-DP
- NLD/PLD：3.3V用、NLDH/PLDH：20V用 / Logic and HV implantation
- SW-DP/ET：フィールドストッパ注入 / Field stopper doping

### 4. PZT積層・アニール / PZT Deposition & Annealing
- Pt-SP → PZT-SP（2,500Å × 4）→ Ti1/Ti2-SP
- 各回後にPZT-ANL（450℃）×4回 / 450℃ annealing after each layer
- CAP-PH/ET：ミリングによる開口処理 / Milling for electrode access

### 5. メタル・プラグ・パッド形成 / Metal, Plug, Pad Formation
- 金属層：ALA, HLA, ALB（3層Al）/ Three-layer Al interconnects
- Wプラグ：CW, CWX, CWA / Tungsten plugs
- PAD-PH/ET → パッド形成、AL-SNT / Pad definition and AL sonic trim

### 6. 裏面加工 / Backside Processing
- Si(111)基板 → 異方性エッチングでキャビティ形成 / Cavity via anisotropic etching

---

## 🔥 放熱設計と対策 / Thermal Design Considerations

- 高電圧駆動による損失（I×V, C×V²×f）を裏面から放熱  
  Power loss from high-voltage drive is dissipated through the backside
- ダイアタッチ材：高熱伝導タイプ（Agエポキシ等）  
  Die attach with high thermal conductivity (e.g., Ag epoxy)
- サーマルビア・放熱基板・GND設計による熱経路確保  
  Heat paths via thermal vias, substrate, and GND layout

---

## 🎓 教材的意義 / Educational Insights

- 高耐圧CMOS設計とTox制御（500Å）  
  HV CMOS design and oxide thickness control
- 分割スパッタ＋アニールによるPZT厚膜形成技術  
  Thick PZT film via split sputtering and annealing
- 放熱設計・裏面エッチング・基板選定まで含めたMEMS-CMOS一体構造  
  MEMS-CMOS integration considering heat, etching, substrate
- 教材・研究用のPZT混載プロセス事例として高い教育価値あり  
  Valuable educational case for monolithic PZT-CMOS integration

---

> ⚠ 本プロセスは、**ラピスセミコンダクタの公開情報**と**技術的推定**に基づいた教育的再構成です。実際の製造フローとは異なる可能性があります。  
> ⚠ This document is an **educational reconstruction** based on **public information** from LAPIS Semiconductor and technical inference. It may differ from the actual manufacturing process.
