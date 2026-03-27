# README

文章内容が、「コムニコプロダクト表記ガイドライン」に沿っているか自動チェックするための環境です。

### インストール

```sh
npm install
```

### 使いかた

#### Visual Studio Code

`samples/` 内のテキストファイルを開いてテキストを入力すると、textlint拡張機能によりリアルタイムで自動チェックされます。

#### コマンドライン

lintを実行します。

```sh
npm run lint
```

自動修正する場合は以下を実行します。

```sh
npm run lint:fix
```
