# 静的ページ作成時のテンプレート

## Requirement

* npm
* yarn

## Installation

```sh
$ brew install node
$ npm i -g yarn
$ yarn install
```

## Development

```sh
$ npm run watch
```
* watchを一回実行すると、変更が http://localhost:3000 に即時適用される

## Deploy

```sh
$ npm run build
```
* netlifyのデプロイ設定で上記のコマンドを設定する
