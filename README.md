# 静的サイトを制作する開発環境

説明は[こちら](http://system.blog.uuum.jp/entry/2018/11/19/130000)を読んでください。

## インストール

```
$ npm i
```

## 開発(コーディング)

```
$ npm start
```

## プロダクション向けビルド

```
$ npm run build
```
## 公開するファイル

プロダクション向けビルドを行うと、 `/public` に公開用のリソースが全て揃います。

`/public` をデプロイし、静的サイトして運用出来ます。  

# Deploy to Netlify
<!-- Markdown snippet -->
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/MozyOk/static-site-boilerplate)
