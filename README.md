## 振り分けくん公開レビュー用プロジェクト

このプロジェクトは、公開レビューをしていただくためにフォークしてきたものです。
ご自由にissueを立てたり、プルリクを出したりしてください。mainブランチへのpushはしないようにお願いします。


<br><br><br>

![Logo](img/logo.svg)

# 振り分けくん

> Zoom の懇親会で大活躍間違いなし！<br>懇親会参加メンバーをいい感じにグループ分けしてくれる web サイトを作りました！

## デプロイ先

https://ikoma1234.github.io/team-generator/

## 動作デモ

<img src="img/demo.gif" alt='Demo' />

## プロジェクトのセットアップ

```shell
npm install
```

## Tailwind CSS のビルド方法

```shell
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```
