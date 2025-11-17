# ADD Development Flow（軽量版）

ADD は  
**Lake → Rivers → Dams → Flow → Gold**  
の順に進むシンプルな開発プロセスです。

それぞれのフェーズは次の役割を持ちます。

---

## Phase 0: Lake（知識を集める）

- チケットに関する情報・仮説・懸念・ユースケースをすべて集める
- 情報の粒度は不問、とにかく書き出す

---

## Phase 1: Rivers（価値単位で分解する）

- Lakeの内容をもとに、1〜2時間で終わる価値フェーズに分解する
- 複数のRiverを作ってもよい
- 必要に応じて後で書き換えてもよい

---

## Phase 2: Dams（イテレーションを定義する）

- 各Riverを小さなイテレーション（Dams）に分割する
- **Probe**（探索）と **Build**（実装）に分かれる
- 1 Dam = 1〜2時間

---

## Phase 3: Flow（実際に前に進める）

- Damの内容に従って実際の作業を行う
- Probeでは学びを Lake に戻す
- Buildでは TDD（Red → Green → Refactor）で進める
- 行動ログを Flow として記録する

---

## Phase 4: Completion（すべての水が流れる）

- Rivers も Dams もすべて完了した状態
- 追加の不確実性がなければチケット完了

---

## Phase 5: Gold Sand（学びを抽出する）

- Lake / Rivers / Dams / Flow を読み返し、  
  得られた学び・パターン・アンチパターンを抽出する
- これはADDの“成果物”であり、次の開発に生きる