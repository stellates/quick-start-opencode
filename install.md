---
title: インストール
layout: default
---

# インストール

## Mac ✅ 検証済み

公式のインストールスクリプトを使います。⚠️ 未検証（配布元の応答は確認済み。パイプ実行自体は未実行のため、実行前に配布元を確認してください）

```bash
curl -fsSL https://opencode.ai/install | bash
```

ほかの方法もあります（いずれも ⚠️ 未検証・公式ドキュメントに基づく）。

```bash
npm install -g opencode-ai
```

```bash
brew install anomalyco/tap/opencode
```

入ったか確かめます。✅ 検証済み（v2.0.30を確認）

```bash
opencode --version
```

## Windows ⚠️ 未検証

Windowsの手順はすべて公式ドキュメントに基づきます。手元のWindows環境で再確認してください。

- 推奨はWSL（Windows Subsystem for Linux）です。その中で上のMac・Linuxと同じ手順を使います。
- WSLを使わない場合は、次のいずれかで入れます。

```
choco install opencode
```

```
scoop install opencode
```

```
npm install -g opencode-ai
```

## 次へ

[初回起動](start.html) に進みます。
