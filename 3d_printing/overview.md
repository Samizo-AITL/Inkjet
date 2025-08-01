# インクジェット技術と3Dプリンタ応用 / Inkjet Applications in 3D Printing

本章では、インクジェット方式を基盤とした3Dプリンティング技術の分類と、関連技術のマッピングを行います。  
インクジェットの高精度な液滴制御技術は、**微細材料吐出・バインダ接着・機能性材料積層**といった3D造形応用に展開されつつあります。

---

## 🧩 1. インクジェットと3Dプリンタの接点

| インクジェット技術      | 3Dプリンタ応用                       | 共通点                             |
|-------------------------|--------------------------------------|------------------------------------|
| 高精度液滴制御           | 材料吐出／接着剤噴射                 | マイクロ秒オーダーの液滴生成制御  |
| 多ノズル並列印字         | 造形面へのライン走査                 | 高速面展開                         |
| 波形調整による量制御     | 吐出量／積層厚みの制御               | 材料依存パラメータチューニング     |

---

## 🧪 2. 応用方式の分類

### 🔹 Binder Jetting（バインダジェッティング）

- 粉末層にバインダ液をインクジェットで選択的に吐出 → 接着
- 造形後に焼結・硬化プロセスが必要
- 材料例：石膏、セラミック、金属粉

### 🔹 Material Jetting（材料ジェッティング）

- 機能性材料（UV樹脂、ワックスなど）を液滴として直接積層
- 各層ごとに紫外線や加熱により硬化
- 使用例：歯科模型、マルチマテリアル構造体

### 🔹 その他の応用形式

- **Drop-on-Demand BioPrinting**（細胞スプレー）
- **ナノ粒子ジェッティング**（電子デバイス・配線形成）

---

## 🏗 3. 構成装置の共通化と差異

| 項目               | インクジェット印刷機          | 3Dプリンタ（Jet方式）         |
|--------------------|-------------------------------|-------------------------------|
| ヘッド種類         | ピエゾ／サーマル              | 主にピエゾ（UV・高粘度対応）   |
| 印字対象           | 紙／フィルム                  | 粉体層／レジン層               |
| 固化手段           | 吸収／蒸発                    | 焼結・UV硬化・熱硬化など       |
| 軸制御             | XYガントリー／ベルト搬送     | XYZステージ制御＋Z積層         |

---

## 🎯 4. 技術的課題と研究動向

| 課題                         | 内容                                     |
|------------------------------|------------------------------------------|
| 吐出安定性                  | 高粘度材料や粒子混入系でのノズル詰まり  |
| 固化／硬化プロセスの制御     | UV照射／加熱条件との整合が必要           |
| 材料の分離・沈降対策         | 懸濁液系（スラリー）での安定分散技術     |
| 高精細制御                   | 10μm以下スケールでの積層精度要求         |

---

## 🔄 5. Inkjetとの将来融合可能性

- MEMSヘッドのマルチマテリアル化（複数流路・加温機能）
- バイオプリンティング・医療デバイス形成への応用
- 成膜／配線形成／フォトニクスなどナノ製造への展開

---

## 📚 参考文献

- ASTM分類（ASTM F2792-12a）：AM技術の公式分類
- Fujifilm Dimatix Jetting Guide
- Nature Materials, Additive Manufacturing Journal ほか
