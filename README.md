# 避難ルートシミュレーションプロジェクト

このプロジェクトでは、青山学院大学相模原キャンパスをモデルとして、緊急時の避難経路をシミュレーションし、安全性や効率性を評価します。Pythonを使用してシミュレーションモデルを構築し、実地データや平面図を基に避難ルートの最適化を目指します。

---

## プロジェクト概要

- **目的**:
  1. 緊急時における避難経路の安全性・効率性を評価。
  2. 出口や経路の封鎖が発生した場合の迂回ルートを計算。
  3. シミュレーションモデルを活用し、将来的な防災計画に役立てる。

- **背景**:
  青山学院大学相模原キャンパス内では、食堂(G棟)、B棟、グラウンドが主要な避難経路に位置します。本プロジェクトは、発火や経路封鎖などの緊急事態を想定し、動線の分散や混雑を含めたルート計算を行います。

- **ゴール**:
  1. 簡易モデル（G棟→B棟→グラウンド）の構築。
  2. 封鎖シナリオに基づく迂回ルートの検出。
  3. 視覚化を通じた避難計画の提案。

---

## 機能

- 避難ルートの最短経路計算（通常時）
- 経路封鎖を考慮した迂回ルートのシミュレーション
- 経路距離や混雑度に基づく動線評価
- シナリオ別のシミュレーション結果の可視化

---

## プロジェクト構成

```plaintext
evacuation-simulation/
├── data/               # 経路データ（平面図、距離、幅など）
├── scripts/            # シミュレーションスクリプト
├── docs/               # プロジェクトに関する文書（報告書や参考資料）
├── tests/              # テスト用のスクリプト
└── README.md           # プロジェクト概要（このファイル）
