# quick-start-opencode

OpenCode初心者向けの日本語クイックスタート集。GitHub Pagesで公開する。

- 公開URL: https://stellates.github.io/quick-start-opencode/
- 公開手順: GitHubの Settings → Pages → Build and deployment → Deploy from branch → ブランチ `main`・フォルダ `/ (root)` を選択して保存する。

## ローカルの確認方法

```bash
export PATH="/opt/homebrew/opt/ruby/bin:$PATH"
export PATH="/opt/homebrew/lib/ruby/gems/4.0.0/bin:$PATH"
jekyll build
```

ビルド結果は `_site/` に出る。確認後は `_site/` を残さないこと。
