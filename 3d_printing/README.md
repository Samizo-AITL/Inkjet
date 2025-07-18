# インクジェット × 3Dプリンティング技術 / Inkjet-Based 3D Printing

本ディレクトリでは、インクジェット技術を活用した3Dプリンティング技術の展開・分類・応用可能性についてまとめています。  
波形制御・液滴応答といった基本技術が、粉末接着、材料積層、バイオ応用などにどのように発展しているかを整理し、用途開発・教育・研究に役立つ知識ベースを構築します。

---

## 📂 構成ファイル / Directory Structure

```plaintext
3d_printing/
├─ overview.md         # インクジェットと3D技術の接点・方式概要
├─ classification.md   # ASTM分類に基づく技術方式マッピング
└─ inkjet_related.md   # 既存インクジェットとの技術融合と課題
```

---

## 🧭 各ファイルの概要

### 🔹 [`overview.md`](./overview.md)
インクジェットによる材料吐出・精密積層技術が、3Dプリンタにどのように展開されているかの総論です。  
Binder Jetting や Material Jetting などの方式が、どのような構造で実現されているかを簡潔に整理しています。

### 🔹 [`classification.md`](./classification.md)
ASTM国際標準によるAdditive Manufacturingの7分類に基づき、インクジェットが関与する方式（Binder Jetting / Material Jetting など）を分類比較しています。  
構造図（Mermaid.js）を用いて視覚的にも技術マップを把握できます。

### 🔹 [`inkjet_related.md`](./inkjet_related.md)
従来のインクジェット応用（商業印刷、電子配線、バイオ滴下）と、3D造形技術との技術融合について記述。  
材料適合・積層精度・多流路化など、今後の展開方向と研究課題を中心にまとめています。

---

## 🎯 想定用途

- インクジェット応用技術の学習・教材化
- バインダジェッティング／UVジェット式3D造形の技術比較
- 材料選定・プリンタ構成の設計検討支援
- 将来的なデジタルファブリケーションとの融合構想

---

## 📚 参考資料

- ASTM F2792-12a: *Additive Manufacturing Technology Classifications*  
- Fujifilm Dimatix: *Jetting Design Guide*  
- Stratasys, HP, Organovo 技術資料  
- Nature, Biofabrication, Additive Manufacturing 各誌論文
