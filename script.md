---
engine: name-name
chapter: 1
title: "Friday 19:30 — プロローグ"
---

## data: マスター

[パーティ hero]
名前: ゆうしゃ
レベル: 1
HP: 20
MP: 4
ATK: 5
DEF: 3
AGI: 4
[/パーティ]

[モンスター slime]
名前: スライム
HP: 10
ATK: 3
DEF: 1
AGI: 2
EXP: 2
GOLD: 1
[/モンスター]

[モンスター ghost]
名前: ゴースト
HP: 14
ATK: 5
DEF: 2
AGI: 6
EXP: 4
GOLD: 3
[/モンスター]

## opening: 19:30 の合図

[BGM: silence.ogg]

> 1930年代、とある町。
> 金曜日の夕方 19:30、いつもの音が鳴る。

**ナレーター** (normal, 中央):
これは Friday 19:30 の動作確認サンプルです。
ノベルパートと RPG (raycast) パートが切り替わります。

**ナレーター** (normal, 中央):
では、町を歩いてみましょう。

[場面転換]

## abel-town: 静かな町 [view=raycast]

[マップ 12x10 タイル=32]
TTTTTTTTTTTT
T..........T
T..RRRRRR..T
T..R....R..T
T..R....R..T
T..RRRRRR..T
T..........T
T..........T
T..........T
TTTTTTTTTTTT
[/マップ]

[エンカウント率: 1/8]
[エンカウント群: slime, ghost, slime+ghost]

[プレイヤー @5,7 向き=上]

[NPC ガイド @5,4 色=#88ccff]
やあ、ようこそ Friday 19:30 へ。
ここはまだ動作確認用の小さな町だ。
[/NPC]

[NPC 旅人 @8,7 色=#ffcc88]
シナリオはまだこれからだよ。
[/NPC]

## ending: つづく

> ……つづく。
