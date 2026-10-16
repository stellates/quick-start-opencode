---
title: 無料モデル
layout: default
---

# 無料モデル

お金をかけずに始めるには、無料提供のモデルを選びます。

## 無料モデルを確認する ✅ 検証済み

次のコマンドで使えるモデル一覧を表示できます。ログインなしで実行できました。

```bash
opencode models
```

一覧の中に `-free` で終わるIDがあります。2026-10-16に確認した例です（提供内容は変わります）。

- `opencode/muse-spark-1.3-contributor-free`
- `opencode/cat-jam-free`
- `opencode/deepseek-v4.1-flash-free`
- `opencode/glm-5.3-flash-free`

モデルIDは `opencode/` から始まる形で指定します。✅ 検証済み（公式ドキュメントの形式と一致）

## モデルを選ぶ ⚠️ 未検証

TUIで `/models` を実行して選びます。または設定ファイルに書きます。

```json
{
  "$schema": "https://opencode.ai/config.json",
  "model": "opencode/muse-spark-1.3-contributor-free"
}
```

## 注意点

- 無料提供は終了する場合があります。使う前に `opencode models` で確かめてください。✅ 検証済み
- 無料モデルごとに利用条件やデータの扱いが異なります。公式ドキュメントの「無料モデル」の節を読んでください。⚠️ 未検証（ドキュメントに基づく）
- Zenの接続にはログインと請求設定が必要です。🔑 要ログイン
- このサイトの検証作業は、Muse Spark 1.3 Freeで実際に行いました。✅ 検証済み

## 次へ

[基本操作](usage.html) に進みます。
