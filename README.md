# 静的ページ作成時のテンプレート


## Directory

```
　├ public              # 出力フォルダ(css/html)がcompileされて展開されます 
　│　├ assets/font       　# WEBフォントを配置する場合の置き場
　│　└ assets/img        　# 画像ファイルを配置する場合の置き場
　├ script              # javascript置き場(compileされて public/assets/javascript に展開されます)
　├ scss              　　　　# scssファイル置き場(compileされて public/assets/css に展開されます)
　└ views              　　# ejs(html)ファイルの置き場(compileされて public に展開されます)
```

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
