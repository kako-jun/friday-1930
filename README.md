# friday-1930

金曜19時30分からやっていたアニメ「ドラゴンクエスト 勇者アベル伝説」の同人RPG。
旧プロジェクト名: gemma-mon。

## 概要

- **エンジン**: [name-name](https://github.com/kako-jun/name-name)（Markdown ベースのゲームスクリプト言語）
- **視点**: 一人称レイキャスティング（DOOM 風）
- **ジャンル**: RPG + マインクラフト風システム（予定）

## プロジェクト構造

```
friday-1930/
├── chapters/
│   └── all.md          # ゲームスクリプト（name-name Markdown）
├── assets/
│   ├── images/         # 画像（PNG, JPG, SVG等）
│   ├── sounds/         # 音声（MP3, WAV, OGG等）
│   ├── movies/         # 動画（MP4, WEBM等）
│   └── ideas/          # 企画メモ
└── README.md
```

## 開発

name-name エディタでクローンして編集する。

```bash
cd /path/to/name-name
docker compose up -d
# ブラウザで http://localhost:5173 を開き、
# 「プロジェクトをクローン」で https://github.com/kako-jun/friday-1930.git を指定
```

## ブランチ戦略

- **develop**: 編集用（name-name はデフォルトで develop を見る）
- **main**: 本番用

## 登場キャラクター

- **アベル**: ニセ勇者成分のある主人公
- **デイジー**: 幼なじみ
- **ティアラ**: 魔法使い
- **キートン**: 情報屋気質の仲間
- **モコッチ**: マスコット
- **ジキド / ムーア**: 敵役

## ライセンス

未定。二次創作のため配布方針は要検討。
