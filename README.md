# Tool4ADHD

このプロジェクトは、ADHD の方向けのシンプルな Web ツールです。

## 概要

- シンプルな Web ページを GitHub Pages で公開できます。
- どなたでも簡単に使えます。

## GitHub Pages での公開方法

1. このリポジトリを GitHub にプッシュします。
2. GitHub のリポジトリ設定から「Pages」を選択し、`main`ブランチの`/ (root)`を公開対象に設定します。
3. 数分後、指定された URL で Web ページが公開されます。

## 初回 GitHub リポジトリへの push 方法

以下のコマンドをターミナルで実行してください（初回のみ必要です）。

```sh
git remote add origin https://github.com/tkgshn/Tool4ADHD.git
git branch -M main
git push -u origin main
```

- これで GitHub リポジトリにファイルがアップロードされます。
- 2 回目以降は `git add . && git commit -m "メッセージ" && git push` だけで OK です。

## 使い方

- ブラウザで公開 URL にアクセスするだけで利用できます。
