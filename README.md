# VSCode
- インストールした拡張機能のリスト
[vscode_installed_extensions.txt](vscode_installed_extensions.txt)

## インストール
```
cat vscode_installed_extensions.txt | xargs -L 1 code --install-extension
```

## 更新方法
```
code --list-extensions > vscode_installed_extensions.txt
```

## 拡張機能

### Japanese Language Pack
- UIを日本語化する

### vscode-icons
- アイコンを表示する

### GitLens
- Gitの差分を表示する

### Git Graph
- Gitの履歴をツリー形式で表示する

### [Partial Diff](https://marketplace.visualstudio.com/items?itemName=ryu1kn.partial-diff)
- 選択範囲の差分を表示する

### Bracket Pair Colorizer
- カッコの対応関係を色付き表示する

### indent-rainbow
- インデントを虹色で表示する

### zenkaku
- 全角スペースを強調表示する

### Trailing Spaces
- 行末の空白を強調表示する

### Code Spell Checker
- スペルミスを検出する

### Regex Previewer
- 正規表現をチェックする

### change-case
- 単語の大文字・小文字変換する

### Bookmarks
- コードをブックマークして移動・リスト化できる

### Auto Rename Tag
- ペアになっているHTML/XMLタグの名前を自動的に変更する

### Auto Close Tag
- HTML/XMLの終了タグを自動的に追加する

### Path Intellisense
- ファイルのパスを補完する
