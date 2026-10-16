---
title: 基本操作
layout: default
---

# 基本操作

TUIでの基本操作です。いずれも ⚠️ 未検証（公式ドキュメントに基づく。自分の画面で試してください）。

## 質問する

コードについて尋ねます。`@` でファイルを指定できます。

```
How is authentication handled in @packages/functions/src/api/index.ts
```

## 変更を頼む

まずプランを作ってもらうのがおすすめです。`Tab` でプランモードに切り替え、やりたいことを説明します。

```
When a user deletes a note, we'd like to flag it as deleted in the database.
```

納得したら `Tab` でビルドモードに戻し、実行してもらいます。

```
Sounds good! Go ahead and make the changes.
```

## 取り消す・やり直す

結果が気に入らなければ、取り消します。

```
/undo
```

複数回実行すると、複数回分戻ります。やり直す場合は次のコマンドです。

```
/redo
```

## 会話を共有する

会話へのリンクを作ります。既定では共有されません。

```
/share
```

## 次へ

[スキル](skills.html) に進みます。
