## swagger-multi-file-docker
### 概要
ファイル分割さらたswagger定義ファイルを編集しつつ、swagger-uiとredocで表示

### 起動

```
$ docker-compose build
$ docker-compose up -d
```

### 確認
#### swagger-ui
https://localhost:8001

#### redoc
https://localhost:8002

#### redoc静的HTMLで確認
`docs/redoc.html` を開いて確認

#### ブラウザ同期

`browser-syncの確認` のブラウザ同期の確認のため下記を実行する

```
% cd ./redoc-cli
% yarn install
% yarn run server
```

任意のopenAPIのymlファイルを更新したらブラウザが自動でリロード+変更点が反映されることを確認