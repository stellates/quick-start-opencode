---
title: 初回起動
layout: default
---

# 初回起動

## プロジェクトを開く ⚠️ 未検証

作業したいフォルダに移動し、OpenCodeを起動します。TUI（ターミナル画面）が開きます。

```bash
cd /path/to/project
```

```bash
opencode
```

コマンド自体は ✅ 検証済み（`opencode --help` で確認）。TUIの操作は自分の画面で試してください。

## プロジェクトを初期化する ⚠️ 未検証

TUIで次のコマンドを実行します。プロジェクトを分析し、`AGENTS.md` を作ります。

```
/init
```

作られた `AGENTS.md` はGitにコミットするのがおすすめです（公式ドキュメントの助言）。

## はじめにConsoleへ接続する 🔑 要ログイン

モデルを使う前に、OpenCode Consoleへ接続します（アカウントやAPIキーが必要です）。⚠️ 未検証（TUI内の操作のため）

TUIを起動した状態で、次のコマンドをTUIの中に入力します。`opencode` の後ろに付ける形ではありません。

```
/connect
```

案内に従ってConsoleにアクセスし、ログインして接続します。Zenを使う場合は [無料モデル](free-model.html) を先に読んでください。

## ブラウザで使う

ブラウザやアプリから接続するには、接続用のワンタイムリンクを表示します。コマンドの説明は ✅ 検証済み（`opencode pair --help` で確認）。リンク発行の動作は ⚠️ 未検証

```bash
opencode pair
```

ブラウザで開くWeb UI版は、次のコマンドでも起動できます。⚠️ 未検証（公式ドキュメントに基づく）

```bash
opencode web
```

## 次へ

[無料モデル](free-model.html) に進みます。
