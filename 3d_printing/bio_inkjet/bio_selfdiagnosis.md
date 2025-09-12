---
layout: default
title: 自己診断・適応制御 | Self-Diagnosis & Adaptive Control
---

# ⚡ 自己診断・適応制御  
*Self-Diagnosis & Adaptive Control for Bio-Inkjet*

本章では、鉛フリー圧電アクチュエータ (KNN) を利用した  
**自己診断機能**と**適応制御 (Adaptive Control)** の応用を整理します。  
Bio-IJ システムにおいて、アクチュエータ応答をセンサー代替として用いることで、  
安定吐出とインク状態モニタリングを同時に実現します。  
*This chapter organizes the application of **self-diagnosis** and **adaptive control** using lead-free piezoelectric actuators (KNN). In Bio-IJ systems, actuator responses serve as sensor substitutes, enabling both stable jetting and ink-state monitoring.*  

---

## 🔹 基本原理  
*Basic Principle*

- **電気的観測**  
  駆動電流、電荷応答、変位波形を観測  
  *Electrical monitoring of drive current, charge response, and displacement waveforms*  

- **センサー代替**  
  アクチュエータ自身の応答を利用  
  *Using actuator responses as a sensor substitute*  

---

## 🔹 自己診断機能  
*Self-Diagnosis Functions*

- **ドット抜け検出**  
  電荷・変位シグネチャから未吐出を検出し、隣接ノズルで補償  
  *Detect missing droplets via charge/displacement signatures and compensate with neighboring nozzles*  

- **粘度推定**  
  応答速度の変化からインク粘度を推定し、駆動電圧をフィードバック  
  *Estimate ink viscosity from response speed and adjust driving voltage accordingly*  

- **気泡検知**  
  応答の非線形変化を解析し、吐出不良や不安定動作を早期発見  
  *Analyze nonlinear changes in response to detect bubbles and prevent unstable jetting*  

---

## 🔹 適応制御戦略  
*Adaptive Control Strategies*

- **PID調整**  
  出力誤差に応じて $K_p, K_i, K_d$ を逐次更新し、吐出波形を安定化  
  *Sequentially update $K_p, K_i, K_d$ based on output error to stabilize jetting waveforms*  

- **FSMモード遷移**  
  異常検出時にリカバリモードへ移行し、再吐出やクリーニング制御を実行  
  *Switch to recovery modes upon fault detection, enabling re-jetting or cleaning control*  

- **LLM連携**  
  長期データを基に制御則を再設計し、新しいインク条件や劣化に対応  
  *Redesign control rules using long-term data, adapting to new inks or device degradation*  

---

## 🔹 実装上のポイント  
*Implementation Notes*

- **駆動ICとの連携**  
  COF駆動ICの電流モニタ端子を利用し、SPI経由で応答データを収集可能  
  *Use current-monitor terminals in COF driver ICs and collect response data via SPI*  

- **処理負荷**  
  数百 Hz〜kHz レベルの演算で十分、FPGA/MCU 実装が容易  
  *Computation at hundreds of Hz to kHz is sufficient; FPGA/MCU implementation is feasible*  

- **教育的価値**  
  MEMS × 圧電 × 制御理論の統合事例として教材化に適する  
  *An integrated case study of MEMS × piezoelectric devices × control theory, suitable for teaching*  

---

## 📌 まとめ  
*Summary*

- KNNアクチュエータは **センサー＋アクチュエータの二重機能**を発揮可能  
  *KNN actuators can serve as both sensors and actuators*  

- 自己診断制御により、**安定吐出・粘度補償・欠陥検出**が実現  
  *Self-diagnosis enables stable jetting, viscosity compensation, and defect detection*  

- AITL (PID–FSM–LLM) アーキテクチャと組み合わせることで、  
  **適応的で信頼性の高いBio-Inkjetシステム**へ発展可能  
  *Combining with the AITL (PID–FSM–LLM) architecture leads to adaptive and reliable Bio-Inkjet systems*  

---
