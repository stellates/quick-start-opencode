# AGENTS.md

## 目的
OpenCode初心者向けの日本語クイックスタート集。インストール → 起動 → Freeモデルでの動作確認、利用上の注意・小技をまとめる。GitHub Pagesで公開する。

- リポジトリ: `stellates/quick-start-opencode`、ブランチ `main`
- 現状 (2026-10-16): コード・サイト生成器・build/test/lint設定なし。決め打ちせず確認すること。
- 対象はOpenCode初心者。説明文よりコピペで動くコマンドと期待される出力を優先する。

## 出力ルール
- このリポジトリでは原則すべて日本語で出力する（応答文・ドキュメント・コミットメッセージを含む）。
- インストール/起動コマンドは記憶で書かず、macOSで実際に実行・検証してから記載する。
- ログイン・APIキー・有料モデルが不要な手順 (Freeモデル) と、必要な手順を明確に分ける。
- ページは短くタスク単位に: `install`、`start`、`free-model`、`tips`、`troubleshooting`。

## GitHub Pages (未設定)
- Jekyll/Hugo/MkDocs等の設定はまだない。追加する場合は `main` から追加CIなしで動く最も単純な構成にする:
  - 既定の選択: 素のMarkdown + Jekyll (`_config.yml`) を Settings → Pages → Deploy from branch で公開。
  - 指示がない限り bundler/npm ツールチェイン、テーマ、プラグインは追加しない。
- Pages設定を追加したら、可能ならローカルserveで確認し、設定手順をREADMEに記載する。

## 作業ルール
- 特段の指示がない限りブランチは作成せず、直接 `main` へpushして良い。
- 文章の推敲は `yomiyasu` スキルを使う（`/` コマンドや `@` では呼べない。エージェントがskillツールで読み込む）。
- 小さくレビュー可能なコミットにする。指示なく大規模なサイト構成を作らない。
- 指示がない限り `README*`、ライセンス、CIワークフローは作らない。現在このリポジトリ唯一のファイルは `AGENTS.md`。
- 編集前に `git status` を確認する。
