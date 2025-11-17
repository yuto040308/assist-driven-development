# AGENTS

このリポジトリは **Assist Driven Development（ADD）** という開発手法で運用されています。  
人間とAIの両方が ADD の原則に従って動くことを前提とします。

ADD の詳細は以下のドキュメントを参照してください。

- `docs/add_overview.md`   …… ADDの思想・目的・世界観
- `docs/add_flow.md`       …… ADDの実際の開発フロー
- `docs/add_glossary.md`   …… 用語集（Lake / Rivers / Dams / Flow / Gold）

---

# 1. ADDとは

ADD は、  
**人間を主役に据え、AIは“補助（Assist）”として動く開発手法** です。

開発を、自然界の水の流れになぞらえて進めます：

- 知識の集約 → **Lake**
- 価値単位への分解 → **Rivers**
- 小さな作業単位 → **Dams**
- 実際の進行 → **Flow**
- 最後に残る学び → **Gold Sand**

これにより大きな課題を安全に分割し、  
不確実性を吸収しながら確実に前進できる開発プロセスを実現します。

---

# 2. ADDの共通ポリシー（人間・AI共通）

1. **Human-First（人間が最優先）**  
   設計・判断・方向性は必ず人間が決め、AIは補助役とする。

2. **Small Phases（極小フェーズ）**  
   1〜2時間で終わるフェーズ単位で進める。

3. **Localized AI（局所AI）**  
   AIを「調査、要約、テスト生成、部分実装、リファクタ」など  
   小さな領域に限定して使う。

4. **Lakeの継続更新**  
   気づき・前提・ユースケースなどは常に Lake に書き戻す。

5. **フェーズを飛ばさない**  
   Lake → Rivers → Dams → Flow → Gold の順番を尊重する。

---

# 3. エージェントの役割（AI / 人間どちらでも）

- **Lake Keeper**  
  知識を収集し、Lake を整える。

- **River Planner**  
  フェーズ（Rivers）を価値単位に分解する。

- **Dam Builder**  
  Probe / Build イテレーション（Dams）を定義する。

- **Flow Assistant**  
  テスト生成・局所実装・リファクタを補助し、Flow を記録する。

- **Gold Digger**  
  最後に学び（Gold Sand）を抽出し次に活かす。

---

# 4. AGENTS.md の役割

本ファイルは以下の機能を持ちます：

- **ADDの世界の入口**  
- **AIが従うべきルール**  
- **人間の思考・作業の基準点**  
- **ADDドキュメントへのポータル**

このリポジトリで動作するAIは、  
**必ず ADD の世界観とフローに基づいて行動してください。**