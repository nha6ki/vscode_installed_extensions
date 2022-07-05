# VSCode
- インストールした拡張機能のリスト：[vscode_installed_extensions.txt](vscode_installed_extensions.txt)

## インストール
```
cat vscode_installed_extensions.txt | xargs -L 1 code --install-extension
```

## 更新方法
```
code --list-extensions > vscode_installed_extensions.txt
```

## 拡張機能

### [Better Solarized Light - Color Theme](https://marketplace.visualstudio.com/items?itemName=ginfuru.ginfuru-better-solarized-dark-theme)
- [Color ThemeをBetter Solarized Lightに変更する](https://code.visualstudio.com/docs/getstarted/themes)

### Japanese Language Pack
- UIを日本語化する

### vscode-icons
- アイコンを表示する

### GitLens
- Gitの差分を表示する
- usage: エディタの上にあるGitボタン

### Git Graph
- Gitの履歴をツリー形式で表示する
- usage: F1 >git-graph.view

### [Partial Diff](https://marketplace.visualstudio.com/items?itemName=ryu1kn.partial-diff)
- 選択範囲の差分を表示する
- usage: Right-click Menu

### Bracket Pair Colorizer
- カッコの対応関係を色付き表示する

### indent-rainbow
- インデントを虹色で表示する

### zenkaku
- 全角スペースを強調表示する

### Trailing Spaces
- 行末の空白を強調表示する

### [Restore Editors](https://marketplace.visualstudio.com/items?itemName=eamodio.restore-editors)
- 開いたエディタタブを保存・復元する
- Cmd+K Cmd+E

### Code Spell Checker
- スペルミスを検出する

### Regex Previewer
- 正規表現をチェックする

### change-case
- 命名規則を変換する
- usage: F1 >change-case

### Bookmarks
- コードをブックマークして移動・リスト化できる
- usage:
  - Bookmarks Toggle: Cmd+Opt+K
  - Bookmarks jump to Next: Cmd+Opt+L
  - Bookmarks jump to Previous: Cmd+Opt+J

### Auto Rename Tag
- ペアになっているHTML/XMLタグの名前を自動的に変更する

### Auto Close Tag
- HTML/XMLの終了タグを自動的に追加する

### Beautify
- HTML/CSS，JavaScriptのコードを整形する

### Path Intellisense
- ファイルのパスを補完する

### [Markdown Preview Enhanced](https://shd101wyy.github.io/markdown-preview-enhanced/#/ja-jp/)
- Markdownの機能を拡張する
- usage: Cmd+Shift+v
  - Right-click Menu

### [Markdown PDF](https://github.com/yzane/vscode-markdown-pdf/blob/master/README.ja.md)
- Markdownファイルをpdf, html, png, jpegに変換する
- usage: Right-click Menu

### [VSCode Reveal](https://www.evilznet.com/vscode-reveal/#/)
- reveal.jsでスライドを作る
