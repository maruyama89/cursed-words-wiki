# ボス

「CHOOSE YOUR OPPONENT」画面で、2体のボスから1体を選んで戦う形式（実機確認）。ボスにはそれぞれ固有のルール変更効果があり、戦闘に影響する。ストア説明文にある「20 bosses that'll try to sabotage your runs, or can be manipulated into multiplying your score even higher（妨害してくることもあれば、逆に利用してスコアを稼ぐ手段になることもある）」の具体的な仕組みがこれだと思われる。

## 使い方
- ボス名がスクリーンショットからは確認できていないため、見た目による仮称を付けている。正式名称が分かり次第更新する
- 効果文はそのまま引用し、訳文には原語を `<small>(英語)</small>` で小さく併記する
- 未確認情報には「（要確認）」を付ける

## 一覧

### ボス（仮称: 蛾のボス）

**見た目**: クリーム色と黄土色の、蛾または昆虫のようなクリーチャー。長い触角と鋭い歯を持つ（要確認: 正式名称）

**効果 (原文)**:
> 2 coloured tiles become colourless.

**効果 (訳)**:
> 色付きタイル<small>(coloured tiles)</small>2枚が無色<small>(colourless)</small>になる。

**メモ**:
- [RED tile / BLUE tile](../glossary/index.md)に依存するシナジー（Wheezy Vixen, Rodman固有スキルなど）を弱体化させる効果と思われる。逆に色に依存しないビルドなら影響が少ない。

---

### ボス（仮称: モグラのボス）

**見た目**: 黒っぽい体にピンク色の手足を持つ、モグラまたは影のようなクリーチャー（要確認: 正式名称）

**効果 (原文)**:
> Scatters 3 VOID tiles onto each grid.

**効果 (訳)**:
> 各グリッド<small>(each grid)</small>にVOIDタイルを3枚ばらまく<small>(scatters ... onto)</small>。

**メモ**:
- 一見妨害効果に見えるが、[Dusty Coffin](../items/index.md)や[Milky Way](../abilities/index.md#milky-wayミルキー・ウェイ)などVOID軸のビルドなら、VOIDタイルの供給源として逆に追い風になりうる。ストア説明文「can be manipulated into multiplying your score even higher」の実例と思われる。

---

### ボス（仮称: シャーク／オオカミ系のボス）

**見た目**: 灰紫色の体に白い腹、鋭い歯を持つサメ/オオカミのようなクリーチャー（要確認: 正式名称）

**効果 (原文)**:
> Steals $3 from you for each word submitted.

**効果 (訳)**:
> 単語を提出する<small>(word submitted)</small>たびに、$3を奪う<small>(steals)</small>。

**メモ**:
- 経済（所持金）に直接ダメージを与えるタイプの妨害。単語をたくさん提出するプレイスタイル（Telescopeのような蓄積型アイテムなど）と相性が悪そう。

---

### ボス（仮称: キツネのボス）

**見た目**: オレンジと白の毛並みを持つキツネのようなクリーチャー、ニヤリとした表情（要確認: 正式名称）

**効果 (原文)**:
> You may only submit words with 5 or fewer tiles.

**効果 (訳)**:
> 5文字以下<small>(5 or fewer tiles)</small>の単語しか提出できない<small>(you may only submit)</small>。

**メモ**:
- 単語の長さを制限する妨害。[Axe](../items/index.md)（3文字以下でボーナス）のような短い単語ビルドとは逆に相性が良く、長い単語で稼ぐビルド（[Alembic Flask](../items/index.md)の連番狙いなど）には不利。

---

### ボス（仮称: ハイエナのボス）

**見た目**: オレンジのモヒカン風の毛と斑点模様を持つハイエナのようなクリーチャー（要確認: 正式名称）

**効果 (原文)**:
> Forces you to sell an item at the beginning of the encounter.

**効果 (訳)**:
> エンカウントの開始時に<small>(at the beginning of the encounter)</small>、アイテムを1つ売却させられる<small>(forces you to sell)</small>。

**メモ**:
- Stickerを強制的に手放させる妨害。アップグレードを重ねたお気に入りのStickerを失うリスクがある、精神的ダメージの大きいタイプ。

---

### ボス（仮称: コウモリのボス）

**見た目**: 茶色い体に紫がかった翼を持つコウモリのようなクリーチャー（要確認: 正式名称）

**効果 (原文)**:
> The grid is 4x3.

**効果 (訳)**:
> グリッドが4×3<small>(4x3)</small>になる。

**メモ**:
- [Grid](../glossary/index.md)に行×列のサイズがあり、ボスによって変更されうることが確定した用例。デフォルトのグリッドサイズは未確認だが、4x3という数字から通常より小さい（あるいは形が変わる）制約と思われる（要確認）。

## 気づいた点
- ボス選択画面にも、他の画面と同様キャラクターパネル（$表示付き）が右側に表示される。$の値がラン中に変動している（$15→$20→$32）ことから、所持金表示である可能性が高い。ボスを選ぶこと自体に$のコストがかかるかは未確認（詳細は[items/index.md](../items/index.md)参照）。

## 関連
- [glossary/index.md](../glossary/index.md) — Boss, Encounter, Void tile
- [items/index.md](../items/index.md) — Dusty Coffin, Game Pad（VOID関連アイテム）
- [abilities/index.md](../abilities/index.md) — Milky Way
